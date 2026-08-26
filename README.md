# Temp

Temp is unused Visual Studio 2003 scratch with a stock empty VB.NET WinForms Test app and a Setup1 installer project. It is not a product: `Test/` is the default WinForms template (`Test.sln` / `Test.vbproj` / `Form1.vb`) whose Form1 has title Form1 and no controls. `Setup1/` is a Visual Studio setup project (`Setup1.sln` + `Setup1.vdproj`) that would output `Setup1.msi`, with empty Debug/Release directories and no files in the installer. Assembly attributes are blank template defaults; the setup project's manufacturer and ARP contact is Empired Limited.

**Source last updated:** 2005-06-15 · **Language:** VB.NET · **Target:** .NET Framework (Visual Studio .NET 2003, ProductVersion 7.10.3077) · **Output:** WinForms WinExe + MSI setup project

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Test` | VB.NET | WinForms WinExe | Stock empty Form1 (title Form1, no controls); startup object `Test.Form1` |
| `Setup1` | Visual Studio setup | vdproj / MSI | Default Setup1 installer; empty Debug/Release; manufacturer Empired Limited |

## How to open

Open `Test/Test.sln` in Visual Studio .NET 2003 for the WinForms app. Open `Setup1/Setup1.sln` in Visual Studio .NET 2003 with Visual Studio Installer for the setup project. Later Visual Studio versions do not load VS 2003 `.vbproj` / `.vdproj` without a conversion.

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `Temp`. `Test` assembly title, description, company, product, and copyright are empty Visual Studio template defaults (ProductVersion 7.10.3077, solution format 8.00). `Setup1.vdproj` ProductName/Title `Setup1`, ProductVersion 1.0.0, Manufacturer and ARPCONTACT Empired Limited.

## License

MIT. Copyright (c) 2026 VaderConsulting, for Dave Robinson's code. See `LICENSE`.
