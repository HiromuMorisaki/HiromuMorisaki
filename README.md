# Hiromu Morisaki（森崎 大夢）

> **iOS × AI エンジニア** — AI で高速に ship しつつ、設計・品質は自分で担保する。

個人で App Store アプリを開発・運用しながら、**① iOS 開発／② AI・業務自動化／③ フルスタック（Web・バックエンド）** の3領域を横断します。Java / JavaScript の実務 3〜5年をベースに、Swift・LLM API・自動化基盤まで一気通貫で扱います。

**実績ハイライト**：App Store リリース **7 本** ／ 個人開発 **10+ 本**（開発中含む） ／ クライアント向け業務自動化 **3 件**

---

## 📱 App Store リリース済み

すべて **ローカル完結・プライバシー重視**（通信ゼロ・SwiftData によるオンデバイス保存）を基本指針としています。

| アプリ | カテゴリ | 主要技術 | 特徴・実績 |
|--------|---------|---------|-----------|
| [**ひと呼吸** — スマホ依存対策・アプリ制限](https://apps.apple.com/jp/app/%E3%81%B2%E3%81%A8%E5%91%BC%E5%90%B8-%E3%82%B9%E3%83%9E%E3%83%9B%E4%BE%9D%E5%AD%98%E5%AF%BE%E7%AD%96-%E3%82%A2%E3%83%97%E3%83%AA%E5%88%B6%E9%99%90/id6810300278) | ヘルスケア／フィットネス · ユーティリティ | SwiftUI · App Intents · SwiftData · Swift Charts · WidgetKit · StoreKit 2 | スクリーンタイム許可不要で起動時に深呼吸を挟む。対象アプリ無制限 |
| [**ITかるた** — IT用語クイズで楽しく暗記](https://apps.apple.com/jp/app/it%E3%81%8B%E3%82%8B%E3%81%9F-it%E7%94%A8%E8%AA%9E%E3%82%AF%E3%82%A4%E3%82%BA%E3%81%A7%E6%A5%BD%E3%81%97%E3%81%8F%E6%9A%97%E8%A8%98/id6808845036) | 教育 · ゲーム · トリビア | SwiftUI · StoreKit 2 · PDFKit · Swift Charts · XcodeGen | ★ 5.0 ／ 全9パック425問。HTTPステータスコード・Linux等の速答かるた。紙の印刷用PDF書き出し対応 |
| [**ふるさと納税 台帳** — 上限シミュ＆ワンストップ管理](https://apps.apple.com/jp/app/%E3%81%B5%E3%82%8B%E3%81%95%E3%81%A8%E7%B4%8D%E7%A8%8E-%E5%8F%B0%E5%B8%B3-%E4%B8%8A%E9%99%90%E3%82%B7%E3%83%9F%E3%83%A5-%E3%83%AF%E3%83%B3%E3%82%B9%E3%83%88%E3%83%83%E3%83%97%E7%AE%A1%E7%90%86/id6811728732) | ファイナンス · ユーティリティ | SwiftUI · SwiftData · TDD | 複数ポータル横断の寄付台帳・総務省基準の目安シミュレーション・ワンストップ申請トラッカー |
| [**コテサク** — 家計簿・節約・サブスク管理](https://apps.apple.com/jp/app/%E5%AE%B6%E8%A8%88%E7%B0%BF-%E7%AF%80%E7%B4%84-%E3%82%B5%E3%83%96%E3%82%B9%E3%82%AF%E7%AE%A1%E7%90%86-%E3%82%B3%E3%83%86%E3%82%B5%E3%82%AF/id6772914926) | ファイナンス · 仕事効率化 | SwiftUI · SwiftData · Vision(OCR) · EventKit · StoreKit 2 | ★ 5.0 ／ 手取り月収から固定費を引いて「今月あと自由に使えるお金」を自動計算・可視化 |
| [**家づくり管理** — ハウスメーカー比較](https://apps.apple.com/jp/app/%E5%AE%B6%E3%81%A5%E3%81%8F%E3%82%8A%E7%AE%A1%E7%90%86-%E3%83%8F%E3%82%A6%E3%82%B9%E3%83%A1%E3%83%BC%E3%82%AB%E3%83%BC%E6%AF%94%E8%BC%83/id6775920878) | ライフスタイル · ユーティリティ | SwiftUI · SwiftData · WidgetKit · PDFKit · Speech/AVFoundation | ハウスメーカーの比較検討・打合せ記録・図面ピンチズーム・端末内AIによる音声文字起こし |
| [**そなえメモ** — 非常食の備蓄とローリングストック管理](https://apps.apple.com/jp/app/%E3%81%9D%E3%81%AA%E3%81%88%E3%83%A1%E3%83%A2-%E9%9D%9E%E5%B8%B8%E9%A3%9F%E3%81%AE%E5%82%99%E8%93%84%E3%81%A8%E3%83%AD%E3%83%BC%E3%83%AA%E3%83%B3%E3%82%B0%E3%82%B9%E3%83%88%E3%83%83%E3%82%AF%E7%AE%A1%E7%90%86%E3%82%A2%E3%83%97%E3%83%AA/id6783843695) | ユーティリティ · ライフスタイル | SwiftUI · SwiftData · UserNotifications | 非常食・防災備蓄の賞味期限管理とローリングストック支援 |
| [**つむぐノート** — エンディングノート・自分史・やりたいこと](https://apps.apple.com/jp/app/%E3%81%A4%E3%82%80%E3%81%90%E3%83%8E%E3%83%BC%E3%83%88-%E3%82%A8%E3%83%B3%E3%83%87%E3%82%A3%E3%83%B3%E3%82%B0%E3%83%8E%E3%83%BC%E3%83%88-%E8%87%AA%E5%88%86%E5%8F%B2-%E3%82%84%E3%82%8A%E3%81%9F%E3%81%84%E3%81%93%E3%81%A8/id6784717709) | ライフスタイル · ユーティリティ | SwiftUI · SwiftData · LocalAuthentication · PDFKit · StoreKit 2 | 端末内完結・Face IDロックのエンディングノート＆自分史 |

---

## 🛠 技術スタック

**iOS**  
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0066FF?style=flat&logo=swift&logoColor=white)
![SwiftData](https://img.shields.io/badge/SwiftData-0066FF?style=flat&logo=swift&logoColor=white)
![WidgetKit](https://img.shields.io/badge/WidgetKit-0066FF?style=flat&logo=swift&logoColor=white)
![StoreKit 2](https://img.shields.io/badge/StoreKit_2-0066FF?style=flat&logo=apple&logoColor=white)
![App Intents](https://img.shields.io/badge/App_Intents-0066FF?style=flat&logo=apple&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat&logo=xcode&logoColor=white)
![XcodeGen](https://img.shields.io/badge/XcodeGen-grey?style=flat)

**AI / 自動化**  
![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat&logo=anthropic&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Dify](https://img.shields.io/badge/Dify-1C64F2?style=flat)
![Apps Script](https://img.shields.io/badge/Google_Apps_Script-4285F4?style=flat&logo=googleappsscript&logoColor=white)

**Web / Script**  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue_3-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**その他**  
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![VBA](https://img.shields.io/badge/VBA-217346?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## ⚙️ 業務自動化・AIワークフローの実績

| 技術 | 内容 |
|------|------|
| **n8n** | Zenn 等から AI/IT の最新記事を定期取得し、自分の関心属性に合わせて AI で要約 → Discord へ自動配信するキュレーションパイプラインを構築・運用 |
| **Google Apps Script** | 外部クライアント向けの業務自動化を複数構築：<br>① 自動車整備会社で、受信メールの事故写真を規定レイアウトで自動プリント<br>② スプレッドシートのエリア名・商品名・位置情報から PowerPoint へオブジェクトと名称を等間隔配置するショールーム用マッピングツール<br>③ 社内の勤怠・研修管理ツールの改修<br>④ Slack + GAS 筋トレ継続支援システム（出筋/退筋スタンプ記録・ダッシュボード・週次まとめ） |
| **Python** | X・Threads 向けマルチプラットフォーム自動投稿スクリプト・画像パイプラインの構築・運用 |
| **Dify** | 書籍ハンズオンで RAG チャットボットを5本構築し、RAG 構成の設計を実践 |

---

## 🚧 開発中・プロトタイプ

| プロジェクト | 概要 | 主要技術 |
|------------|------|---------|
| **コミコム** | Amazon・楽天・Yahoo! を横断し、送料・ポイント込みの「実質最安」を比較する iOS アプリ | SwiftUI · SwiftData ＋ **Supabase / サーバーサイド（フルスタック構成）** |
| **現金主義** | 現金貯金をゲーミフィケーションで楽しくする育成アプリ | SwiftUI · SwiftData · StoreKit 2 · CloudKit · Swift Charts · HealthKit |
| **スパイを見抜け** | 4〜6人で1台のiPhoneを囲んで遊ぶ対面パーティゲーム（旧会話ゲームのスキーマ互換） | SwiftUI · SwiftData |
| **firekeeper-swarm** | ワンサム・サバイバルゲーム試作（iOS向け片手操作アクション） | Swift · SpriteKit |
| [**portfolio-hub**](https://github.com/HiromuMorisaki/portfolio-hub) | 本ポートフォリオサイト（アプリ別ケーススタディ・アーキ図） | Vue 3 · TypeScript |

---

## 📝 技術記事（Zenn）

Zenn にて **「意思決定ログ」** シリーズを連載中。設計上の選択・つまずき・解決の過程を公開しています。

- [個人開発アプリ6本で標準化した「ローカル完結アーキテクチャ」— SwiftUI × SwiftData 意思決定ログ](https://zenn.dev/hinaridake/articles/ios-local-first-architecture)
- [AI に任せた所、自分で握った所 — 個人開発6本で見えた「線引き」 | 意思決定ログ](https://zenn.dev/hinaridake/articles/ai-development-boundary)
- [IT用語を「かるた」で覚えるiOSアプリを出した — 課金の軸・出題の公平性・提出でハマった所 | 意思決定ログ](https://zenn.dev/hinaridake/articles/it-karuta-release-decisions)
- [個人開発のiOSアプリ4本、App Storeの検索だけで90日。数字を全部出します](https://zenn.dev/hinaridake/articles/indie-ios-apps-90days-numbers)
- [家づくりアプリのコラム45本をAIに点検させたら、点検役のAIも間違えていた](https://zenn.dev/hinaridake/articles/ai-content-fact-check-housing-app)
- [AIに50人のユーザーを演じさせて7回調査したアプリが、90日で11ダウンロードだった](https://zenn.dev/hinaridake/articles/ai-persona-survey-vs-reality)

👉 **[Zenn アカウント（@hinaridake）](https://zenn.dev/hinaridake)**

---

## 📬 連絡先

[![X](https://img.shields.io/badge/X-@h__morisaki-000000?style=flat&logo=x)](https://x.com/h_morisaki)
&nbsp;
[![Threads](https://img.shields.io/badge/Threads-@h__morisaki-000000?style=flat&logo=threads)](https://threads.net/@h_morisaki)
&nbsp;
[![Note](https://img.shields.io/badge/Note-h__morisaki-41C9B4?style=flat)](https://note.com/h_morisaki)
&nbsp;
[![Zenn](https://img.shields.io/badge/Zenn-hinaridake-3EA8FF?style=flat&logo=zenn&logoColor=white)](https://zenn.dev/hinaridake)
