# Software-Testing-Quality-Engineering-Roadmap
軟體測試與品質工程學習地圖

## 前言
> 網路上資料很多，問AI可能答得更好～可是我就是想要試著用自己的話寫一次。
> 內容很多，也可能會動態調整，也會有稍微雜亂的內容，一天寫一點，總有寫完的一天（？）

## 測試基礎
### 測試思維
* [什麼是軟體測試？](/docs/fundamentals/what-is-testing.md)
  * [測試的目的](/docs/fundamentals/what-is-testing.md#測試的目的)
  * [測試的限制](/docs/fundamentals/what-is-testing.md#測試的限制)
  * 風險
  * 測試範圍
  * 測試深度
  * 測試優先級
  * 測試左移
  * 測試右移（？）

### 測試設計
* 等價類別
* 邊界值分析
* 決策表
* 狀態轉換
* Pairwise Testing
* Error Guessing
* Risk-based Testing

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
