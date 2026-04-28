# LUMINA-30 構造マップ

公式構造関係定義  
（2026年4月 現行リポジトリマップ）

本リポジトリは、LUMINA-30エコシステム内のリポジトリ間の安定した構造的関係を定義する。

本リポジトリは記述的であり、規範的ではない。

新たな権限、政策、実装ロジックを導入しない。

---

## LUMINA-30内での位置づけ

主な対象者：保守担当、レビュー担当、repo間関係を確認する読者。

LUMINA-30 repo群の関係構造を確認する場合に使用する。

正典本文や事故レビュー手順の代替としては使用しない。

- [Lumi30-Index / LUMINA-30 索引](https://github.com/lumina-30/Lumi30-Index)  
  主要repo索引と入口導線に使用。

- [LUMINA-30 Overview / LUMINA-30 概要](https://github.com/lumina-30/lumina-30-overview)  
  repo関係の前に概念構造を確認する場合に使用。

- [Incident Review Hub / 事故レビュー主ハブ](https://github.com/lumina-30/lumina30-incident-review)  
  実務上の事故レビュー導線に使用。

---

## 位置づけ

本リポジトリは、正典層および参照層の外側に位置する。

構造明示レイヤーとしてのみ機能する。

正典文書を変更しない。  
執行機構を定義しない。  
ガバナンス提案を導入しない。

---

## 現行リポジトリ構成の対象範囲

現在の公開repo構成は、以下の構造的役割として扱う。
この一覧は記述用であり、階層、権限、認証状態、準拠状態、運用義務を作らない。

---

## Layer 0 — 文明的境界（正典中核）

目的：  
不可侵の文明的境界を定義する。

対象：
- LUMINA-30

特性：
- 正典としての境界参照
- 非処方的
- 正典的意味の変更不可

注記：  
SUPおよび数理補足資料は、現行公開リポジトリマップでは単独リポジトリとして列挙しない。  
これらは固定補助記録として残り、必要な場合は Index、Public Record、PDF Archive、FullText、または関連するアーカイブ導線を通じて参照する。

---

## Layer 1 — 入口・翻訳・公開発見層

目的：  
境界概念を構造的に可読化し、入口導線を提供する。

対象：
- .github
- lumina-30-overview
- Lumi30-Index
- lumina30-public-reference

特性：
- 入口層
- 検索インデックス最適化
- 公開発見性と引用補助
- 執行ロジックを含まない

---

## Layer 2 — 構造的責任・制御層

目的：  
人間の拒否権が保持される、または消失する構造条件を記述する。

対象：
- stop-authority-reference
- ai-accountability-reference
- institutional-friction-toolkit

特性：
- 記述的
- 手続的
- 非処方的

---

## Layer 3 — 運用レビュー・記録層

目的：  
主たる事故後レビュー経路、固定公開記録の真正性、安定したアーカイブ配布、全文参照補助を提供する。

対象：
- lumina30-incident-review
- Lumi30-Public-Record
- Lumi30-PDF-Archive
- Lumi30-FullText

特性：
- レビュー指向
- 記録保存指向
- 実務参照型
- リポジトリ横断互換

---

## レイヤー外の構造明示

目的：  
いずれのリポジトリの地位も変更せず、repo間関係を明示する。

対象：
- lumina-30-structure-map

特性：
- 構造明示のみ
- 正典変更なし
- 執行機構なし
- ガバナンス提案なし

---

## 構造の流れ

主方向：  
境界 → 入口 / 翻訳 → 責任 → レビュー / 記録

逆探索経路（事故起点ルート）：  
事故 → Incident Review → 構造的責任 → 入口 / 翻訳 → 境界

---

## ガバナンス注記

本構造マップは、解釈を安定化するためのものである。

調整義務を作らず、義務を課さず、既存リポジトリの地位を変更しない。

---

## 関連リポジトリ

目的に応じて以下を参照する。

- [Organization Profile / 組織入口](https://github.com/lumina-30)  
  初見者向けの組織レベル入口。

- [LUMINA-30 Charter / LUMINA-30 正典](https://github.com/lumina-30/LUMINA-30)  
  正典としての境界参照。

- [LUMINA-30 Overview / LUMINA-30 概要](https://github.com/lumina-30/lumina-30-overview)  
  概念概要と視覚導線。

- [Lumi30-Index / LUMINA-30 索引](https://github.com/lumina-30/Lumi30-Index)  
  repo群全体の入口索引。

- [FullText Reference / 全文参照](https://github.com/lumina-30/Lumi30-FullText)  
  全文抽出と参照補助。

- [Public Reference / 公開参照ハブ](https://github.com/lumina-30/lumina30-public-reference)  
  公開向けの簡潔な引用・発見性入口。

- [Incident Review Hub / 事故レビュー主ハブ](https://github.com/lumina-30/lumina30-incident-review)  
  事故レビューと境界判定の主リポジトリ。

- [Stop Authority Reference / 拒否権定義アンカー](https://github.com/lumina-30/stop-authority-reference)  
  stop/refusal authority の簡潔な定義アンカー。

- [AI Accountability Reference / 説明責任参照](https://github.com/lumina-30/ai-accountability-reference)  
  制度的説明責任と責任連続性の参照。

- [Institutional Friction Toolkit / 制度摩擦ツールキット](https://github.com/lumina-30/institutional-friction-toolkit)  
  停止不全と手続的無効の分析。

- [Public Record / 公開記録真正性](https://github.com/lumina-30/Lumi30-Public-Record)  
  固定記録識別子とハッシュ参照。

- [PDF Archive / PDF固定配布](https://github.com/lumina-30/Lumi30-PDF-Archive)  
  安定配布用のPDFアーカイブ。
