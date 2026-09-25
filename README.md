# 模组有趣功能提取

一个非官方的《空洞骑士》模组功能整理与再实现项目。

本仓库主要从社区公开的《空洞骑士》模组中筛选有趣的功能，提取、移植、重写或组合其部分设计思路与实现，并做适度调整，让这些功能更符合个人喜好、更有趣，或更适合与其他模组搭配使用。

## 项目简介

《空洞骑士》拥有活跃的模组社区，许多模组作者创造了非常有趣的功能和玩法。本项目源于对这些模组的兴趣，目标是对其中一些有趣功能进行整理、学习和再实现，并加入一些个人化的改动。

本项目不是官方项目，也不是简单的“整合包”。它更偏向于个人兴趣驱动的实验性仓库，可能包含：

- 从公开模组中获取灵感并重新实现的功能；
- 对原有功能进行轻量修改、增强或组合；
- 为个人玩法偏好定制的实验性改动；
- 对部分模组机制的移植、适配或兼容性调整。

## 主要特点

- 收集并整理《空洞骑士》社区模组中的有趣机制；
- 对原功能进行适度改造，使其更符合个人玩法；
- 可能包含多个独立小功能或实验性补丁；
- 持续更新，内容取决于个人兴趣和时间；
- 可能与其他模组存在冲突，使用前请自行测试。

## 安装与使用

请根据具体功能说明进行安装。通常情况下，模组文件需要放入《空洞骑士》的 `Mods` 文件夹中，并确保已正确安装 Hollow Knight Modding API 或相关依赖。

在使用前，请务必：

1. 备份你的游戏存档；
2. 确认当前游戏版本与模组兼容；
3. 一次只添加少量模组，方便排查冲突；
4. 阅读具体功能对应的说明文件。

## 免责声明

1. **非官方项目**  
   本项目是非官方、非商业的个人兴趣项目，与 Team Cherry、Hollow Knight 官方、Steam、GOG 以及任何原模组作者均无隶属、合作、授权或认可关系。

2. **版权归属**  
   《空洞骑士》及其相关内容的版权归 Team Cherry 及其相关权利方所有。社区模组中的代码、美术、音频、文本、设计等版权归各自原作者所有。本项目不声称拥有任何第三方内容的版权。

3. **仅用于学习与交流**  
   本项目主要用于个人学习、模组研究、技术交流和娱乐。请勿将其用于商业用途，包括但不限于售卖、付费下载、付费整合、众筹、广告盈利或捆绑销售。

4. **遵守原模组许可证**  
   如果本仓库包含、引用、修改或分发来自第三方模组的内容，请务必遵守原项目的许可证和授权条款。若原模组许可证禁止修改、再分发或公开传播，请不要使用或分发相关内容。建议优先参考原模组思路并进行独立实现，而不是直接复制受限制的代码或资源。

5. **风险自负**  
   使用本模组或本仓库中的任何内容可能导致游戏崩溃、存档损坏、进度丢失、性能下降、模组冲突或其他异常情况。请在安装前备份存档和游戏文件，并自行承担使用风险。

6. **无担保**  
   本项目按“现状”提供，不提供任何明示或暗示的担保，包括但不限于可用性、稳定性、兼容性和安全性。作者不对因使用本项目而产生的任何直接或间接损失负责。

7. **关于版权**
  本仓库只修改采用`Creative Commons Zero v1.0 Universal` 授权或其他支持二次修改、以及分发的项目

8. **侵权处理**  
   如果您是原作者，并认为本仓库中的内容侵犯了您的权益，或您不希望自己的作品被引用、修改、分发，请通过 Issue 或邮箱 `3807260848@qq.com` 联系我。我会在确认后尽快删除、修改或调整相关内容。

9. **请支持正版与原作者**  
   请支持《空洞骑士》正版，也请尊重和支持社区模组作者的劳动成果。如果某个功能来自他人的模组，请在可能的情况下注明来源并给予致谢。

   
## 版权与许可

- 本仓库中由我原创的部分，除非另有说明，采用 `Creative Commons Zero v1.0 Universal` 授权。
- 第三方内容遵循其原项目许可证。
- 未明确声明许可证的部分，默认保留所有权利。
- 如果你计划分发、修改或二次使用本项目，请先确认相关内容的授权情况。

## 致谢

感谢 Team Cherry 创作了《空洞骑士》。  
感谢所有社区模组作者、工具作者和文档贡献者。  
如果没有他们的工作，本项目中的许多灵感和功能探索都不会存在。

## 联系

如有问题、建议或侵权相关事项，请通过 GitHub Issue 或 `3807260848@qq.com` 联系。




