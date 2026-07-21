# Samurai Painting Quote Tool v4 → v6
**Smart Quotation Tool for Professional Painters / プロ塗装職人向けスマート見積もりツール**

[![v4 Live Demo](https://img.shields.io/badge/v4_Live_Demo-Click_Here-blue)](https://isao1301111-eng.github.io/samurai-painting-quote-v4/)
[![v5 + Hallucination Guard](https://img.shields.io/badge/v5_%F0%9F%9B%A1%EF%B8%8F_Hallucination_Guard-Try_Now-00e676)](https://isao1301111-eng.github.io/samurai-painting-quote-v4/samurai-painting-quote-v5.html)
[![v6 + Saved History](https://img.shields.io/badge/v6_%F0%9F%93%82_Saved_History-Try_Now-C9A84C)](https://isao1301111-eng.github.io/samurai-painting-quote-v4/samurai-painting-quote-v6.html)

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
| **v6 📂** | [https://isao1301111-eng.github.io/samurai-painting-quote-v4/samurai-painting-quote-v6.html](https://isao1301111-eng.github.io/samurai-painting-quote-v4/samurai-painting-quote-v6.html) |

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
| `samurai-painting-quote-v5.html` | v5 | + Hallucination Guard Protocol v1.0 (12-point) |
| `samurai-painting-quote-v6.html` | v6 | + Saved Quotes & Clients (history, restore, JSON backup) |

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

**12-Point Automatic Verification Engine:**
1. ✅ Active surface / item check — confirms at least one billable item exists
2. ✅ Surface area validation — all enabled surfaces must have area > 0
3. ✅ Item quantity validation — all enabled items must have qty > 0
4. ✅ Client info check — flags missing name or address
5. ✅ Job type check — warns if no job type is selected
6. ✅ Logical contradiction detection — e.g., New Build × peeling paint, New Build × oil→water switch
7. ✅ NSW market rate check ($/m²) — blended rate compared against 2025–26 market ranges per surface type
8. ✅ Line item count consistency — enumeration-verified total count
9. ✅ Total amount sanity check — flags suspiciously low totals
10. ✅ **Paint volume re-verification** — independently recalculates litres (area ÷ coverage × coats × material factor) and fails on any mismatch
11. ✅ **Paint consumption plausibility** — flags mL/m²/coat outside the physical 50–200mL range
12. ✅ **Paint cost ratio check** — warns if paint cost is an abnormal share of the surface total (normal 5–55%)

**Behavior:**
- ❌ **Errors** block quote generation — user must fix before proceeding
- ⚠️ **Warnings** are shown but do not block generation
- In STRICT MODE, the generated quote includes an **"AI Verification Report"** section appended at the bottom

**Portfolio significance:** Demonstrates "AI verifying AI output" — the tool validates its own calculations before presenting them, addressing hallucination risks in AI-generated financial documents.

---

**[日本語]**  
v5では **ハルシネーション防止プロトコル v1.0** を導入。見積書生成前にAIが自己出力を検証します。

ヘッダーの **🛡️ STRICT MODE** トグル（緑アクセント）で有効化。

**12項目の自動検証エンジン：**
1. ✅ 有効な表面・項目の存在確認
2. ✅ 有効表面の面積入力チェック
3. ✅ 有効項目の数量入力チェック
4. ✅ お客様情報入力確認
5. ✅ 作業内容（ジョブタイプ）選択確認
6. ✅ 論理矛盾検出（新築×剥離ありなど）
7. ✅ NSW市場レンジ（$/m²）照合
8. ✅ 件数＝列挙一致確認
9. ✅ 合計額サニティチェック
10. ✅ **塗料量の独立再計算** — 面積÷塗布量×回数×材質係数で再計算し、不一致なら計算エラーとして検出
11. ✅ **塗料消費量の物理的妥当性** — mL/m²/回 が物理的範囲（50〜200mL）を外れると警告
12. ✅ **塗料費比率チェック** — 塗料費が表面合計に占める割合が異常（正常5〜55%）なら警告

**エラー時は見積もり生成をブロック。** STRICTモードON時、見積書末尾に「AI Verification Report」セクションを付加。

---

## 📂 v6: Saved Quotes & Clients / 履歴・顧客管理

**[English]**  
v6 adds two things on top of v5: an **AI free-text input** and a **persistence layer**.

**🤖 AI free-text input (LLM × Guard):** describe the job in plain English or Japanese ("20yo weatherboard house, 2 storeys, 80m² exterior, peeling paint, switching oil to water") and the tool structures it into the form — then the **13-point Hallucination Guard verifies the AI's own output** (paint volume & cost, contradictions, NSW market rates) before you quote. This is the portfolio thesis in one flow: *an LLM is fast but hallucinates; a rules engine is exact but rigid — combine them so each covers the other's weakness.* Runs on the offline **demo parser** by default (no key, works for everyone); enter your own Claude API key to switch on real `claude-opus-4-8` extraction. The key is stored only in your browser and sent directly to Anthropic.

**📂 Persistence layer:** every generated quote can be saved and reused, turning the tool from a one-shot calculator into a lightweight quote ledger.

- 💾 **Save** — store a generated quote with full client info, all inputs, and its Hallucination Guard result
- 📂 **History & Clients tab** — searchable list by client name / address / quote number
- ↩ **Restore** — reopen any past quote in one click to edit and regenerate
- ⧉ **Duplicate** — spin off an alternate plan for the same client under a new quote number
- 📤📥 **JSON Export / Import** — back up or move all data between devices
- Compact quote cards show **total area (m²)** and **paint volume (L)** at a glance; a 🛡️ **Verified** chip marks quotes that passed the 13-point Guard

Data is stored locally in the browser (`localStorage`) — **no server, no API, single HTML file**, GitHub Pages–ready.

**[日本語]**  
v6ではv5の上に **AI自由記述入力** と **永続化層** の2つを追加しました。

**🤖 AI自由記述入力（LLM × Guard）：** 「築20年の木造2階建て、外壁80㎡、ひび割れあり、油性から水性に塗り替え」のように自由に書くと、AIがフォームに構造化 → その後 **13項目のハルシネーション防止がAI自身の出力を検証**（塗料量・塗料金額・矛盾・NSW相場）してから見積もりへ進みます。これは本ポートフォリオの主張を1つの流れで体現します：*LLMは速いが幻覚する／ルールエンジンは正確だが融通が利かない → 組み合わせて互いの弱点を消す。* 既定では鍵不要の**オフラインのデモ解析**で誰でも動作。自分のClaude APIキーを入れると本物の `claude-opus-4-8` 抽出に切替。キーはブラウザ内のみに保存され、Anthropicへ直接送信されます。

**📂 永続化層：** 生成した見積もりを保存・再利用でき、単発の計算ツールから軽量な**見積もり台帳**へと進化。

- 💾 **保存** — お客様情報・全入力・ハルシネーション検証結果ごと見積もりを保存
- 📂 **履歴・顧客管理タブ** — 顧客名／住所／見積番号で検索
- ↩ **復元** — 過去の見積もりをワンクリックで再表示・編集・再生成
- ⧉ **複製** — 同じ顧客の別プランを新しい見積番号で作成
- 📤📥 **JSONエクスポート／インポート** — 全データのバックアップ・端末間移行
- コンパクトなカードに**総面積（m²）**と**塗料量（L）**を表示。13項目のGuardを通過した見積もりには🛡️**検証済**チップを表示

データはブラウザ内（`localStorage`）に保存 — **サーバー不要・API不要・単一HTML**、GitHub Pages対応。

**Portfolio significance:** Demonstrates "AI verifying AI" end-to-end — an LLM proposes the structured quote, a deterministic 13-point engine audits it, and a persistence layer keeps the verified results as a real quote ledger. Deep field expertise (27 years) plus AI plus guardrails, in one self-contained page.

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
