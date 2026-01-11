# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 项目概述

「极速车库」是一个 HTML5 3D 跳跃游戏（跳一跳类型），用于营销推广。用户长按屏幕控制方块跳跃，赢取积分可兑换租车权益。

## 运行方式

直接在浏览器中打开 `jump_jump.html` 即可运行游戏。无需构建步骤。

## 技术栈

- **前端**: 原生 HTML5 + CSS3 + JavaScript
- **3D 渲染**: Three.js (r128 via CDN)
- **交互**: 触摸/鼠标长按控制跳跃力度

## 代码结构

游戏代码全部在 `jump_jump.html` 单文件中，包含：
- 样式 (`<style>`) - UI 组件、弹窗、动画
- 游戏逻辑 (`<script>`) - Three.js 3D 场景、游戏状态管理、积分系统

## 关键功能模块

- **3D 场景**: 跳跃平台生成、方块移动、相机跟随
- **游戏机制**: 长按蓄力、跳跃距离计算、完美跳跃判定
- **UI 系统**: 登录弹窗、结算弹窗、复活机制、积分显示
- **数据管理**: 手机号输入、本地积分存储
