# Samurai Painting Quote Tool v4 → v5
**Smart Quotation Tool for Professional Painters / プロ塗装職人向けスマート見積もりツール**

[![v4 Live Demo](https://img.shields.io/badge/v4_Live_Demo-Click_Here-blue)](https://isao1301111-eng.github.io/samurai-painting-quote-v4/)
[![v5 + Hallucination Guard](https://img.shields.io/badge/v5_%F0%9F%9B%A1%EF%B8%8F_Hallucination_Guard-Try_Now-00e676)](https://isao1301111-eng.github.io/samurai-painting-quote-v4/samurai-painting-quote-v5.html)

---

## 🎯 Overview / 概要

**[English]**  
A professional quotation tool built on **27 years of hands-on experience** in the architectural painting industry. Unlike simple area × rate calculators, this tool accounts for **material type**, **substrate condition**, and **existing paint type and degradation level** to generate realistic, job-ready quotes.

Automatic warnings are shown for common on-site risks (e.g., switching from oil-based to water-based paint). Based on NSW 2025–26 market rates.

**[日本語]**  
建築塗装業界で**27年間**現場を経験してきた知見をもとに開発した、実務特化型の自動見積もりツールです。単純な面積×単価計算ではなく、**材質・下地状態・既存塗膜の種類と劣化度**を細かく考慮し、現場で実際に使える見積もりを瞬時に生成します。

油性→水性切替時のリスクなど、現場で起きやすい問題についての自動警告表示付き。NSW（ニューサウスウェールズ州）2025〜26年の相場に基づいた計算ロジックを使用。

---

## ✨ Key Features / 主な特徴

| Feature | 機能 |
|---|---|
| Material-aware calculation | 材質を考慮した計算（Plaster, Timber, Aluminium, Concrete, Steel, Fibre Cement など） |
| Paint condition detection | 既存塗膜の状態を判定・警告（油性→水性切替時の注意など） |
| Full bilingual support | 日本語 / English ワンクリック切り替え |
| Print-ready quote output | 印刷用・PDF保存対応の見積書出力 |
| Extras & Options | 足場・高圧洗浄・5年保証・カラーコンサルなど |
| Offline-ready | 単一HTMLファイル、インターネット不要で動作 |

---

## 🚀 Live Demo / デモ

| Version | URL |
|---|---|
| **v4** | [https://isao1301111-eng.github.io/samurai-painting-quote-v4/](https://isao1301111-eng.github.io/samurai-painting-quote-v4/) |
| **v5 🛡️** | [https://isao1301111-eng.github.io/samurai-painting-quote-v4/samurai-painting-quote-v5.html](https://isao1301111-eng.github.io/samurai-painting-quote-v4/samurai-painting-quote-v5.html) |

---

## 📸 Screenshots / スクリーンショット

**v5 Main UI — 🛡️ STRICT MODE toggle (top right)**
![v5 Main UI](%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202026-05-20%20215029.png)

**Hallucination Guard — Verification Protocol panel (error detection)**
![Verification Panel](%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202026-05-20%20215230.png)

**AI Verification Report — appended to quote in STRICT MODE**
![AI Verification Report](%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202026-05-20%20215354.png)

---

## 💼 Background / 開発背景

**[English]**  
Over **27 years** working in architectural painting — **15 years in the Kanto region (Tokyo / Kanagawa, Japan)** and **12 years in Sydney, Australia** — I encountered the same problem thousands of times: quotes that didn't account for material type or existing paint conditions led to unexpected costs and on-site issues.

This tool was built to solve that — packaging real field knowledge into a practical digital system.

I am currently transitioning my career toward **AI Consulting and Digital Automation** in the construction and DX space, and relocating to the **Kanto region (Tokyo / Kanagawa)** in October 2026. This is **Portfolio #1**, demonstrating how deep industry expertise can be combined with digital tools to create real value.

**[日本語]**  
関東（東京・神奈川）で**15年**、シドニーで**12年**、合計**27年間**にわたって建築塗装の現場に携わってきました。その中で何度も経験したのが「材質や既存塗膜の状態を見誤ったことで、後から追加費用や問題が発生する」というケースです。

このツールは、そうした現場のリアルな知見をデジタル化したものです。

現在、建築・DX分野での**AIコンサルタント・AI自動化フリーランス**へのキャリアチェンジを進めており、2026年10月に**関東（東京・神奈川周辺）**に帰国予定です。このツールは**ポートフォリオ第1弾**として、現場経験とデジタルツールを組み合わせた実践的な価値を体現しています。

---

## 📁 Files / ファイル構成

| File | Version | Description |
|---|---|---|
| `index.html` | v4 | Material-Aware AI Quote Generator |
| `samurai-painting-quote-v5.html` | v5 | + Hallucination Guard Protocol v1.0 |

---

## 🛠️ Tech Stack / 技術スタック

- **HTML5 + CSS3 + Vanilla JavaScript**（外部ライブラリなし / No external libraries）
- Single-file architecture（単一HTMLファイル構成）
- Fully responsive & print-optimized（レスポンシブ対応・印刷最適化済み）

---

## 🛡️ v5: Hallucination Guard Protocol / ハルシネーション防止プロトコル

**[English]**  
v5 introduces the **Hallucination Guard Protocol v1.0** — a built-in AI output verification system that validates the quote before generation.

Activate via the **🛡️ STRICT MODE** toggle (green accent) in the header. When enabled:

**9-Point Automatic Verification Engine:**
1. ✅ Active surface / item check — confirms at least one billable item exists
2. ✅ Surface area validation — all enabled surfaces must have area > 0
3. ✅ Item quantity validation — all enabled items must have qty > 0
4. ✅ Client info check — flags missing name or address
5. ✅ Job type check — warns if no job type is selected
6. ✅ Logical contradiction detection — e.g., New Build × peeling paint, New Build × oil→water switch
7. ✅ NSW market rate check ($/m²) — blended rate compared against 2025–26 market ranges per surface type
8. ✅ Line item count consistency — enumeration-verified total count
9. ✅ Total amount sanity check — flags suspiciously low totals

**Behavior:**
- ❌ **Errors** block quote generation — user must fix before proceeding
- ⚠️ **Warnings** are shown but do not block generation
- In STRICT MODE, the generated quote includes an **"AI Verification Report"** section appended at the bottom

**Portfolio significance:** Demonstrates "AI verifying AI output" — the tool validates its own calculations before presenting them, addressing hallucination risks in AI-generated financial documents.

---

**[日本語]**  
v5では **ハルシネーション防止プロトコル v1.0** を導入。見積書生成前にAIが自己出力を検証します。

ヘッダーの **🛡️ STRICT MODE** トグル（緑アクセント）で有効化。

**9項目の自動検証エンジン：**
1. ✅ 有効な表面・項目の存在確認
2. ✅ 有効表面の面積入力チェック
3. ✅ 有効項目の数量入力チェック
4. ✅ お客様情報入力確認
5. ✅ 作業内容（ジョブタイプ）選択確認
6. ✅ 論理矛盾検出（新築×剥離ありなど）
7. ✅ NSW市場レンジ（$/m²）照合
8. ✅ 件数＝列挙一致確認
9. ✅ 合計額サニティチェック

**エラー時は見積もり生成をブロック。** STRICTモードON時、見積書末尾に「AI Verification Report」セクションを付加。

---

## 👤 Developer / 開発者

**Isao Matsumoto（松本 勲）**

- 27 years in Architectural Painting / 建築塗装業界 27年
  - 15 years: Kanto region, Japan（関東：東京・神奈川）
  - 12 years: Sydney, Australia（シドニー、オーストラリア）
- Founder, Samurai Painting Services（Samurai Painting Services 代表）
- AI Consultant / AI Automation Specialist（AIコンサルタント・AI自動化 転換中）
- Returning to Kanto, Japan — October 2026（2026年10月 関東帰国予定）

**Contact / 連絡先**
- Email: isao1301111@gmail.com
- LinkedIn: [linkedin.com/in/isao-matsumoto-1b271411b](https://linkedin.com/in/isao-matsumoto-1b271411b)

---

⭐ If this tool is useful or inspires you, please give it a Star!  
⭐ 役に立ったら、ぜひ Star をお願いします！
