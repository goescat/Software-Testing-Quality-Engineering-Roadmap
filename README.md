# Software-Testing-Quality-Engineering-Roadmap
## 軟體測試與品質工程學習地圖

## 前言
> 雖然叫做「軟體測試與品質工程學習地圖」，但這其實只是個好聽的名字。
> 
> 更準確的說，這是一份我的個人心得與筆記。我想盡量用簡單、容易理解的方式來整理，希望即使是完全沒有測試基礎，不知道測試是什麼的人，也能看得懂～
> 
> 即使網路上已經有非常多資料，甚至直接問 AI 可能還能得到更完整的答案，但我還是想試著用自己的話，把這些東西重新整理一次，用自己的理解去詮釋它們。
> 
> 當然，每個人的測試之路都不一樣。這份地圖並不是「全部學完才能當 QA」的清單，也不可能涵蓋所有 QA、QE、SDET（或是其他測試相關職稱）會接觸到的技能，一定會有遺漏，也一定會有一些我目前還不知道、甚至很多大神才會的東西。
> 
> 即便如此，暫時列出來也發現內容並不少，之後在寫作的過程中都會持續調整，偶爾也可能有一些比較雜亂的內容。
> 
> 一天寫一點，總有寫完的一天吧 XD

## 測試基礎
### 測試思維
* [什麼是軟體測試？](/docs/fundamentals/what-is-testing.md)
  * [測試的目的](/docs/fundamentals/what-is-testing.md#測試的目的)
  * [測試的限制](/docs/fundamentals/what-is-testing.md#測試的限制)
  * [測試優先級](/docs/fundamentals/what-is-testing.md#測試優先級)
  * [測試範圍](/docs/fundamentals/what-is-testing.md#測試範圍)
  * [測試左移](/docs/fundamentals/what-is-testing.md#測試左移)
  * [測試右移](/docs/fundamentals/what-is-testing.md#測試右移)

### 測試設計
* [測試案例設計](/docs/fundamentals/test_case_design.md)
    * [使用案例／情境測試 （Use Case / Scenario Testing）](/docs/fundamentals/test_case_design.md#使用案例情境測試use-case--scenario-testing) 
    * [等價類劃分 （Equivalence Partitioning）](/docs/fundamentals/test_case_design.md#等價類劃分equivalence-partition)
    * [邊界值分析 （Boundary Value Analysis）](/docs/fundamentals/test_case_design.md#邊界值分析boundary-value-analysis)
    * [決策表測試 （Decision Table Testing）](/docs/fundamentals/test_case_design.md#決策表測試decision-table-testing)
    * [狀態轉換測試 （State Transition Testing）](/docs/fundamentals/test_case_design.md#狀態轉換測試state-transition-testing)
    * 配對測試 （Pairwise Testing）
    * 錯誤猜測（Error Guessing）

### 測試類型
* 功能測試
* 回歸測試
* 冒煙測試 Smoke Test
* 健全性測試 Sanity Test
* 整合測試
* 驗收測試
* 探索式測試

<!--
### 常見詞彙補充
UAT
Staging-->

## 程式設計
* 程式設計基礎
<!--
* 變數與資料型別
* 條件與迴圈
* 函式
* 例外處理
* 模組
* 物件導向
* 資料結構
* 演算法
-->

## 工程實務
* Git
<!--
* Code Review
* Debugging
* Logging
* Clean Code
* Design Pattern
* 軟體架構
-->


## 自動化測試
### Unit / Integration
* pytest
* JUnit
* Jest

### API
* Postman
* curl
* requests
* httpx

### UI
* Selenium
* Playwright
* Cypress

### Mobile
* Appium
* Android
* iOS

## 測試工程
* 測試框架設計
* Fixture
* 測試資料管理
* 測試環境管理
* 測試隔離
* 平行測試
* Test Retry
* Test Reporting
* Logging
* 測試結果分析
* Flaky Test

## CI/CD 與測試基礎設施
* CI/CD
* Pipeline
* Artifact
* Test Report
* Quality Gate
* Parallel Execution
* Test Selection
* Test Environment

* GitHub Actions
* GitLab CI
* Jenkins

## 系統、網路觀念
* Linux
* Shell
* HTTP
* TCP/IP
* DNS
* SSH
* Proxy

* SQL
* MySQL / PostgreSQL
* Redis
* Cache
* Data Consistency

* REST API
* Microservices
* Message Queue
* Kafka
* Event-driven Architecture
* Distributed Systems
* Concurrency
* Consistency
* Fault Tolerance

## 雲端與基礎設施
### Cloud
* AWS / GCP / Azure

* Docker
* Kubernetes

## 品質工程
* Observability
* Monitoring
* Logging
* Metrics
* Tracing
* SLI / SLO / SLA
* Incident Management
* Feature Flag
* Canary Release
* A/B Testing
* Chaos Engineering
