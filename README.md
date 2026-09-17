# Netapi

Royal Australian Navy VB6 sample (project Project1, form `frmNetAPI`) that lists currently connected network resources. On form click it opens an MPR `WNetOpenEnum` for `RESOURCE_CONNECTED`, walks `WNetEnumResource` NETRESOURCE records, and prints each local drive letter alongside its remote UNC name.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Netapi.vbp`) | VB6 | WinForms exe | Lists connected drive mappings via WNetEnumResource |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Netapi.vbp`

## Requirements

- Visual Basic 6.0 IDE

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Netapi`.
Company names in project files: Royal Australian Navy.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
