Music Intelligence Engine (MIE)

An AI-native toolkit for organizing and preparing DJ music libraries.
 一个面向 AI 的 DJ 音乐库整理工具。

✨ Overview | 项目简介

Music Intelligence Engine (MIE) is an open-source toolkit designed for DJs, music collectors and AI Agents.

It helps organize large music libraries safely without modifying the original files, while providing a scalable foundation for future AI-powered DJ workflows.

Music Intelligence Engine（MIE）是一个面向 DJ、音乐收藏者以及 AI Agent 的开源工具。

它能够在不修改原始音乐文件的前提下，帮助整理大型 DJ 曲库，并为未来的 AI 排歌、DJ Model、音乐分析等功能提供统一基础。

🚀 Current Features | 当前功能（v0.1.0-alpha）

✅ Scan music folders
 扫描音乐文件夹

✅ Generate Music Library (music_library.json / music_library.m3u)
 生成 Music Library 数据文件

✅ Standardize audio filenames
 标准化音乐文件名

Example:
Artist - Title (Mix Version).ext
✅ Experimental Genre Classification
 实验性音乐风格分类

✅ Safe Copy Workflow
 所有操作均复制文件，绝不修改原始音乐文件

🔒 Safety First | 安全设计

Music Intelligence Engine never modifies your original music library.

All generated files are written into a new Music Intelligence folder inside the selected music directory.

Music Intelligence Engine 永远不会修改、删除或移动原始音乐文件。

所有输出内容都会生成到所选音乐文件夹中的 Music Intelligence 目录内。

📂 Supported Formats | 支持格式

MP3
WAV
AIFF / AIF
FLAC
M4A


⚡ Quick Start | 快速开始

启动 Skill：
/Music Intelligence Engine
然后按照菜单操作：
1. 选择文件夹并扫描 / Select Folder and Scan
0、退出程序 / Exit
当前支持：
① 标准化文件名 / Normalize Filenames
② 音乐风格分类 / Classify by Genre

📁 Output Structure | 输出目录

程序会自动在所选音乐文件夹中生成：
Music Intelligence/

├── 音乐库 Library/
│   ├── music_library.json
│   └── music_library.m3u
│
├── 音乐集合 Collections/
│   ├── 标准化文件名 Filename Standardization/
│   └── 曲风分类 By Genre/
│
└── 报告 Reports/
    ├── filename_normalization_report.csv
    ├── genre_classification_report.csv
    └── metadata_debug_report.csv
原始音乐文件保持不变。

🛠 Current Status | 当前状态

Current Version

v0.1 - alpha

Implemented
Music Library Scanner
Music Library JSON / M3U Generator
Filename Standardization

音乐库扫描仪
音乐库JSON/M3U生成器
文件名标准化

🗺 Roadmap | 开发计划

v0.2
--

v0.3
--

v0.4
--

v0.5
--


⚠ Disclaimer | 免责声明

Genre Classification is currently experimental.

Classification results should be reviewed before being used in professional DJ libraries.

当前版本的音乐风格分类功能仍处于实验阶段。

建议在正式 DJ 曲库中使用前，结合分类报告进行人工确认。

❤️ Philosophy | 项目理念

Traditional music managers organize files.

Music Intelligence Engine organizes music knowledge.

传统音乐管理软件整理的是文件。

Music Intelligence Engine 整理的是音乐知识。

📄 License | 开源协议

MIT License
