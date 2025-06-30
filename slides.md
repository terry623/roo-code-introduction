---
theme: default
background: "/images/background.webp"
title: Roo Code Introduction
drawings:
  persist: false
transition: slide-left
---

# Roo Code 實戰指南
## 助你效率倍增的 AI 程式助手

<!--
嗨大家，我今天要分享的題目是：

Roo Code 實戰指南，助你效率倍增的 AI 程式助手

那我是來自 AIDE 的 Terry
-->

---
layout: quote
---

# 大家或許會問：「這場簡報和我有什麼關係？」

<!--
在開始之前，我想大家心裡可能都會想問：『這場簡報… 究竟和我有什麼關係？』

因為大家都是工程師嘛，平常在 Coding 時，能輔助使用的 AI 工具也是相當多樣

那我們 AIDE 在使用 AI 工具輔助開發也是一陣子了，剛好有些實用的心得可以分享給大家參考
-->

---
layout: statement
---

## 今天將快速掌握 <span v-mark.underline.orange>Roo Code</span> 的核心用法

<br/>

## 更有效率地運用 AI 工具於日常工作

<!--
今天我們將在這場分享中，讓大家快速地掌握 Roo Code 的各種核心用法

更重要的是，透過理解它的使用方式與應用場景，可以學會如何更有效率地將 AI 這個強大的工具

真正融入到我們的日常寫程式的流程中，而不僅僅是停留在『問個問題、寫點程式碼』的應用
-->

---
layout: center
---

## 我們將聚焦三個問題

<br/>

## 1. 為什麼用？

<br/>

## 2. 什麼時候用？

<br/>

## 3. 怎麼使用？

<!--
第一：為什麼用？ 我們為什麼需要 Roo Code？它和我們已經在使用的工具有什麼本質上的區別？

第二：什麼時候用？ 在開發流程的哪些環節，Roo Code 能發揮最大的價值？

第三，也是最重要的：怎麼使用？ 我們會一起看看 Roo Code 的具體功能和操作方法。

透過這三個問題，我們就能完整地建立起對 Roo Code 的認識
-->

---
layout: statement
---

# 為什麼用？

---
layout: center
---

# 將 AI 從被動的「打字加速器」或「問答機器」
# 提升為能理解專案、自主執行任務的「代理人」

<!--
提到 AI 程式助手，許多人第一個想到的可能是 GitHub Copilot

GitHub Copilot 於 2021 年年底，最初僅提供 AutoComplete 功能。

到了 2023 年，GitHub Copilot 進一步推出 Chat 功能

這項功能讓工程師能在 IDE 使用 ChatGPT 或其他 AI 模型

當遇到問題時，工程師可以直接在 IDE 內與 AI 互動，提出問題並獲得解答

從 2025 年開始，AI 的發展進入了 AI 代理時代

簡單來說，變成在無需人類介入的情況下，根據指定目標完成相關任務。
-->

---
layout: center
---

# 得益於活躍的開源社群，功能迭代快速
# 且易於整合公司內部 AI Provider

<!--
是它的生態系統。Roo Code 的一大優勢是，它背後有一個非常活躍的開源社群

這代表什麼？代表它的功能迭代非常快速，能夠不斷吸收來自全球開發者的智慧，保持在技術的前沿

它天生就易於整合。我們可以很方便地將公司內部的 AI Provider 接入 Roo Code

這意味著我們既能享受到社群的創新力量，又能確保我們的程式碼和資料安全地保留在公司內部，符合合規要求
-->

---
layout: center
---

# Roo Code 相比 Cline 有更高度的自訂性
# 能更彈性地符合團隊標準與角色需求

<!--
在 Roo Code 中，我們可以定義團隊的程式碼規範、客製化 AI 的回應風格、甚至為不同角色設定不同的輔助模式

這種彈性，讓 Roo Code 能更好地適應我們團隊的標準與獨特的工作流程，而不是讓我們去適應工具。
-->

---
layout: statement
---

# 什麼時候用？

---
layout: center
---

# Autocomplete
能在輸入過程中即時預測並補全程式碼 -> 副駕駛

