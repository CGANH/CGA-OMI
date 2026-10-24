# CGA OMI — Bộ cài đặt chính thức / Official installers

Bộ cài công khai của các ứng dụng CGA OMI (cganh.com). Tải bản mới nhất ở mục **[Releases](https://github.com/CGANH/CGA-OMI/releases)**, không cần CGA Hub.

Public installers of the CGA OMI apps (cganh.com). Get the latest version from **[Releases](https://github.com/CGANH/CGA-OMI/releases)** — no CGA Hub needed.

| Ứng dụng / App | Windows | macOS | Release |
|---|---|---|---|
| CGA Hub | `.msi` / `Setup .exe` | Apple Silicon / Intel `.zip` | `cga-hub-v…` |
| CGA Edit Video | `Setup .exe` | — | `cga-edit-video-v…` |
| CGA Effect Video | `.msi` | — | `cga-effect-video-v…` |
| CGA DevC | `.msi` / `Setup .exe` | — | `cga-devc-v…` |
| CGA Photo Editing | `.msi` | — | `cga-photo-v…` |
| CGA Drafting Documents | `.msi` | — | `cga-documents-v…` |
| CGA SpreadSheet | `.msi` | — | `cga-sheets-v…` |

> Khuyên dùng **CGA Hub**: Hub tự tải đúng bản, kiểm tra chữ ký và tự cập nhật. Tải trực tiếp ở đây phù hợp khi máy không cài được Hub hoặc cần bản cũ.
> **CGA Hub** is recommended: it picks the right package, verifies it and keeps apps updated.

## Kiểm tra file tải về / Verify your download

Mỗi Release có `SHA256SUMS.txt`. So mã của file vừa tải với mã trong đó — khác nhau thì **không cài** và tải lại.

Windows (PowerShell):

```powershell
Get-FileHash .\CGAHub-1.0.11-x64.msi -Algorithm SHA256
```

macOS (Terminal):

```sh
shasum -a 256 CGAHub-1.0.11-mac-arm64.zip
```

Chỉ tải từ `github.com/CGANH/CGA-OMI` hoặc `cganh.com`. Only download from `github.com/CGANH/CGA-OMI` or `cganh.com`.

## Cảnh báo khi mở bộ cài / Security prompts

- **Windows**: nếu SmartScreen hiện “Windows protected your PC”, bấm **More info → Run anyway** sau khi đã kiểm tra SHA-256 ở trên.
- **macOS**: giải nén `.zip`, kéo ứng dụng vào **Applications**. Lần đầu mở, nhấn **chuột phải → Open** (hoặc System Settings → Privacy & Security → **Open Anyway**).

## Phần mềm bên thứ ba / Third-party software

CGA Hub có thể cài kèm **qBittorrent** (GNU GPL). Mã nguồn, giấy phép và thông báo bên thứ ba nằm trong Release của CGA Hub (`qBittorrent-*-source.tar.gz`, `THIRD-PARTY-NOTICES.txt`).

## Hỗ trợ / Support

- Website: https://cganh.com
- Zalo: https://zalo.me/g/8yj53bfqzr4n9to8jtuo
- Facebook: https://web.facebook.com/groups/cgaomi/

© CGANH. All rights reserved. Repository này chỉ chứa bộ cài đặt, không chứa mã nguồn ứng dụng.
This repository only hosts installers; it does not contain application source code.
