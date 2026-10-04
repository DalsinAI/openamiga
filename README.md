# Open Amiga

An index of the Open Amiga family: free software for AmigaOS 3.2 (m68k) from
Dalsin Limited, made for AmigaChrome and usable on real Amigas and PiStorm.
Each project lives in its own repository with its own README and licence.

## Programs and system parts

| Repository | What it is | State, 4 October 2026 |
| --- | --- | --- |
| [openamigasocket](https://github.com/DalsinAI/openamigasocket) | OpenSocket: `bsdsocket.library`, its driver, a Commodity and network tools | Working in AmigaChrome |
| [openamigamail](https://github.com/DalsinAI/openamigamail) | OpenMail: IMAP/SMTP email client with TLS and OAuth sign-in | In progress |
| [openamigaprint](https://github.com/DalsinAI/openamigaprint) | OpenPrint: printing stack from `printer.device` to PDF and IPP printers | In progress |
| [openamigabrowser](https://github.com/DalsinAI/openamigabrowser) | OpenBrowser: WebKit-based web browser (68020+ with FPU) | In progress |
| [openamigartg](https://github.com/DalsinAI/openamigartg) | OpenRTG: RTG graphics system with `openrtg.library`, OpenGPU and Warp3D | In progress |
| [openamigamedia](https://github.com/DalsinAI/openamigamedia) | OpenMedia: `openmedia.library` for hardware video decode and encode | Designed |
| [openamigavlc](https://github.com/DalsinAI/openamigavlc) | Unofficial VLC media player port | Planned |
| [openamigaprefs](https://github.com/DalsinAI/openamigaprefs) | OpenPrefs: GadTools preferences editors | Designed |
| [openamigamulticore](https://github.com/DalsinAI/openamigamulticore) | OpenMulticore: spec and library for running jobs on extra cores | Specified |

## Library ports

Open-source libraries ported to AmigaOS 3.2 (m68k), first for OpenBrowser.
Each keeps its upstream licence; see its repository for the upstream version
and the Amiga changes. These repositories are being filled as the ports are
finished.

| Repository | Library |
| --- | --- |
| [openamigacurl](https://github.com/DalsinAI/openamigacurl) | libcurl, with TLS through AmiSSL |
| [openamigacairo](https://github.com/DalsinAI/openamigacairo) | cairo and pixman |
| [openamigafreetype](https://github.com/DalsinAI/openamigafreetype) | FreeType |
| [openamigaharfbuzz](https://github.com/DalsinAI/openamigaharfbuzz) | HarfBuzz |
| [openamigafontconfig](https://github.com/DalsinAI/openamigafontconfig) | Fontconfig |
| [openamigaxml](https://github.com/DalsinAI/openamigaxml) | XML library |
| [openamigaimage](https://github.com/DalsinAI/openamigaimage) | Image format libraries |
| [openamigasqlite](https://github.com/DalsinAI/openamigasqlite) | SQLite |
| [openamigapsl](https://github.com/DalsinAI/openamigapsl) | libpsl (Public Suffix List) |

## AmigaChrome tools

| Repository | What it is |
| --- | --- |
| [amigachrome-stoves](https://github.com/DalsinAI/amigachrome-stoves) | Cross-compiler toolchains used by AmigaChrome's Kitchen |
| [amigachrome-gameports](https://github.com/DalsinAI/amigachrome-gameports) | Game ports and compatibility work for m68k AROS |

## Licence

This index is MIT licensed (`LICENSE`, Copyright (c) 2026 Dalsin Limited).
Dalsin Limited's own projects are MIT; library ports and other third-party
code keep their upstream licences, as each repository states.
