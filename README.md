# Open Visual Cloud Immersive Video Samples
[![Travis Build Status](https://travis-ci.com/OpenVisualCloud/Immersive-Video-Sample.svg?branch=master)](https://travis-ci.com/OpenVisualCloud/Immersive-Video-Sample)
[![Stable release](https://img.shields.io/badge/latest_release-v1.0-green.svg)](https://github.com/OpenVisualCloud/Immersive-Video-Sample/releases/tag/v1.0)
[![Contributions](https://img.shields.io/badge/contributions-welcome-blue.svg)](https://github.com/OpenVisualCloud/Immersive-Video-Sample/wiki)

The Immersive Video Samples includes 2 samples which is based on different streaming frameworks.

OMAF samples is based on OMAF standard, uses MPEG DASH as the protocol to deliver tiled 360 video stream, and it can support both VOD and live streaming mode.

The WebRTC sample enables 360 tiled streaming based on WebRTC streaming protocol and Open WebRTC Toolkit media server framework to support low-latency.

Both of the samples use SVT-HEVC with MCTS supported to do 360 video tiled encoding and achieve Real-time performance for 4K and 8K contents.

# What's in this project
The Immersive Video Sample contains below components:
-  **Source Code** of the components which is necessary to build the samples. Please refer to [src](src/README.md) for details.
-  **OMAF Sample**: Immersive 360 Video streaming sample based on OMAF standard which uses MPEG-DASH to delivery Tiled 360 video. Please refer to [OMAF Sample Readme](OMAF-Sample/README.md) for details.
-  **WebRTC Sample**: use WebRTC streaming protocol and Open WebRTC Toolkit media server framework to do low-latency live streaming for Immersive 360 Video. Please refer to [WebRTC Sample Readme](WebRTC-Sample/README.md) for details.

# System requirements
## Operating system
The Immersive Video samples may run on Linux* 64 bit operating systems. The list below represents the operating systems that the samples were tested and validated on:
- **Client**: CentOS 7.6 or Ubuntu* 18.04 Server LTS
- **Server**: CentOS 7.6

# License
OMAF samples is licensed under OSI-approved BSD 3-Clause license and LGPLv2.0 license for different components, see [OMAF-Sample LICENSE](src/LICENSE);

WebRTC Samples is licensed under Apache License 2.0. See [WebRTC-Sample LICENSE](WebRTC-sample/owt-server/LICENSE) for details.

# How to contribute
See [CONTRIBUTING](CONTRIBUTING.md) for details. Thank you!

# How to report bugs
Use the [Issues](https://github.com/OpenVisualCloud/Immersive-Video-Sample/issues) tab on GitHub.
