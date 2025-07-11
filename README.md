# 舔狗计划
最近刚追到高中时期的白月光✨，脑子里全是和妹妹聊天的剧本📖。
工作基本停摆了，游戏也卸了，连熬夜刷剧都不敢了，怕眼圈太黑影响形象👀。
等我谈稳定了👫，再说要不要恢复正常更新！

为了追🌸白月光🌸，MD，硬生生变成了情感专家、聊天达人、朋友圈文案大师📱！

无知时尬聊白月光😅🙇‍♂️
成熟时读懂白月光🤔🙇‍♂️
恋爱时融化白月光🥰🙇‍♂️

白月光助我！喝咩！👋青春永驻！
任何尴尬：终将被绝妙话术化解🧙‍♂️！

因此我[FuJr](https://github.com/FUjr)将暂停更新一段时间📵，所有新内容暂时停更，项目进度也会放缓。
等我谈稳定了👫，再回来和大家分享我的舔狗成功学📖！
感谢理解，祝大家都能追到自己的白月光✨！
白月光，启动！

# QModem

**[中文 README](README.zh-cn.md)** | **English README**

[![Auto compile with OpenWrt SDK](https://github.com/FUjr/modem_feeds/actions/workflows/main.yml/badge.svg)](https://github.com/FUjr/modem_feeds/actions/workflows/main.yml)
[![License: MPL 2.0](https://img.shields.io/badge/License-MPL_2.0-brightgreen.svg)](https://opensource.org/licenses/MPL-2.0)

**QModem** is a comprehensive cellular modem management system for OpenWRT-based routers. It provides a LuCI-based web interface for easy administration and advanced control over various cellular modems.

This project aims to provide a stable, extensible, and user-friendly solution for integrating cellular connectivity into OpenWRT.

## Features

-   **Broad Hardware Support**: Manages a wide range of USB and PCIe cellular modems from vendors like Quectel, Fibocom, and more.
-   **Intuitive Web Interface**: A clean LuCI interface for at-a-glance status monitoring and configuration.
-   **Advanced Modem Control**: Fine-tune your connection with features like band locking, cell locking, and network mode selection.
-   **SMS and Multi-WAN**: Includes optional plugins for sending/receiving SMS and configuring multi-WAN failover/load balancing.
-   **Robust and Stable**: Designed for reliability with features like slot-based device binding and optimized AT command handling.

For a complete list of features and capabilities, please see the [User Guide](docs/user-guide.md).

## Getting Started

### Installation

To install QModem, add the custom feed to your OpenWRT build environment and select the `luci-app-qmodem` packages in `make menuconfig`.

For detailed, step-by-step installation instructions, please refer to the **[Installation Guide](docs/user-guide.md#installation)**.

### Configuration

Once installed, QModem can be configured through the LuCI web interface under the "Network" -> "QModem" menu.

For a complete walkthrough of the web interface and all configuration options, please see the **[User Guide](docs/user-guide.md)**.

## Documentation

This project maintains comprehensive documentation to help users and developers.

-   **[User Guide](docs/user-guide.md)**: The primary document for users. It covers installation, configuration, and all features of the web interface.
-   **[Developer Guide](docs/developer-guide.md)**: For those who want to contribute, adapt a new modem, or understand the inner workings of the project. It details the project structure, core scripts, and adaptation process.
-   **[Supported Hardware List](docs/support_list.md)**: A list of modems known to be compatible with QModem.

## Contributing

Contributions are welcome! Whether it's adding support for a new modem, fixing a bug, or improving the documentation, your help is appreciated.

Please start by reading the **[Developer Guide](docs/developer-guide.md)** to understand the project's structure and how to get started.

## License

This project is licensed under the Mozilla Public License Version 2.0. Please see the [LICENSE](LICENSE) file for full details.

---

**Documentation Notice**: This documentation is AI-generated. We welcome community contributions to update and improve it based on real-world usage experience.

**Note**: Commercial use of this software is strictly prohibited without prior permission.

## Acknowledgments

This project builds upon the work of several other open-source projects and communities. We extend our thanks to the developers and contributors of:

-   [Siriling/5G-Modem-Support](https://github.com/Siriling/5G-Modem-Support)
-   [fujr/luci-app-4gmodem](https://github.com/fujr/luci-app-4gmodem)
-   [obsy/sms_tool](https://github.com/obsy/sms_tool)
-   [gl-inet/gl-modem-at](https://github.com/gl-inet/gl-modem-at)
-   [ouyangzq/sendat](https://github.com/ouyangzq/sendat)
