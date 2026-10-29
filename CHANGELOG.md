# Release notes / 更新日志

## 3.3.3 — Windows · 2026-10-29

- Color sliders and numeric fields stay synchronized.
- Presets update visible values; manual edits select Custom.
- Exposure, highlights, shadows, vibrance and green/magenta tint controls.
- Natural, Portrait, Vintage, Faded film and High contrast presets.
- Reset individual controls or the full color configuration.
- Five-second color preview does not consume the daily export allowance.
- Existing saved color settings migrate to the visible control values; appearance may differ from older releases.

新增调色滑块与数值双向同步、曝光、高光、阴影、自然饱和度、绿／洋红控制及多个预设；支持单项和全部重置，五秒调色预览不扣导出额度。

The public lightweight package contains the application and user documents. FFmpeg/FFprobe are installed separately. macOS release availability is tracked separately.

## macOS 1.0 preview — Apple Silicon · 2026-10-29

Native SwiftUI app compiled and packaged on a Mac runner. Corrected resource bundle placement; package signature layout and basic startup checks passed. FFmpeg/FFprobe are separate dependencies. This is an unnotarized arm64 preview; full interactive media and activation acceptance is pending. No application source is published.

## macOS 1.1.6 — owner-supplied distribution · 2026-10-29

- Published the original Mac ZIP without changing its contents.
- Includes the compiled app, FFmpeg/FFprobe and nine PDF user guides.
- Separate nine-language PDF ZIP and SHA-256 checksums provided.
- Requires macOS 13+ and Apple Silicon; the earlier temporary 1.0 preview is superseded.
- No application source, backend or private configuration is published. This entry records distribution, not a claim that the app was re-tested on a Mac.
