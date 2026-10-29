# YINGHE Studio 3.3.3 / 映核

## Start / 开始使用

Extract the entire ZIP into a writable folder, then run YINGHE-Studio.exe. Prepare FFmpeg and FFprobe as described in INSTALL.md. Windows 10/11, 64-bit, with .NET Framework 4.8 is recommended.

请完整解压到可写入的文件夹，再运行 YINGHE-Studio.exe。请按 INSTALL.md 另行准备 FFmpeg 与 FFprobe。建议使用 64 位 Windows 10/11 和 .NET Framework 4.8。

Drag videos into the queue, choose processing options, preview, then export. Output defaults to output beside the program. An output frame rate of 0 preserves source timing unless another effect requires adjustment.

拖入视频，设置参数，预览后开始导出。默认输出到程序旁的 output 文件夹。输出帧率 0 表示保持原视频帧率；抽帧等功能仍会改变视频时间戳或帧分布。

## Free and Pro / 免费版与专业版

Free works immediately, without registration. It allows 10 successful full exports per local calendar day. Preview, failed and cancelled tasks do not consume the quota. Restarting the program preserves usage. Keep Windows date, time and timezone correct.

免费版无需注册，每个本地自然日可成功导出 10 个视频。预览、失败、取消不计数，重启后保留用量。请保持 Windows 日期、时间和时区正确。

Pro is US$49 for 365 days, for one active computer, without automatic renewal. Buy at https://yinghe.org/buy.php. After payment confirmation, the code is emailed to the checkout address. Enter it in License & quota and activate online once; later use is supported offline. Check junk mail, or recover the code at https://yinghe.org/account.php.

专业版为 49 美元 / 365 天，同时激活一台电脑，不自动续费。请在 https://yinghe.org/buy.php 购买；付款确认后，注册码发送到付款邮箱。在“授权与额度”输入注册码，首次联网激活后可离线使用。未收到邮件请检查垃圾邮件，或在 https://yinghe.org/account.php 找回。

To transfer, connect the old computer to the internet and unbind it, then activate the original code on the new computer. Expiry or unbinding restores Free and preserves that day's usage. Pro exports also count toward the usage retained after downgrade. Offline devices cannot be revoked instantly; do not keep duplicate copies of an old authorization.

换机时，请在旧电脑联网解绑，再在新电脑用原注册码激活。到期或解绑后恢复免费版，当日用量保留。专业版成功导出也会记录用量。已离线的旧授权无法即时远程撤销，请勿保留旧授权副本同时使用。

Coffee support is optional and does not include a Pro license: https://yinghe.org/support.php.

“买我一杯咖啡”为自愿支持，不包含专业版授权。

## Editing / 编辑功能

Color adjustments use sliders with editable numeric values. Presets populate all controls, so you can see and refine the complete look. Manual edits switch the selection to Custom. Use ↺ or double-click a slider to reset one value, or Reset color to restore all controls. Select a video, then Preview color to check a five-second sample; it does not use an export.

色彩调整采用滑块与数字双向同步。选择预设会更新全部调色数值，随后可微调；手动修改后显示“自定义”。点击 ↺ 或双击滑块可恢复单项，“重置色彩”恢复全部。选中视频后点击“预览调色”查看五秒效果，不扣导出次数。

The controls include exposure in EV, brightness, contrast, saturation, vibrance, highlights, shadows, temperature, green/magenta tint, gamma and hue. Presets include Natural, Portrait, B&W, Cinema, Warm, Cool, Vivid, Vintage, Faded film and High contrast. Positive temperature is warmer; positive tint is more magenta. Older saved presets are converted once to visible parameters; their appearance may differ slightly from the older stacked-filter version.

提供曝光 EV、亮度、对比度、饱和度、自然饱和度、高光、阴影、冷暖色温、绿／洋红、伽马和色调。新增自然、人像、复古、褪色胶片、高对比预设。色温正值偏暖，绿／洋红正值偏洋红。旧版本保存的预设会一次性转成可见参数，与旧版叠加滤镜的外观可能略有差异。

- Watermark: image position, top/bottom center, size, margin, coordinates and opacity.
- Picture in picture: image or video overlay; short video loops; overlay audio is not mixed.
- Intro/outro: choose an image or video to enable; clear its path to remove. Images use an integer duration; video selection reads its full duration.
- Trim start/end, crop, playback speed, frame removal, subtle animated zoom, resolution, rotation, flips, bitrate and color presets.

水印与画中画的“不透明度”：0 为全透明，100 为完全显示。片头片尾选文件即添加，清空即取消。图片可设置整数秒，选择视频后自动读取完整长度。旋转与翻转默认关闭。

## Data and support / 数据与支持

Settings and output are stored beside the program. Authorization and daily usage are stored per Windows user in %LOCALAPPDATA%\YINGHE\Studio. Do not delete this directory to repair settings: missing or damaged usage records can block export.

设置与输出保存在程序文件夹，授权与额度保存在当前 Windows 用户的 %LOCALAPPDATA%\YINGHE\Studio。请勿通过删除授权数据目录来重置设置或次数；记录丢失或损坏会阻止导出。

If a GPU encoder fails, the app retries with CPU H.264. Support: licenses@yinghe.org. Include the app version and error text; do not send payment card details, API keys or your license code publicly.

显卡编码失败时会尝试 CPU H.264。支持邮箱：licenses@yinghe.org。反馈时请提供版本号和错误信息，不要公开银行卡资料、支付私钥或注册码。

This lightweight public package does not bundle FFmpeg. Obtain FFmpeg/FFprobe separately through the official FFmpeg download page and preserve their licenses. See INSTALL.md.