<br />

# Chat
能透過文字理解並回應使用者提問 -> 技術顧問

<br/>

# Agent
能在設定的目標和範圍內自主執行多步驟任務 -> 專案執行者

<!--
剛剛有稍微講過這個 AI 助手的歷史了
-->

---
layout: center
---

# Agent 擅長處理高層次的目標

# 開發者從「下達具體指令」

# 轉變為「委託一個任務」

<!--
我想強調一下 Agent 模式之所以強大，是因為它擅長處理『高層次的目標』。

這帶來了一個根本性的轉變：作為開發者，我們的工作重心，從過去『下達具體而微的指令』，像是『建立一個檔案』、『寫一個迴圈』、『呼叫這個 API』……

轉變為『委託一個完整的任務』。我們定義好目標和邊界，然後把執行的過程交給 AI 代理人。我們則可以抽身出來，專注在更高層次的架構設計、業務邏輯和最終結果的審核上。這才是真正意義上的『人機協作』。
-->

---
layout: statement
---

# 怎麼使用？

<!--
好，理論說了這麼多，大家一定都手癢了

接下來，我們就進入第三個，也是最實用的部分：到底該『怎麼使用』Roo Code？
-->

---
layout: section
---

# Getting Started ✍️

<!--
請大家看著我的螢幕

1. 通常會把 Roo Code 拉到右側，你就可以拉檔案

2. 安裝教學與填 API Endpoint

3. 文字輸入你的需求

4. 提及 Context

5. 切換 Modes

6. Code Actions

7. 增強提示

8. 插入圖片

9. 送出後查看 Checkpoints
-->

---
layout: center
---

# Context Mentions

<br/>

# Multiple Modes

<br/>

# Code Actions

---
layout: center
---

# Enhance Prompt

<br/>

# Image Insertion

<br/>

# Checkpoints

---
layout: section
---

# Customizing ⭐

<!--
掌握了基本用法後，我們來看看 Roo Code 的進階玩法，也就是如何讓它變得更『懂你』更『適合你的團隊』——客製化。
-->

---
layout: center
---

# Instructions
`.roo/rules/`<br/>`.roo/rules-{modeSlug}/`

<br/>

# Modes
`.roomodes`

<br/>

# Exclusions
`.rooignore`

<!--
1. Instructions

2. Modes

3. Exclusions

如果覺得在使用 Roo Code 時每次都有說明很多的 Prompt 才讓 AI 進入情況

那就可以設定團隊共用的角色，把每次重複性的東西放入設定
-->

---
layout: section
---

# MCP 🚀

<!-->
簡單來說你可以想成是 AI 應用程式的 TypeC 接口

你透過這個接口，讓 AI 可以跟你的檔案系統，git，github，postgres 等等等
-->

---
layout: center
---

# Context7
https://mcp.context7.com/mcp

<br/>

# DeepWiki
https://mcp.deepwiki.com/mcp

<!-->
MCP 大家市面上找有非常多非常多

但這邊最推薦這兩個 MCP，覺得非常實用
-->

---
layout: quote
---

# 回到第一點：「為什麼用 Roo Code？」

<!--
它不僅僅是另一個程式碼工具。它是一個能理解專案上下文、能自主執行任務、能深度客製化的『AI 開發夥伴』

你可以在你專案中，新增各種不同的角色，等於為團隊招募了很多不同技能，你想怎麼客製化的免費工程師

開發時把適合的任務直接交辦給他，告訴他最終的目標究竟是什麼

看著他去分解目標，使用各式各樣的工具，最終一步步解決問題。你再去 Review 他寫的 Code

這就是在使用 Roo Code 時的正確方式
-->

---
layout: statement
---

## 現在就開始，讓 <span v-mark.underline.orange>Roo Code</span> 成為你的 AI 開發夥伴

<!--
我們在演講後，會再分享簡報、錄影檔，還有安裝教學的文件

可以直接安裝看看，開始嘗試玩玩 Roo Code，融進平常的開發工作流程中
-->

---
layout: statement
---

# Thank you.
