# 大綱:

如何將傳統機器人領域跟AI結合, 目前機器人的趨勢

## 從AI+Expo展看無人科技新趨勢: Anduril的啟示

### Anduril:

是一家公司, 用AI平台做無人機, 無人台等等
較好的產品有**雷達站, Ghost無人機, Dive XL 自主無人潛艦**

Castelion也是類似的公司?

### 目前AI技術:

用AI做影片來播放給大家 → 只做一次加字幕的修改
在看的當下沒有發現是AI做的影片, 很逼真

### AI的發展如何顛覆現在作戰模式?

- **DL, RL:**
    - 目標自動識別
    - 自主決策
- **邊緣AI與小型模型:**
    - 無通訊環境反應
    - 現場即時感知運算
- **生成式AI:**
    - 戰場摘要生成
    - NLP

### Physical AI的時代即將來臨:

- **AI三要件: 算力, 資料, Algorithm**
- **AI演化流程: 感知型AI → 生成式AI → Agentic AI → Physical AI**
- 專門用來訓練robot和自駕車的**Cosmos** model, 生成擬真的影片數據, 加速機器人實現智慧與自主

### AI Agent例子:

- **Manus:** 號稱全球真正的通用型AI, 例如寫PPT, 找房子, 篩選履歷等等

### AI for 戰場:

- 衛星, 雷達, 無人機訊息等整合與應用
- 戰場決策輔助系統: **Lattice AI**
- 模擬戰場行動與預測, 攻擊偵測和資安防禦
- **Dual Use: 軍民皆通用**
無人機取代高價的武器
- 可能會用軟體定義戰爭, AI協同決策
- 小型廉價無人機配合AI的大規模部署, 可以比傳統武器更具優勢 → 台灣在半導體, 電子製造經驗是轉型國防創新的基礎

### AI + Expo展:

- 350+研討活動, 181家參與, 在美國華盛頓舉行
- OpenAI有部門for government, 用內部模型確保政府的資料安全, 且是小型輕量的專用model for 特定任務
- **主要主題: AI x 陸海空無人載具, AI x 國防服務, AI x 戰場預測**
- **公司: Palantir, BostonDynamics**
- BostonDynamics發展軍用機器狗搭配機械臂, 用來巡檢, 幫警察擋子彈, 在加入Computer Vision後可執行自主任務,
- **Google and Microsoft:**

|  | **Google** | **Microsoft** |
| --- | --- | --- |
| **個人** | NotebookLM運用, Gemini | Microsoft Compilot |
| **代理人** | AgentSpace可串接, 管理多個Agent | Copilot Studio |
| **邊緣AI平台** | Google Distributed Cloud | AI Foundry提供客製化AI開發平台 |

### AI x 國防公司:

ANADYR, picogrid, Hidden level

### AI 新創國防公司:

ANDURIL, APEX, CASTELION, EPIRUS, FIRESTORM

### Palantir: 政府高度依賴的資料分析工具

### **GHOSTROBOTICS:**

**軍用機器狗**

## 工業機器人在智慧製造的應用與展望

### Delta Smart Manufacturing Digital Twin Based on NVIDIA Omniverse

### **DIATwin Virtual Machine Development Platform:**

建立高擬真虛擬機台模型，支援離線參數調整、路徑規劃、模擬驗證等功能。可實現與實際控制系統間的無縫切換（virtual‑physical integration）。模擬準確度達 95–99%

### Why 協作型機器人不導入到工廠?

因為速度反而較慢, 精度也不夠準確

### Virtual world connected to physical world

會讓成果符合更真實的結果

**CAMIS: Collaborative Assembling Monitoring and Inspection System Introduction:**

分成Manual Operation, Human-Robot Collaboration, Automated Operation

是否能在品質保證的情況下完成自動化工作

## 2025美國AUTOMATE與德國AUTOMATICA的觀察

### 2025AUTOMATE (美國底特律自動化與機器人展):

- **目前工業化巨頭公司:**
    - SIEMENS
    - NVIDIA
    - ABB: **最新一代OmniCore控制平台**
    - FANUC: **CRX協作型機器人, 應用在汽車噴塗與零件搬運, 工業機器人和協作型機器人的界線會越來越模糊**
    - Mobile Industrial Robots
    - Universal Robots(UR)
    - Harmonic Drive LLC(HD)
    - Industry 4.0 Accelerator
- Teradyne Robotic整合UR和MiR技術, 並且購併機器人公司, 像是AutoGuid, MiR, Universal Robots等等
- Cognex, Keyence算是前兩大AI視覺檢測, 3D感測器的公司
- ATI Industrial Automation**賦予機器人觸覺能力**

### 2025 AUTOMATICA (德國慕尼黑機器人技術展):