# Interesting Feature Extractions from Mods

An unofficial Hollow Knight mod feature organization and reimplementation project.

This repository mainly selects interesting features from publicly available Hollow Knight mods in the community, extracts, ports, rewrites, or combines some of their design ideas and implementations, and makes moderate adjustments so that these features better fit personal preferences, are more interesting, or are more suitable for use alongside other mods.

## Project Introduction

Hollow Knight has an active modding community, and many mod authors have created very interesting features and gameplay. This project stems from an interest in these mods. Its goal is to organize, study, and reimplement some interesting features, while adding some personal changes.

This project is not an official project, nor is it a simple "modpack." It is more of an experimental repository driven by personal interest and may include:

- Features inspired by public mods and reimplemented;
- Lightweight modifications, enhancements, or combinations of original features;
- Experimental changes customized for personal gameplay preferences;
- Porting, adaptation, or compatibility adjustments for some mod mechanics.

## Main Features

- Collect and organize interesting mechanics from the Hollow Knight community mods;
- Moderately modify original features to better fit personal gameplay;
- May contain multiple independent small features or experimental patches;
- Continuously updated, depending on personal interest and time;
- May conflict with other mods; test before use.

## Installation and Usage

Please install according to the specific feature instructions. Usually, mod files need to be placed in the `Mods` folder of Hollow Knight, and Hollow Knight Modding API or related dependencies must be correctly installed.

Before use, please be sure to:

1. Back up your game saves;
2. Confirm that the current game version is compatible with the mod;
3. Add only a few mods at a time to make conflict troubleshooting easier;
4. Read the instruction file corresponding to the specific feature.

## Disclaimer

1. **Unofficial Project**  
   This project is an unofficial, non-commercial personal interest project. It is not affiliated with, partnered with, authorized by, or endorsed by Team Cherry, Hollow Knight official, Steam, GOG, or any original mod author.

2. **Copyright Ownership**  
   The copyright of Hollow Knight and related content belongs to Team Cherry and its relevant rights holders. The copyright of code, art, audio, text, designs, etc. in community mods belongs to their respective original authors. This project does not claim ownership of any third-party content.

3. **For Learning and Communication Only**  
   This project is mainly for personal learning, mod research, technical exchange, and entertainment. Please do not use it for commercial purposes, including but not limited to selling, paid downloads, paid compilations, crowdfunding, advertising revenue, or bundled sales.

4. **Comply with Original Mod Licenses**  
   If this repository contains, references, modifies, or distributes content from third-party mods, you must comply with the license and authorization terms of the original projects. If the original mod license prohibits modification, redistribution, or public distribution, please do not use or distribute the relevant content. It is recommended to prioritize referencing the original mod's ideas and implementing them independently, rather than directly copying restricted code or resources.

5. **Use at Your Own Risk**  
   Using this mod or any content in this repository may cause game crashes, save corruption, progress loss, performance degradation, mod conflicts, or other abnormal situations. Please back up saves and game files before installation, and you assume the risks of use yourself.

6. **No Warranty**  
   This project is provided "as is" without any express or implied warranties, including but not limited to availability, stability, compatibility, and safety. The author is not responsible for any direct or indirect losses caused by the use of this project.

7. **Regarding Copyright**  
   This repository only modifies projects licensed under `Creative Commons Zero v1.0 Universal` or other projects that support secondary modification and distribution.

8. **Infringement Handling**  
   If you are an original author and believe that the content in this repository infringes your rights, or you do not want your work to be referenced, modified, or distributed, please contact me through an Issue or email at `<3807260848@qq.com>`. After confirmation, I will delete, modify, or adjust the relevant content as soon as possible.

9. **Please Support the Official Game and Original Authors**  
    Please support the official version of Hollow Knight, and respect and support the work of community mod authors. If a feature comes from someone else's mod, please credit the source where possible and give thanks.

## Copyright and License

- Unless otherwise stated, the parts of this repository originally created by me are licensed under `Creative Commons Zero v1.0 Universal`.
- Third-party content follows the licenses of its original projects.
- For parts without an explicit license, all rights are reserved by default.
- If you plan to distribute, modify, or reuse this project, please first confirm the authorization status of the relevant content.

## Acknowledgements

Thanks to Team Cherry for creating Hollow Knight.  
Thanks to all community mod authors, tool authors, and documentation contributors.  
Without their work, many of the inspirations and feature explorations in this project would not exist.

## Contact

If you have questions, suggestions, or copyright-related matters, please contact me through a GitHub Issue or `3807260848@qq.com`.
