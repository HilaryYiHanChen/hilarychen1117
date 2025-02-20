# SAS與SPSS(PASW)工具介紹與學習

### 🔭 學習歷程
- 需要基本統計基礎，運用在SAS、SPSS(PASW)上會快速許多
- SAS適合程度較高使用者、SPSS適合初學者
- 兩個最大的差別是`SAS需要寫語法`、`SPSS則不需` (_後面會有表格做比較_) <br>
  👉🏻SAS在編寫語法過程中，若沒有太大邏輯錯誤還是可以RUN出data，只是你不知道這個data到底是正確還是錯誤？這時候回去檢查寫得**語法**就很重要了 <br>
  👉🏻SPSS操作更為方便，基本上只要點選要對應的統計分析就可RUN出data了
---

### SAS
 功能強大，常用於醫學統計、金融業
 <table border="1">
  <tr>
    <th>進入門檻</th>
    <td>基本統計學概念</td>
  </tr>
  <tr>
    <th>特色</th>
    <td>不需程式基礎，若是進階使用者也可和程式結合</td>
  </tr>
  <tr>
    <th>運算能力</th>
    <td>運算能力效率高，可處理較大、廣、複雜等數據等統計分析</td>
  </tr>
   <tr>
    <th>資料管理</th>
    <td>處理強大、含有SQL（結構化查詢語言）</td>
  </tr>
   <tr>
    <th>總評</th>
    <td>雖說是高階用戶在使用，但進入門檻較低，只有把握邏輯概念，在撰寫語法上就會快速許多</td>
  </tr>
 </table>

---

### SPSS(PASW)
 容易上手，處理資料庫有限
<table border="1">
  <tr>
    <th>進入門檻</th>
    <td>基本統計學概念</td>
  </tr>
  <tr>
    <th>特色</th>
    <td>不需寫程式，操作方便、編程方便、新手友善</td>
  </tr>
  <tr>
    <th>運算能力</th>
    <td>運算能力較弱，可處理數據量較少，類似Excel專屬統計進階版</td>
  </tr>
  <tr>
    <th>資料管理</th>
    <td>受限於介面排版，熟悉後在處理上才會比較快</td>
  </tr>
  <tr>
    <th>總評</th>
    <td>其實與SAS一樣只要具備基本的統計知識就能使用，若是資料簡單、探勘數據深度及廣度不大的話，那此工具就很適合可以簡單處理者</td>
  </tr>
  </table>
  
---

```mermaid
graph LR
  A(定義分析目標) --> B(資料搜集)
  B --> C(資料品質分析)
  C --> D(模型建置)
  D --> E(模型部署)
  E --> F(模型監控與調整)
  F --> A
