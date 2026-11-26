# Let's Build The House (LBTH) — 3D Multiplayer Online Game

![Unity](https://img.shields.io/badge/Unity-2019.4.30f1-black?logo=unity)
![C#](https://img.shields.io/badge/Language-C%23-512BD4)
![Game Type](https://img.shields.io/badge/Game-3D%20Multiplayer-blue)
![Project](https://img.shields.io/badge/Project-Capstone-green)

## 專案簡介｜Overview

Let's Build The House（LBTH）是一款使用 Unity 開發的 3D 多人連線小遊戲，為大學畢業專題，由團隊成員共同設計與開發。

本專案透過團隊討論制定遊戲玩法、功能需求及開發方向，並參考網路教學與技術資源，將相關技術整合至遊戲中。各成員依照不同的開發領域進行分工，最終整合為具備多人連線、場景互動、角色狀態及遊戲流程管理的遊戲作品。

本人主要負責遊戲 UI/UX 開發、場景切換流程、部分場景特效製作，以及地形負面屬性的資料管理。

## 遊戲展示｜Game Demo

- [Demo Video — YouTube](https://youtu.be/5fUnyJxTlJc)
- [Demo Game — Google Drive](https://drive.google.com/file/d/1Zm0TZ8b5T98E5yDYYekjbO0rrLzIKqAu/view?usp=sharing)

## 遊戲功能｜Game Features

- **Multiplayer Gameplay**：支援多人連線與共同遊玩。
- **Room & Lobby System**：提供房間大廳及玩家等候介面。
- **Scene Management**：管理不同遊戲階段之間的場景切換。
- **Player & Environment Status**：呈現角色及場地相關狀態資訊。
- **Object Interaction**：支援遊戲場景中的物件互動及相關操作提示。
- **Environmental Effects**：提供場景粒子特效及地形負面屬性機制。
- **Game Results**：於遊戲結束後呈現結算畫面。

## 個人開發貢獻｜My Contributions

### 1. 場景管理與切換（Scene Management）

負責不同遊戲階段的場景切換與流程銜接，使玩家能夠在等候、遊戲進行及結算等階段之間順利轉換。

### 2. 遊戲介面與使用者體驗（UI/UX Development）

負責遊戲介面的設計與功能實作，依據遊戲需求及操作流程建立對應的 UI，提供玩家清楚的資訊呈現與操作回饋。

主要負責項目包含：

- 場地狀態顯示介面。
- 角色狀態顯示介面。
- 物件互動提示及資訊顯示介面。
- 玩家等候列表。
- 多人連線房間大廳。
- 遊戲結果結算畫面。

### 3. 場景特效製作（Visual Effects）

使用 Unity Particle System 製作部分遊戲場景特效，呈現環境變化及地形效果，提升遊戲的視覺回饋與場景辨識度。

### 4. 地形屬性資料管理（ScriptableObject-Based Data Management）

使用 Unity ScriptableObject 儲存地形特效對玩家造成的負面屬性，將地形效果的參數設定與實際遊戲邏輯分離。

此設計具有以下優點：

- 集中管理不同地形的負面屬性及相關參數。
- 避免相同屬性資料於多個物件中重複宣告。
- 提高資料重用性，降低重複設定的成本。
- 透過 Unity Inspector 調整屬性，減少直接修改程式碼的需求。
- 提升地形效果系統的可維護性與擴展性。

## 技術與工具｜Tech Stack

| Category | Technology |
|---|---|
| Game Engine | Unity 2019.4.30f1 (LTS) |
| Programming Language | C# |
| Game Type | 3D Multiplayer Game |
| UI Development | Unity UI (uGUI) |
| Text Rendering | TextMeshPro |
| Scene Management | Unity Scene Management |
| Visual Effects | Unity Particle System |
| Data Management | ScriptableObject |
| Camera Tools | Cinemachine |
| Version Control | Git / GitHub |

## 團隊合作與開發流程｜Team Collaboration

本專案採用團隊分工與共同討論的開發模式，由成員共同制定遊戲設計方向、功能需求及實作方式，再依據各自負責的模組進行開發。

開發過程中，團隊透過網路教學、技術文件及相關範例學習所需技術，並依照遊戲需求進行調整、整合與測試。

透過此次專題開發，累積了以下實務經驗：

- 團隊需求討論與功能規劃。
- 遊戲功能模組化與成員分工。
- 不同遊戲系統之間的整合。
- UI 介面與遊戲狀態的串接。
- Unity 元件與資料管理機制的應用。
- 多人連線遊戲的協作開發經驗。

## 專案結構｜Project Structure

- `Assets/` — 遊戲場景、程式腳本、美術資源及相關遊戲資產。
- `Packages/` — Unity 套件與相依性設定。
- `ProjectSettings/` — Unity 專案與引擎相關設定。

## 執行方式｜Getting Started

### Requirements

- Unity Hub
- Unity Editor 2019.4.30f1
- Git

### Installation

1. Clone this repository.

   `git clone https://github.com/p89108989/project_Let-s_Build_The_House.git`

2. 使用 Unity Hub 匯入專案資料夾。
3. 使用對應版本的 Unity Editor 開啟專案。
4. 等待 Unity 完成資源匯入及相依套件安裝。
5. 開啟對應的遊戲場景。

亦可透過上方的 Demo Game 連結取得遊戲展示版本。

## 專案資訊｜Project Information

| Item | Description |
|---|---|
| Project Type | Undergraduate Capstone Project |
| Development Type | Team Development |
| Genre | 3D Multiplayer Online Game |
| My Role | UI/UX Developer & Visual Effects |
| Development Status | Completed Academic Project |

本專案為大學畢業專題之團隊共同開發成果，遊戲設計與整體功能由團隊成員共同完成。本 Repository 主要作為專題成果保存及個人開發經歷展示用途。
