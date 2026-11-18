# ケーススタディ — 私が作り、リリースした AI プロダクト

本番環境で動く AI プロダクトと自動化システムを作っています。ここでは、課題、アーキテクチャ、エンジニアリング上の制約、そして私が担当した範囲を、エンジニアに役立ち、関係企業に安全なレベルで説明します。

[English](README.md) · [Español](README.es.md) · [Português](README.pt.md)

---

## Taishoku Reset — 日本の退職代行 SaaS

日本の退職代行サービスのための本番 SaaS です。LINE からの受付、安全な Web フォーム、AI による音声・翻訳、社内の運用フローで構成されています。

- **役割:** 共同創業者 / Tech Lead
- **状態:** 2026-11-08 から本番稼働
- **このケースの範囲:** プロダクトの背景、公開フロー、ボックス単位のアーキテクチャ、エンジニアリング上の課題、担当範囲。
- **含めないもの:** ソースコード、D1 スキーマ、プロンプト、価格ロジック、オペレーターパネル、インシデント資料、顧客データ、コンバージョン指標、内部エンドポイント、分析 ID。

→ **[ケーススタディを読む](case-studies/taishoku-reset/README.ja.md)** · [プロダクト](https://taishokureset.com) · [Instagram](https://www.instagram.com/taishokureset/)

---

## 主なエンジニアリング

| プロジェクト | 示していること | リンク |
|---|---|---|
| **JA ⇄ ES Live Interpreter** | Linux 上の日西双方向通訳。PipeWire、ローカル Whisper、Vertex/Gemini 翻訳、VOICEVOX/Piper TTS、GTK4 UI、185 テスト。 | [コード](https://github.com/javperman/interprete-ja-es) |
| **video-editor-ai** | 技術チュートリアル向けの決定的な編集パイプライン。`edit_plan.json`、不変リビジョン、ローカル ASR、字幕、PiP、NVENC レンダー、QC。30 分 → 約 7.6 分、ピーク 2.5 GB。 | [コード](https://github.com/javperman/video-editor-ai) · [デモ](https://youtu.be/XcZ60adpBms) |
| **FitPrimeLab** | EN/ES/PT/JA の多言語フィットネスプラットフォーム。インタラクティブなツールと記事。 | [サイト](https://fitprimelab.com) · [コード](https://github.com/javperman/fitprimelab-site) |
| **AI Engineering Playbook** | エージェントとの開発方法。AGENTS.md の契約、フェーズ計画、レビュー、テスト、MCP、秘密情報の管理。 | [コード](https://github.com/javperman/ai-engineering-playbook) |

---

## これらのケーススタディについて

- **課題**、**公開フロー**、**ボックス単位のアーキテクチャ**、**エンジニアリング上のトレードオフ**を説明します。
- 私が担当した範囲と、担当していない範囲を記録します。
- 公開されている証拠へのリンクを示します。サイト、公開リポジトリ、公開されている法務ページ、公開 SNS です。

## 含まれないもの

- コードの公開ではありません。クライアント企業と自社のコードは非公開です。
- 顧客データ、認証情報、内部指標、プロンプト、データベーススキーマ、オペレーター画面は含みません。
- 企業の法的代理、商業条件、顧客関係の所有を主張するものではありません。

---

## 連絡先

- スタジオ: [Peresotech](https://peresotech.com) — AI と自動化の独立スタジオ。
- LinkedIn: [javier-perez-manzano](https://www.linkedin.com/in/javier-perez-manzano)
- Email: [contact@peresotech.com](mailto:contact@peresotech.com)
- プロフィール: [github.com/javperman](https://github.com/javperman)
