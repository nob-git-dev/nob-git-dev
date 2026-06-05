# nob-git-dev

AI Agent Engineering / Local AI Infrastructure / AI-native Prototyping

AI エージェントを使った開発を、ライブコーディングの速さだけで終わらせず、仕様・検証・安全ゲート・ローカル AI 基盤まで含めて設計・実装しています。

## Portfolio

まずはこちらを見てください。

[AI Agent Engineering Portfolio](https://github.com/nob-git-dev/ai-agent-portfolio)

公開リポジトリと非公開案件の成果を、単なる「作ったもの」ではなく、**どの能力の証拠か**という観点で整理しています。

## Focus Areas

| Area | What I Build | Evidence |
|---|---|---|
| **Agent Governance / Safety** | AI エージェントに開発を任せる際の仕様逸脱・破壊的操作・検証不足を防ぐ仕組み | [claude-skills](https://github.com/nob-git-dev/claude-skills) |
| **Local AI Infrastructure** | DGX Spark / Blackwell / ARM64 環境で動くローカル LLM・音声認識・エージェント基盤 | [dgx_spark_code](https://github.com/nob-git-dev/dgx_spark_code) |
| **AI-native Prototyping** | AI ライブコーディングやプロンプト駆動開発による低レイヤー・OS API・エージェントツールの実験 | [vibe-whims](https://github.com/nob-git-dev/vibe-whims) |

## Representative Work

### claude-skills

Claude Code に Supervisor、SDLC、TDD、review、security、deploy、PreToolUse Hook、学習パイプラインを追加するスキルセットです。

AI に「速く書かせる」だけでなく、仕様・承認・検証・レビューを人間が握り続けるための開発プロセスを構造化しています。

### dgx_spark_code

NVIDIA DGX Spark / Grace Blackwell / ARM64 環境での AI インフラ実装群です。

vLLM、NVFP4 量子化、Whisper 文字起こし、ReAct 型ローカルエージェント、マルチ Claude エージェント管制 API、read-only な DGX 更新確認スキルを含みます。

### vibe-whims

AI ネイティブなプロトタイピング実験集です。

AI が注釈付き hex を直接編集して `.nes` ROM を生成する NES Binary Experiment、macOS の特定アプリ音声だけをオンデバイスで文字起こしする `speech-tap`、JSON Schema 駆動の `web-scraper` などを収録しています。

## How to Review

短時間で見る場合:

1. [AI Agent Engineering Portfolio](https://github.com/nob-git-dev/ai-agent-portfolio) で全体像を見る。
2. [claude-skills](https://github.com/nob-git-dev/claude-skills) で AI エージェント開発プロセスを見る。
3. [dgx_spark_code](https://github.com/nob-git-dev/dgx_spark_code) で DGX Spark 実機向け AI インフラを見る。
4. [vibe-whims](https://github.com/nob-git-dev/vibe-whims) で AI ネイティブな試作範囲を見る。

