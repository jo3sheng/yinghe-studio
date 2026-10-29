# Install YINGHE Studio / 安装映核

## Windows 3.3.3 complete portable package

1. Use 64-bit Windows 10/11 with .NET Framework 4.8.
2. Download **YINGHE-Studio-3.3.3-Windows.zip** from [the official Windows release](https://github.com/jo3sheng/yinghe-studio/releases/tag/v3.3.3). The matching **.zip.sha256** file contains the owner's SHA-256 checksum.
3. Extract the entire ZIP into a writable folder.
4. Keep the **ffmpeg** folder beside **YINGHE-Studio.exe**. FFmpeg, FFprobe and their required DLLs are bundled; a separate installation is not needed. Do not mix files from different FFmpeg builds.
5. Run the app, add a short video and check a five-second preview before processing the full queue.

The original owner's software ZIP and checksum are distributed unchanged. The package contains the user guide, release notes and third-party notices/licenses. Hardware encoding still depends on compatible GPU hardware, drivers and the bundled FFmpeg build.

The executable is not presented as a newly code-signed release. Windows may show publisher/reputation prompts depending on device settings. Do not disable system-wide protection; use the official files and contact licenses@yinghe.org if installation is blocked.

Free works without registration. Pro requires online activation and supports subsequent offline processing.

## Windows 中文步骤

下载 **YINGHE-Studio-3.3.3-Windows.zip**，完整解压到可写入目录，再运行 **YINGHE-Studio.exe**。FFmpeg、FFprobe 及配套 DLL 已在 ffmpeg 文件夹中，无需另行安装。请保留整个文件夹结构，并用配套 .sha256 文件核对下载。此完整包取代此前临时发布的 Windows-App 轻量包。

## macOS 1.1.6 complete package

1. Use an Apple Silicon Mac (arm64), macOS 13 or later. This ZIP does not support Intel Macs.
2. Download **YINGHE-Studio-1.1.6-MAC.zip** from [the Mac release](https://github.com/jo3sheng/yinghe-studio/releases/tag/v1.1.6-macos).
3. Extract the complete ZIP. It contains **YINGHE Studio.app** and a **Manuals** folder. Keep the application's Contents/Resources intact.
4. Open the app and consult the version-specific PDF guide. FFmpeg and FFprobe are already bundled; a separate installation is not required.
5. The [nine-language manuals ZIP](https://github.com/jo3sheng/yinghe-studio/releases/download/v1.1.6-macos/YINGHE-Studio-1.1.6-Manuals-9-Languages.zip) provides the same PDFs independently of the software download.

The ZIP is redistributed unchanged as supplied by the owner. This upload check verified archive integrity, arm64 executable format/permissions and PDF readability on Windows; it did not independently verify Apple Developer ID signing, notarization or runtime behaviour on a Mac.

Mac 1.1.6 需 Apple Silicon 和 macOS 13 及以上。完整解压后可见 YINGHE Studio.app 与 Manuals 文件夹；FFmpeg、FFprobe 已内置，无需另外安装。请按对应语言的 PDF 手册操作。本次原样上传，不宣称在 Mac 上重新复测或验证 Apple 公证状态。
