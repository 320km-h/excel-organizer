# 第三方开源许可

本工具的 Windows 预编译包由 [PyInstaller](https://pyinstaller.org/) 打包，内含以下第三方开源库。它们各自的版权归原作者所有，均以宽松许可（MIT / BSD / Apache-2.0 / MPL-2.0 等）分发，允许随本工具一并再分发。

| 库 | 用途 | 许可 |
|----|------|------|
| [openpyxl](https://openpyxl.readthedocs.io/) | 读写 .xlsx、提取嵌入图片 | MIT |
| [Pillow](https://python-pillow.org/) | 图片处理 | HPND（MIT 风格） |
| [opencv-python](https://github.com/opencv/opencv-python) | 颜色 / 连通块后处理 | Apache-2.0（OpenCV 本体）/ MIT（封装） |
| [NumPy](https://numpy.org/) | 数值计算（OpenCV 依赖） | BSD-3-Clause |
| [dashscope](https://github.com/dashscope/dashscope-sdk-python) | 调用通义千问视觉模型 | Apache-2.0 |
| [PyYAML](https://pyyaml.org/) | 读取 config.yaml | MIT |
| [requests](https://requests.readthedocs.io/) | HTTP 客户端（dashscope 依赖） | Apache-2.0 |
| [urllib3](https://urllib3.readthedocs.io/) | HTTP 底层（requests 依赖） | MIT |
| [certifi](https://github.com/certifi/python-certifi) | CA 根证书（HTTPS） | MPL-2.0 |
| [charset-normalizer](https://github.com/jawah/charset_normalizer) | 编码探测（requests 依赖） | MIT |
| [idna](https://github.com/kjd/idna) | 国际化域名（requests 依赖） | BSD-3-Clause |
| [PyInstaller](https://pyinstaller.org/) bootloader | 打包引导程序 | GPL with bootloader exception（允许分发打包产物） |

> 本表为主要依赖，不一定穷尽全部传递依赖。各库的完整许可文本随其 Python 包一并分发，可在对应库的源码仓库或 PyPI 页面查看。
