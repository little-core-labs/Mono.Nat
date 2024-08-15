# Mono.Nat

[![NuGet version](https://badge.fury.io/nu/mono.nat.svg)](https://badge.fury.io/nu/mono.nat)

[![CLR Build status](https://ci.appveyor.com/api/projects/status/ji0fbdgaxpa7bvc0)](https://ci.appveyor.com/project/nterry/mono-nat)&nbsp;&nbsp;&nbsp;&nbsp;[![Mono Build Status](https://travis-ci.org/nterry/Mono.Nat.svg)](https://travis-ci.org/nterry/Mono.Nat)

## Description
NAT stack for Mono and .NET applications. Also available on Android and IOS is pending.

## How to Build

### Prerequisites
1. **MSBuild**: Ensure you have MSBuild installed. If you have Visual Studio installed, you should already have MSBuild. To install without Visual Studio, refer to the [MSBuild documentation](https://learn.microsoft.com/en-us/visualstudio/msbuild/walkthrough-using-msbuild?view=vs-2022#install-msbuild).
2. **Make**: Install Make for Windows from [GnuWin32](https://gnuwin32.sourceforge.net/packages/make.htm).

### Setup
1. **Add MSBuild to PATH**:
   - Locate the MSBuild.exe binary executable, typically found at `{INSTALL_LOCATION_DIR}\Microsoft Visual Studio\2022\Community\MSBuild\Current\Bin`.
   - Add this path to the `PATH` environment variable.
   - Confirm the setup by running `msbuild --version`.

2. **Add Make to PATH**:
   - Locate `make.exe`, typically found at `{INSTALL_LOCATION_DIR}\GnuWin32\bin\`.
   - Add this path to the `PATH` environment variable.
   - Confirm the setup by running `make --version`.

### Build Commands
- **Release Build**: Run `make pack`.
- **Debug Build**: Run `make`.