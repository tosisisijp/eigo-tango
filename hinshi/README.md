# 英語品詞学習システム

## 概要
英語の品詞を詳細に分類・整理し、体系的な学習を支援するドキュメント集です。古典文法と現代文法の両方を含み、品詞の詳細な分類と相互関係を明確にすることで、効率的な英語学習を実現します。

## 主要品詞ファイル
- [名詞.md](名詞.md) - v1.0.0 (2025-06-08)
- [動詞.md](動詞.md) - v1.0.0 (2025-06-08)
- [形容詞.md](形容詞.md) - v1.0.0 (2025-06-08)
- [副詞.md](副詞.md) - v1.1.0 (2025-06-11)
- [代名詞.md](代名詞.md) - v1.0.0 (2025-06-08)
- [前置詞.md](前置詞.md) - v1.0.0 (2025-06-08)
- [接続詞.md](接続詞.md) - v1.0.0 (2025-06-08)

## ファイル構成

### 基本品詞
7つの主要品詞を中心とした体系的な分類

### 詳細分類ファイル
- **名詞系**: 普通名詞、固有名詞、集合名詞、物質名詞、抽象名詞、可算名詞、不可算名詞
- **動詞系**: 自動詞、他動詞、使役動詞、知覚動詞、授与動詞、連結動詞、状態動詞、進行動詞、完了動詞
- **形容詞系**: 限定形容詞、叙述形容詞、数量形容詞、同一性・識別形容詞、比較級、最上級、原級
- **副詞系**: 様態副詞、時副詞、場所副詞、移動副詞、頻度副詞、程度副詞、確信副詞、機能的分類副詞、談話標識副詞
- **代名詞系**: 人称代名詞、指示代名詞、疑問代名詞、関係代名詞、不定代名詞、再帰代名詞、所有代名詞
- **前置詞系**: 時前置詞、場所前置詞、方向前置詞、前置詞の種類
- **接続詞系**: 等位接続詞、従位接続詞、相関接続詞
- **その他の品詞**: 冠詞、助動詞（法助動詞）、間投詞

### 文法構造ファイル
- **文の構造**: 5文型と特殊構文、文の要素、文の種類、語順の基本ルール
- **句と節**: 句、節、名詞節、関係節、従属節、独立節、動詞句
- **時制**: 時制、現在時制、過去時制、未来時制、現在完了、過去完了、未来完了
- **その他**: 限定詞、修飾語、補語、述語、語、慣用句、句動詞、間投詞

### 横断的概念ファイル
- **機能別**: 状態に関わる品詞、程度に関わる品詞、場所に関わる品詞、時間に関わる品詞、所有に関わる品詞、様態と状態
- **システム**: 全体インデックス、文法タグ階層

## バージョン管理
セマンティックバージョニング（MAJOR.MINOR.PATCH）を採用

### バージョン更新基準
- **PATCH (例: 1.0.0 → 1.0.1)**: 誤字修正、例文追加、軽微な改善
- **MINOR (例: 1.0.0 → 1.1.0)**: 新分類追加、新セクション追加、構造の部分的改善
- **MAJOR (例: 1.0.0 → 2.0.0)**: 分類体系の大幅変更、構造の根本的見直し

## 更新履歴

### 2025-06-25
- **MINOR**: 句動詞.md v1.1.0 - 動詞+副詞の分類体系を大幅改善
- **改善**: 従来の「分離可能・分離不可」を「汎用分離句動詞・代名詞分離句動詞・固定句動詞」に変更
- **新分類**: 自然さの違いを明確化（代名詞分離句動詞は名詞時に非分離を推奨）
- **詳細化**: 分類体系ツリー、末端品詞比較表、使用上の注意点を全面更新

### 2025-06-11
- **MINOR**: 副詞.md v1.1.0 - 移動副詞分類を新規追加（統語機能「移動修飾」・意味機能「移動副詞」）
- **改善**: 副詞分類体系の詳細化（back, forth, along, aside等の移動を表す副詞を独立分類）
- **新規**: 011-日付管理.mdc - 日付の自動取得と管理に関する専門ルール追加
- **改善**: 010-README管理.mdc - 日付管理部分を011に分離、README管理に特化

### 2025-06-08
- **システム**: バージョン管理システムを導入
- **システム**: README管理ルールを追加
- **システム**: Git操作管理ルールを追加
- **初期化**: 主要品詞ファイル（7個）にversion・lastUpdatedフィールドを追加

## 使用方法

### 学習者向けガイド
1. **基本学習**: 主要品詞ファイルから開始
2. **詳細学習**: 各品詞の下位分類ファイルで深掘り
3. **横断学習**: 機能別・概念別ファイルで関連性を理解
4. **構造理解**: 文法構造ファイルで文の組み立てを学習

### ナビゲーション
- **全体インデックス**: [全体インデックス.md](全体インデックス.md) - 全ファイルへの包括的インデックス
- **文法タグ階層**: [文法タグ階層.md](文法タグ階層.md) - タグベースの分類体系

## 技術情報

### 開発環境
- **エディタ**: Obsidian（推奨）
- **バージョン管理**: Git/GitHub
- **ファイル形式**: Markdown (.md)

### GitHub連携
- **リポジトリ**: https://github.com/tosisisijp/eigo-hinshi.git
- **ブランチ**: main
- **更新フロー**: ローカル編集 → コミット → プッシュ → ChatGPT共有

### ルール管理
プロジェクトの品質と一貫性は以下のルールファイルで管理されています：
- **基本方針**: 品詞分類整理・文法学習の基本方針
- **編集ルール**: 変更規模別の編集プロセス
- **品質管理**: 検証・品質管理プロセス
- **相互参照**: 全体相互参照システム管理
- **Git操作**: 安全なGit操作管理
- **README管理**: README.mdの管理と更新
- **日付管理**: 日付の自動取得と管理（手動入力禁止）

## 貢献方法
1. **Issue報告**: 誤りや改善提案をGitHub Issuesで報告
2. **Pull Request**: 修正・改善のプルリクエスト
3. **フィードバック**: 学習効果や使用感のフィードバック

## ライセンス
このプロジェクトは学習目的で作成されています。自由に学習・参考にご利用ください。

---
**最終更新**: 2025-06-25  
**総ファイル数**: 約90ファイル  
**主要品詞**: 7ファイル（バージョン管理対象）  
**その他品詞**: 3ファイル（冠詞、助動詞、間投詞）  
**詳細分類**: 約80ファイル 