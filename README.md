<div align="center">
  <h1 align="center">WorldNamePacket-Updated</h1>
  <p>世界名称数据包-高版本支持</p>
</div>

<div align="center">
  <a href="./LICENSE">
    <img src="https://img.shields.io/github/license/xmmtx/World-Name-Packet" alt="License" />
  </a>
  <a href="https://www.xm233.cn/sponsor">
    <img src="https://img.shields.io/badge/%24-sponsor-F87171.svg" alt="Sponsor" />
  </a>
</div>

中文 | [English](./README_en-us.md)
## 简介
服务器端映射模组伴侣。自动设置世界名称
在多世界模式下 - 无需手动配置，且不会出现“世界未识别”的情况
信息。

支持的平台：Fabric、Spigot

支持的地图模组：VoxelMap、Xaero's Map、JourneyMap、Rei's Minimap。

## 功能

这个模组在特定情况下有所帮助：当你连接到服务器时
如果模组包含的维度超过原版中的三个，那么映射模组就很容易出错
并且可能会把地图弄混，或者问你正在哪个地图上。这可能会
这在许多模组服务器上都会发生——但如果有原版服务器的话，也会发生
一个代理（Bungeecord/Velocity等）。

这个工具通过告诉映射模组它连接的是哪个世界来解决这个问题。

## 安装

从“发布”部分下载一个jar文件，并将其放入你的mods/plugin文件夹中
**服务器端**。如果你正在使用代理（Bungecord/Velocity等），请确保
它安装在所有服务器上。

这个罐子在Fabric和Spigot上都能用——我知道这很糟糕。

## 配置

无需配置。该模组会自动从...读取世界名称
你的服务器配置（原版为`level-name`，模组为维度名称）。
一个常见的问题是，你所有的世界都被命名为“world”——你得改改这个了
以便该模块能正常运行。

## Forge版本在哪里？

抱歉，我不了解Forge。如果你能编写代码实现它，请告诉我！