- **Around 47,500. visitors, over 1,100 robots exhibited, Around 800 exhibitors**

### AI推動機器人的應用:

- 用來引導機器人的機器視覺
- **機器人控制與指令:** KUKA與SIEMES可讓User透過NLP來管理robot, 包括下達指令, 進行故障排查和維護操作
- 規劃, 優化機器人的移動路徑: YASKAWA的Motoman NEXT系列機器人, 搭配AI機器視覺以及自適應路徑規劃功能, 來完成無碰撞路徑的拾取與放置作業
ABB也有推出路徑規劃的機器人控制軟體, 將感知功能嵌入至機器人控制器中

### 廠商在展會上發佈的協作機器人作品:

- Comau的MyCo系列
- 台達電的D-Bot協作機器人
- EPSON首款協作機器人AX6
- Hyundai Robotics的HDC36與HDC50

### 設備整合機器人的新技術平台:

- **SRCI: Standard Robot Command Interface**
透過profinet的SRCI (標準機器人指令介面) 的統一標準 來將機器人控制指令轉換到PLC開發環境中, 讓developer不需使用機器人的programming來控制機器人
- 保留 / 省略機器人專用控制器
- 機器人與PLC系統的整合

### 人型機器人展示:

NEURA Robotics是德國最具代表的人型機器人公司, 最近發布了4NE1 Gen-3

### 中國機器人勢力龐大:

- 在AUTOMETICA展覽中, 有800多家大概有**1/4**都是大陸的, 非常厲害
**ex: 新松機器人, 越疆機器人, 埃夫特智能機器人**
- 由於**稀土磁石對人性機器人非常重要**, 又**70%的稀土磁石來自中國**, 所以中國機器人業才會那麼強大

### AI與機器人技術發展的交匯:

| 年代 | AI | 機器人技術 |
| --- | --- | --- |
| 1960 | 符號主義 & 專家系統 
(試圖模擬人類思考) | 自動化 & 工業機器人 (有高效率的重複操作, 但缺乏自主性和靈活性, 沒有大腦, 眼睛, 觸感) |
| 1980 | ML & DL (真實世界數據蒐集) | 移動和協作機械臂 (嘗試感知環境) |
| 2000 | 瓶頸: 如何在複雜動態環境中有效運行 | 瓶頸: 可執行單一任務, 但難以適應非結構化環境 |
| 2010 | AI需要**身體**去感知 | 機器人需要更強**大腦** |
| 2025 | 將**AI的大腦**以及**機器人的身體**融合:
1. 感知與交互融合
2. 學習與適應結合
3. 決策與執行統一
4. 軟硬體協同進化 | 同AI |

### 佔機器人成本70%的執行機構:

- **旋轉執行器:** 多用於機器人關節處, 像手腕, 膝關節的靈活轉動
- **線性執行器:** 多用於機器人大臂和下肢, 像手臂和腿部伸展
- **末端執行器:** 機器人腕部末端

### 六維力矩感測器: 歐美廠商主導

- 中國業者採用MEMS方法來降低成本 (MEMS體積小, 耗能低)

### 實現機器人力矩感測的產品:

電流環, 力矩感測器, 電子皮膚

### 以特斯拉為例:

### 結語:

- 參展商數量明顯增加, AI和機器人已深度融合, 因此機器人已不再是機械化工具, 而是環境適應的智慧夥伴
- 幾乎所有的機器人業者都是販售機器人 + AI, 已不再單純販售機器人
- 發展機會: **機器視覺, 力觸覺感測技術, 聚醚醚酮(PEEK)材料**

## MOTONEXT 工業機器人最新技術介紹:

- 安川電機公司

### i3 - Mechatronics概念

- integrated
- intelligent
- innovative
- **YASKAMA Cockpit**是實現i3-Mechatronics的核心軟體工具, 以下是特點:
    - 產線中各式各樣的設備皆能連結
    - 可利用YCP去進行AI數據分析
    - 能與ERP (綜合業務系統), MES(製造執行系統)及大數據server建立數據連結

### MOTOMAN NEXT系列:

將人員的作業更加自動化 (包含自我判斷, 自我狀況的把握)

# Remarks:

- **Delta Digital Twin:** 台達電針對工業自動化, 智慧製造的虛擬實體整合平台
- **Digital Twin:** 將實體系統在虛擬環境中建模, 並與真實世界數據雙向連結
- **NPI, New Product Introduction:** 新產品導入
    - 在虛擬環境中建模與模擬整條生產線
- **MP, Mass Product:** 量產階段
    - 模組化的 RTM 容易調整，使生產線能快速適應不同產品需求
    - 

車資：40塊+90塊

公館100塊怪人
