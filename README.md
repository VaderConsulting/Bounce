# Bounce

VB6 Server Bounce Log (`Bounce.exe`) that records planned/unplanned server downtime (down/up times) into a SQL Server database via ADO data controls, with history and autocomplete helpers. Open `Bounce.vbp` in the VB6 IDE.

**Source last updated:** 2000-06-01 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Bounce` (`Bounce.vbp`) | VB6 | WinForms exe | Log planned/unplanned server downtime to SQL |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Bounce.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `MSADODC.OCX`
  - `MSDATGRD.OCX`
  - `MSDATLST.OCX`
  - `MSDATREP.OCX`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Bounce`.
Company names in project files: CSC.

## License

MIT © 2026 Vader Consulting for Dave Robinson's code. See `LICENSE`.
