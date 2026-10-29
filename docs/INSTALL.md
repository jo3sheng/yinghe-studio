# Install YINGHE Studio / 安装映核

## Windows 3.3.3 lightweight package

1. Use 64-bit Windows 10/11 with .NET Framework 4.8.
2. Download YINGHE-Studio-3.3.3-Windows-App.zip from the official release. Extract the entire ZIP into a writable folder.
3. Obtain a Windows FFmpeg build through the links on [FFmpeg's official download page](https://ffmpeg.org/download.html#build-windows). Keep the provider's notices and licenses.
4. Create an ffmpeg folder next to YINGHE-Studio.exe. Copy ffmpeg.exe and ffprobe.exe into it, together with every DLL required by that build. Do not mix files from different FFmpeg builds.
5. Run YINGHE-Studio.exe, add a short video and use the five-second preview before processing the full queue.

The app also allows choosing an existing FFmpeg executable. FFprobe must be beside it. H.264 export requires libx264 or a compatible supported hardware encoder; not every FFmpeg build includes every effect or encoder. Filters primarily use the CPU.

The executable is currently unsigned. Windows security behavior depends on the device's settings. Do not disable antivirus or system-wide protection to install the app; use the official distribution, verify the hash, and contact support if installation is blocked.

Free works without registration. Pro activation requires internet; routine processing can be offline after activation. Keep your purchased registration code private.

## Windows 中文步骤

1. 建议 64 位 Windows 10/11 和 .NET Framework 4.8。
2. 下载 Windows-App.zip，并完整解压到可写入目录。
3. 通过 [FFmpeg 官方下载页](https://ffmpeg.org/download.html#build-windows)获取 Windows 版本，保留其许可证及说明。
4. 在 YINGHE-Studio.exe 同目录建立 ffmpeg 文件夹，放入 ffmpeg.exe、ffprobe.exe 及该版本需要的全部 DLL。
5. 打开软件，先用短视频做五秒预览。也可在软件中选择现有 FFmpeg 路径；FFprobe 需与它同目录。

此公开包不附带 FFmpeg，不会把授权后台、注册码、个人设置或测试日志放入安装包。不要将不同 FFmpeg 版本的文件混用。

## macOS 1.1.6 complete package

1. Use an Apple Silicon Mac (arm64), macOS 13 or later. This ZIP does not support Intel Macs.
2. Download **YINGHE-Studio-1.1.6-MAC.zip** from [the Mac release](https://github.com/jo3sheng/yinghe-studio/releases/tag/v1.1.6-macos).
3. Extract the complete ZIP. It contains **YINGHE Studio.app** and a **Manuals** folder. Keep the application's Contents/Resources intact.
4. Open the app and consult the version-specific PDF guide. FFmpeg and FFprobe are already bundled; a separate installation is not required.
5. The [nine-language manuals ZIP](https://github.com/jo3sheng/yinghe-studio/releases/download/v1.1.6-macos/YINGHE-Studio-1.1.6-Manuals-9-Languages.zip) provides the same PDFs independently of the software download.

The ZIP is redistributed unchanged as supplied by the owner. This upload check verified archive integrity, arm64 executable format/permissions and PDF readability on Windows; it did not independently verify Apple Developer ID signing, notarization or runtime behaviour on a Mac.

Mac 1.1.6 需 Apple Silicon 和 macOS 13 及以上。完整解压后可见 YINGHE Studio.app 与 Manuals 文件夹；FFmpeg、FFprobe 已内置，无需另外安装。请按对应语言的 PDF 手册操作。本次原样上传，不宣称在 Mac 上重新复测或验证 Apple 公证状态。
