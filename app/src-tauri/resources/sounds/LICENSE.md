# 内置提示音效来源与授权

本目录下的全部音效来自 Kenney 的 **Interface Sounds (1.0)** 素材包，授权为
[Creative Commons Zero (CC0 1.0)](http://creativecommons.org/publicdomain/zero/1.0/)——
可自由用于个人、教育与商业项目，无需署名（本项目仍在此致谢）。

来源：<https://kenney.nl/assets/interface-sounds>
镜像仓库（WAV 格式）：<https://github.com/Calinou/kenney-interface-sounds>

转换处理：ffmpeg 裁剪首尾静音（-45dB 阈值）、混为单声道、44.1kHz / 16-bit PCM WAV。

| 文件 | 原始文件 | 时长 | 默认用途 |
| --- | --- | --- | --- |
| `switch.wav` | `switch_001.wav` | ~0.12s | 录音开始 |
| `minimize.wav` | `minimize_001.wav` | ~0.25s | 进入识别处理 |
| `confirmation.wav` | `confirmation_001.wav` | ~0.28s | 识别完成 |
| `error.wav` | `error_001.wav` | ~0.13s | 识别失败 |
| `pluck.wav` | `pluck_001.wav` | ~0.06s | 可选 |
| `glass.wav` | `glass_001.wav` | ~0.18s | 可选 |
| `tink.wav` | `tick_004.wav` | ~0.05s | 简洁方案兜底音（Windows/系统音不可用）·录音开始 |
| `pop.wav` | `drop_003.wav` | ~0.07s | 简洁方案兜底音（Windows/系统音不可用）·进入识别处理 |
| `ding.wav` | `confirmation_003.wav` | ~0.30s | 可选 |
| `soft-alert.wav` | `error_008.wav` | ~0.14s | 可选 |

> 简洁方案的兜底音（tink/pop）为 simple-sound-scheme change 新增：
> 按 cometix-dictation 的极简提示音风格（macOS 系统音 Tink/Pop 的音色特征）从同一素材包
> 挑选的替代音色——Apple 系统音不可再分发，macOS 上简洁方案直接运行时引用系统音
> （与 cometix-dictation 一致），Windows 及系统音不可用时使用这两个 CC0 兜底音。

> Kenney 的原始授权声明见下（摘自素材包 LICENSE.txt）：
>
> License: (Creative Commons Zero, CC0)
> <http://creativecommons.org/publicdomain/zero/1.0/>
>
> This content is free to use in personal, educational and commercial projects.
> Support us by crediting Kenney or www.kenney.nl (this is not mandatory)
