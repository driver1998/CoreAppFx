# CoreAppFx

This is a simple demo of an UWP app running on .NET Framework.

- `main` branch is [NetCoreApp](https://github.com/driver1998/NetCoreApp) ported to .NET Framework, with WinUI 2.
- `anycpu` branch is an simplified version without WinUI 2 and is built as `AnyCPU`. Which in APPX terms is `neutral` (remember that?).

## Known issues

- F5 in VS will attach the CoreCLR debugger instead of the Desktop CLR debugger so debugging won't work. Please attach the Desktop CLR debugger manually.

## Acknowledgments

- Mile.Xaml for XAML compiler enablement
- Windows App SDK for MSIX packaging