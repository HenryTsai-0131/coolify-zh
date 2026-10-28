🌏 **繁體中文** ｜ [English 原文](https://github.com/coollabsio/coolify)

> **非官方翻譯**：本 repo 是 [coollabsio/coolify](https://github.com/coollabsio/coolify) README 的中文翻譯，與原作者無關，亦非官方出品。
> 原專案授權：Apache-2.0（見 [LICENSE](LICENSE)）。翻譯依據原專案 commit `f778942`（2026-10-28），內容可能落後原文，請以原專案為準。

---

<div align="center">

<img src="https://raw.githubusercontent.com/coollabsio/coolify/main/public/coolify-logo.svg" alt="Coolify logo" width="120" />

# Coolify

**一個開源平台，讓你在自己的伺服器上部署應用程式、資料庫與服務。**

永遠開源且免費，這是我們的[理念](https://coolify.io/philosophy)。

![Latest Release Version](https://img.shields.io/badge/dynamic/json?labelColor=grey&color=6366f1&label=Latest%20released%20version&url=https%3A%2F%2Fcdn.coollabs.io%2Fcoolify%2Fversions.json&query=coolify.v4.version&style=for-the-badge
)

[網站](https://coolify.io) · [文件](https://coolify.io/docs) · [雲端版](https://app.coolify.io) · [Discord](https://coollabs.io/discord) · [社群](https://github.com/coollabsio/coolify/discussions)

</div>

## Coolify 是什麼？

Coolify 是 Heroku、Netlify 與 Vercel 的開源、可自行託管的替代方案。它能協助你在自己的硬體上管理伺服器、應用程式與資料庫，你只需要一個 SSH 連線。

你可以使用 VPS、裸機伺服器（bare-metal server）、Raspberry Pi，或任何接受 SSH 連線的伺服器。Coolify 在讓你掌控自己基礎設施的同時，也提供雲端平台的便利性。

你的設定都保存在自己的伺服器上。即使你不再使用 Coolify，正在執行的資源仍會繼續運作，也依然可以管理。

## Coolify 能做什麼？

- **部署任何應用程式：** 從 GitHub、GitLab、Bitbucket 或 Gitea 取得原始碼，並使用 Nixpacks、Railpack、Dockerfile、Docker Compose 或預先建置好的 Docker 映像檔進行建置。
- **執行資料庫與服務：** 部署受管理的資料庫，以及超過 360 個一鍵部署的服務，並提供持久性儲存空間與自動產生的憑證。
- **自動化部署：** 每次 Git push 時自動部署、建立 pull request 預覽、呼叫部署 webhook，並可回滾至保留的應用程式映像檔。
- **管理網路：** 設定自訂網域、自動 HTTPS 憑證、反向代理（reverse proxy）、健康檢查與容器網路。
- **營運你的基礎設施：** 管理多台伺服器、檢視部署與執行階段記錄、開啟容器終端機，並監控資源狀態。
- **保護你的工作負載：** 設定資料庫與儲存空間備份、排程任務、環境變數、機密資料與通知。
- **整合到你的工作流程：** 透過儀表板、API、CLI、MCP 與以團隊為基礎的存取控制來管理資源。

## 快速開始

只要一行指令，就能在受支援的伺服器上安裝 Coolify：

```bash
curl -fsSL https://cdn.coollabs.io/coolify/install.sh | bash
```

請閱讀[安裝指南](https://coolify.io/docs/installation)了解系統需求與詳細說明。你也可以在執行之前先檢視[安裝腳本](https://github.com/coollabsio/coolify/blob/main/scripts/install.sh)。

## 自行託管或雲端版

| 自行託管 | Coolify Cloud |
| --- | --- |
| 在你自己的伺服器上安裝 Coolify。 | 使用由我們維護的 Coolify 實例。 |
| 完整掌控並自行維護整個平台。 | 享有高可用性，並減少維護工作。 |
| 免費且開源。 | 付費服務，提供電子郵件通知與額外支援。 |

建議的自行託管架構是使用一台伺服器執行 Coolify，並使用一台或多台伺服器來執行已部署的資源。如果你不想維護 Coolify 伺服器，可以使用 [Coolify Cloud](https://app.coolify.io)。最新價格請參閱 [coolify.io](https://coolify.io)。

## 社群與支援

- 閱讀[文件](https://coolify.io/docs)。
- 加入 [Discord](https://coollabs.io/discord) 上的社群。
- 在 [GitHub Discussions](https://github.com/coollabsio/coolify/discussions) 提出問題。
- 提交變更之前，請先閱讀[貢獻指南](https://github.com/coollabsio/coolify/blob/main/CONTRIBUTING.md)。
- 檢視[行為準則](https://github.com/coollabsio/coolify/blob/main/CODE_OF_CONDUCT.md)。
- 透過[支援頁面](https://coolify.io/docs/contact)聯絡團隊。

## 捐款
為了保持完全免費與開源、不將任何功能放在付費牆後面，並讓專案持續進步，我們需要你的協助。如果你喜歡 Coolify，請考慮捐款，協助我們資助專案未來的開發。

[coolify.io/sponsorships](https://coolify.io/sponsorships)

非常感謝你！

### 特大贊助商

* [Context.dev](https://www.context.dev/) - 為 AI 代理程式打造的網頁爬取 API
* [Ginernet](https://ginernet.com/) - 在西班牙提供高效能伺服器代管
* [SerpAPI](https://serpapi.com) - Google Search API — 透過我們快速、簡單且完整的 API 爬取 Google 與其他搜尋引擎。
* [MVPS](https://www.mvps.net) - 以最高品質提供平價 VPS 伺服器
* [ScreenshotOne](https://screenshotone.com) - 為開發者打造的截圖 API
* [PrivateAlps](https://privatealps.net) - 雲端服務供應商，為重視隱私與掌控權的人提供 VPS 與伺服器基礎設施
* [Seibert Group](https://seibert.link/coolifysoftware) - 透過 Claude Code 等 AI 代理程式，提升全公司的生產力
* [Contabo](https://contabo.com/en/coolify-vps/) - 價格無可匹敵的雲端 VPS 與專用伺服器

### 大型贊助商

* [Vanaways](https://www.vanaways.co.uk) - 在英國各地銷售與租賃全新廂型車
* [Cloudways](https://www.cloudways.com/en/?id=2125302) - DigitalOcean 旗下的受管理雲端主機平台
* [ByteBase](https://www.bytebase.com) - 大規模資料庫 CI/CD 與安全性
* [Ramnode](https://ramnode.com/) - 高效能雲端 VPS 主機
* [23M](https://23m.com) - 高可用性主機解決方案專家！
* [Macarne](https://macarne.com) - 最佳 IP Transit 與 Carrier Ethernet 解決方案，簡化網路連線
* [Hetzner](http://htznr.li/CoolifyXHetzner) - 伺服器、雲端、主機與資料中心解決方案
* [Logto](https://logto.io) - 為開發者打造更好的身分識別基礎設施
* [Supadata](https://supadata.ai/) - 爬取 YouTube、網頁與檔案，為你的下一個專案取得可供 AI 使用的乾淨資料。
* [Tolgee](https://tolgee.io) - 開源的在地化平台
* [Best Consultant](https://bc.direct) - 值得信賴的技術顧問夥伴
* [ArcJet](https://arcjet.com) - 先進的網頁安全與效能解決方案
* [SupaGuide](https://supa.guide) - 你的 Supabase 完整指南
* [CodeRabbit](https://coderabbit.ai) - 將程式碼審查時間與錯誤減少一半
* [Convex](https://convex.link/coolify.io) - Convex 是為網頁應用程式開發者打造的開源響應式資料庫。
* [GoldenVM](https://billing.goldenvm.com) - 優質的虛擬機器主機解決方案
* [Comit International](https://comit.international) - 榮獲《紐約時報》獎項的承包商！
* [Compai](https://www.trycomp.ai) - 開源的合規自動化平台，提供你快速達成合規所需的一切。是 Drata 與 Vanta 的開源替代方案。
* [Tigris](https://www.tigrisdata.com) - 現代化的 S3 替代方案
* [Blacksmith](https://blacksmith.sh) - 基礎設施自動化平台
* [JobsCollider](https://jobscollider.com/remote-jobs) - 為開發者提供 30,000 多個遠端職缺
* [Darweb](https://darweb.nl/?ref=coolify.io&utm_source=coolify.io) - 設計、開發、交付。專精於電子商務的 3D CPQ 解決方案。
* [Hostinger](https://www.hostinger.com/vps/coolify-hosting) - 網站主機與 VPS 解決方案
* [Mobb](https://vibe.mobb.ai/) - 保護由 AI 產生的程式碼，釋放開發生產力
* [Ubicloud](https://www.ubicloud.com) - 開源雲端基礎設施平台
* [PFGLabs](https://pfglabs.com) - 用 Golang 打造真實專案
* [JuxtDigital](https://juxtdigital.com) - 數位公關與 AI 權威建立機構
* [SaasyKit](https://saasykit.com) - 為開發者打造的完整 SaaS 入門套件
* [American Cloud](https://americancloud.com) - 位於美國的雲端基礎設施服務
* [Greptile](https://www.greptile.com) - AI 程式碼審查工具
* [VPSDime](https://vpsdime.com/) - 平價 VPS 主機 - 4GB 每月僅 5 美元
* [dataforest Cloud](https://cloud.dataforest.net/en) - 在數秒內獨立以 seed 形式部署雲端伺服器。企業級硬體、頂級網路，100% 德國製造。
* [ISHosting](https://ishosting.com/) - 主機與 VPS 解決方案
* [NodePlus.ai](https://nodeplus.ai/) - 能讀懂貴公司所執行的每個系統的 AI

### 小型贊助者

<a href="https://serverside.com/?utm_source=coolify.io"><img width="60px" alt="Serverside" src="https://cdn.coollabs.io/sponsors/serverside.svg"/></a>
<a href="https://darkvps.pro"><img width="60px" alt="DarkVPS" src="https://cdn.coollabs.io/sponsors/darkvps.png"/></a>
<a href="https://www.opensourcealternatives.to"><img width="60px" alt="Open Source Alternatives" src="https://cdn.coollabs.io/sponsors/opensourcealternatives.png"/></a>
<a href="https://onserva.com/"><img width="60px" alt="Onserva" src="https://onserva.com/icon.svg"/></a>
<a href="https://www.movavi.com/mac.html?utm_source=coolify.io"><img width="60px" alt="Movavi" src="https://cdn.coollabs.io/sponsors/movavi.png"/></a>
<a href="https://usefoil.com/"><img width="60px" alt="ABXY" src="https://usefoil.com/favicon.svg"/></a>
<a href="https://www.launchfa.st/?utm_source=coolify.io"><img width="60px" alt="LaunchFast Boilerplates" src="https://github.com/LaunchFast-Boilerplates.png"/></a>
<a href="https://www.netrouting.com/?utm_source=coolify.io"><img width="60px" alt="Netrouting" src="https://github.com/netroutingcom.png"/></a>
<a href="https://github.com/mindedtech"><img width="60px" alt="MindEd Tech" src="https://github.com/mindedtech.png"/></a>
<a href="https://youstable.com/?utm_source=coolify.io"><img width="60px" alt="YouStable" src="https://github.com/youstable.png"/></a>
<a href="https://transcript.lol/?utm_source=coolify.io"><img width="60px" alt="Transcript LOL" src="https://transcript.lol/logo.png"/></a>
<a href="https://www.autom.dev/?utm_source=coolify.io"><img width="60px" alt="Autom" src="https://cdn.coollabs.io/sponsors/autom.png"/></a>
<a href="https://www.huntapi.com/?utm_source=coolify.io"><img width="60px" alt="HuntAPI" src="https://cdn.coollabs.io/sponsors/huntapi.png"/></a>
<a href="https://ultraservers.com/?utm_source=coolify.io"><img width="60px" alt="ULTRASERVERS" src="https://github.com/ULTRASERVERS.png"/></a>
<a href="https://vibetone.com/?utm_source=coolify.io"><img width="60px" alt="VibeTone" src="https://github.com/vibetonefm.png"/></a>
<a href="https://www.piloterr.com/?utm_source=coolify.io"><img width="60px" alt="Piloterr" src="https://cdn.coollabs.io/sponsors/piloterr.svg"/></a>
<a href="https://yoxel.com/?utm_source=coolify.io"><img width="60px" alt="Alexey Panteleev" src="https://github.com/aspantel.png"/></a>
<a href="https://summyt.app?utm_source=coolify.io"><img width="60px" alt="SummYT - YouTube Summarizer" src="https://summyt.app/logo.svg"/></a>
<a href="https://open-elements.com/?utm_source=coolify.io"><img width="60px" alt="OpenElements" src="https://github.com/OpenElements.png"/></a>
<a href="https://xaman.app/?utm_source=coolify.io"><img width="60px" alt="Xaman" src="https://github.com/XamanApp.png"/></a>
<a href="https://monadical.com/?utm_source=coolify.io"><img width="60px" alt="Monadical" src="https://github.com/Monadical-SAS.png"/></a>
<a href="https://maas.engineering/?utm_source=coolify.io"><img width="60px" alt="Magic as a Service" src="https://github.com/magicasaservice.png"/></a>
<a href="https://fivemanage.com?utm_source=coolify.io"><img width="60px" alt="FiveManage" src="https://cdn.coollabs.io/sponsors/fivemanage.jpg"/></a>
<a href="https://cryptojobslist.com/?utm_source=coolify.io"><img width="60px" alt="Crypto Jobs List" src="https://github.com/cryptojobslist.png"/></a>
<a href="https://serpapi.com/?utm_source=coolify.io"><img width="60px" alt="SerpAPI" src="https://github.com/serpapi.png"/></a>
<a href="https://typebot.io/?utm_source=coolify.io"><img width="60px" alt="typebot" src="https://cdn.bsky.app/img/avatar/plain/did:plc:gwxcta3pccyim4z5vuultdqx/bafkreig23hci7e2qpdxicsshnuzujbcbcgmydxhbybkewszdezhdodv42m@jpeg"/></a>
<a href="https://360creators.com/?utm_source=coolify.io"><img width="60px" alt="360Creators" src="https://opencollective-production.s3.us-west-1.amazonaws.com/account-avatar/503e0953-bff7-4296-b4cc-5e36d40eecc0/icon-360creators.png"/></a>
<a href="https://capgo.app/?utm_source=coolify.io"><img width="60px" alt="Cap-go" src="https://github.com/cap-go.png"/></a>
<a href="https://cirun.io/?utm_source=coolify.io"><img width="60px" alt="Cirun" src="https://cdn.coollabs.io/sponsors/cirun-logo.png"/></a>
<a href="https://github.com/puls-digital-group"><img width="60px" alt="Puls Digital Group" src="https://github.com/puls-digital-group.png"/></a>
<a href="https://github.com/jonathanprl"><img width="60px" alt="Jonathan Pereira" src="https://github.com/jonathanprl.png"/></a>
<a href="https://outboundgateway.com/"><img width="60px" alt="OutboundGateway" src="https://github.com/OutboundGateway.png"/></a>
<a href="https://github.com/t4dt"><img width="60px" alt="T4DT GmbH" src="https://github.com/t4dt.png"/></a>
<a href="https://internetgarden.co/?utm_source=coolify.io"><img width="60px" alt="Internet Garden" src="https://cdn.coollabs.io/sponsors/internetgarden.ico"/></a>
<a href="https://evercam.io/?utm_source=coolify.io"><img width="60px" alt="Evercam" src="https://github.com/evercam.png"/></a>
<a href="https://web3.career/?utm_source=coolify.io"><img width="60px" alt="Web3 Jobs" src="https://cdn.coollabs.io/sponsors/web3jobs.png"/></a>
<a href="https://linkdr.com?utm_source=coolify.io"><img width="60px" alt="LinkDr" src="https://cdn.coollabs.io/sponsors/linkdr.svg"/></a>
<a href="https://arvensis.systems/?utm_source=coolify.io"><img width="60px" alt="Arvensis Systems" src="https://cdn.coollabs.io/sponsors/arvensis.png"/></a>
<a href="https://www.runpod.io/?utm_source=coolify.io"><img width="60px" alt="RunPod" src="https://cdn.coollabs.io/sponsors/runpod.svg"/></a>
<a href="http://gravitywiz.com/?utm_source=coolify.io"><img width="60px" alt="Gravity Wiz" src="https://github.com/gravitywiz.png"/></a>
<a href="https://www.uxwizz.com/?utm_source=coolify.io"><img width="60px" alt="UXWizz" src="https://github.com/UXWizz.png"/></a>
<a href="https://codext.link/coolify-io?utm_source=coolify.io"><img width="60px" alt="Codext" src="https://cdn.coollabs.io/sponsors/codext.jpg"/></a>
<a href="https://interviewpal.com"><img width="60px" alt="InterviewPal" src="https://cdn.coollabs.io/sponsors/interviewpal.svg"/></a>
<a href="https://decidable.no?utm_source=coolify.io"><img width="60px" alt="Decidable" src="https://github.com/Decidable-AS.png"/></a>
<a href="https://hosthavoc.com"><img width="60px" alt="Host Havoc" src="https://cdn.coollabs.io/sponsors/hosthavoc.png"/></a>

...以及更多贊助者，請見 [GitHub Sponsors](https://github.com/sponsors/coollabsio)

## Star 歷史

[![Star History Chart](https://api.star-history.com/svg?repos=coollabsio/coolify&type=Date)](https://star-history.com/#coollabsio/coolify&Date)
