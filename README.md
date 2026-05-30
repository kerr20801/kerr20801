# Kerr

**Security & DevOps · 台灣**

滲透測試 / 基礎架構設計 / AI 工具開發 / Chrome 套件

---

## 🔧 能解決的問題

- **資安稽核與滲透測試** — Web 應用程式漏洞（IDOR、CORS、注入攻擊）、內網架構審查
- **基礎架構設計** — K8s / K3S / Nginx HA / ELK Stack / ESXi 虛擬化
- **AI 工具開發** — 自動化 pipeline、LLM 整合、瀏覽器端安全工具
- **DevSecOps** — CI/CD 安全閘道、DLP、HIDS 部署

---

## 🔴 實戰案例

**Web Application Security Assessment — LicenseHub Staging**
> 4 Critical · 3 High · 半天 · 1 人

核心發現：跨租戶 IDOR（缺少 `company_id` 驗證）、CORS 配置錯誤、User-Agent 身份驗證繞過。
完整筆記：[IDOR 模式分析](https://github.com/kerr20801/kerr-notes/blob/main/security/2026-05-28-web-app-assessment-idor-patterns.md)

---

## 🛠 公開作品

### Chrome 套件（均已上架 Chrome Web Store）

| 作品 | 說明 |
|------|------|
| [SentinelDLP](https://github.com/kerr20801/SentinelDLP) | 貼上攔截 DLP — 18 種敏感資料偵測，語意打碼，零遙測 |
| [EnvGuard](https://github.com/kerr20801/EnvGuard) | 環境色條 — PROD / STAGING / DEV 即時提示，防部署到錯誤環境 |
| [PIW](https://github.com/kerr20801/PIW-repo) | Prompt Injection Warning — AI 聊天網站貼上注入偵測 |
| [HeaderShield](https://github.com/kerr20801/HeaderShield) | HTTP 安全 Header 即時評分（A–F），含修復設定，支援需登入頁面 |

### 資安工具

| 作品 | 說明 |
|------|------|
| [PacketScope](https://github.com/kerr20801/PacketScope) | tcpdump 封包威脅分析 — Beaconing / PortScan / Exfil 偵測，本機處理 |
| [nas-ai](https://github.com/kerr20801/nas-ai) | NAS 上傳安全閘道 — MIME 驗證 + Entropy 分析 + Isolation Forest，TG 告警 |
| [infra-sentinel](https://github.com/kerr20801/infra-sentinel) | 基礎架構 CVE 週期掃描 — nginx / ES / K8s，NVD API，去重告警 |

### 基礎架構

| 作品 | 說明 |
|------|------|
| [vcenter-power-guard](https://github.com/kerr20801/vcenter-power-guard) | UPS NUT 監控 → 5 狀態機 → vCenter 有序關機，CatBoost 動態預測剩餘時間 |
| [ha-manager](https://github.com/kerr20801/ha-manager) | HAProxy + Keepalived 管理平台 — Web UI 設定 HA 叢集，SSH 部署 |

### 瀏覽器工具（純前端，零後端）

| 作品 | 說明 |
|------|------|
| [log-anonymizer](https://github.com/kerr20801/log-anonymizer) | Log 貼上自動遮蔽 — 10 種格式，IP / Token / 帳密，支援還原 |
| [auto-sanitize](https://github.com/kerr20801/auto-sanitize) | Config 消毒 + LLM 語意驗證（Claude / GPT / Gemini） |

### 技術筆記

| 作品 | 說明 |
|------|------|
| [kerr-notes](https://github.com/kerr20801/kerr-notes) | 實戰筆記：K8s / 資安 / AI 應用 / 基礎架構，含多個 AI 模型觀點對比 |

---

## ⚙️ 技術棧

```
Languages    Python · JavaScript · Bash
Infra        K8s · K3S · Nginx · ESXi · VMware · Keepalived · MetalLB
Security     Burp Suite · OWASP Top 10 · DLP · HIDS · Network Analysis
Monitoring   ELK Stack · Grafana · Zabbix · Graylog
AI/ML        LightGBM · LSTM · CatBoost · LLM integration
Browser      Chrome MV3 · Shadow DOM · Content Scripts · WebAssembly
```

---

## 📬 聯繫

接受顧問合作：基礎架構審計、資安評估、DevOps 自動化

**Email** kidd.jk@gmail.com
