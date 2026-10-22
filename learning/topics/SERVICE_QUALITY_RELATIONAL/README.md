# ゼミ合宿課題：長期的関係とサービス品質

## 問い
固定額の先払い・品質が観察不能・成果連動契約が使えない、というサービス取引で、
なぜ一回限りでは高品質が実現せず、関係の継続によって何が変わり、
どんな取引条件のもとで高品質が維持できるのか（繰り返しゲーム／関係的契約のロジック）。

## 範囲
課題文：[attachments/seminar_camp_assignment_service_quality_ja.md](attachments/seminar_camp_assignment_service_quality_ja.md)（原本PDFも同フォルダ）

## 提出物（4点）
| # | 区分 | ファイル | 状態 |
| --- | --- | --- | --- |
| 1 | 作業用資料 | [deliverables/01_notation-table.md](deliverables/01_notation-table.md) | 未着手 |
| 2 | 作業用資料 | [deliverables/02_problem-formulation.md](deliverables/02_problem-formulation.md) | 未着手 |
| 3 | 完成稿 | [deliverables/03_main-text.md](deliverables/03_main-text.md) | 未着手 |
| 4 | 完成稿 | [deliverables/04_technical-appendix.md](deliverables/04_technical-appendix.md) | 未着手 |

提出締切は過ぎており、個人的な学習として2026-10-06から再度取り組んでいる。課題の要件（4点・一貫性・変更記録）は守る。

## 固有の注意
- 仮定・記号・分析方法・結論を変更したら、必ず [deliverables/00_change-log.md](deliverables/00_change-log.md) に「何を・なぜ・どこに影響するか」を記録し、4文書を一貫して更新する（課題の要件）。
- 行動順序・情報構造・契約の範囲は課題文のまま。変えない。
- 本文には結論に必要な式だけ。計算はTechnical Appendixへ。
- すべて日本語。

## 進め方のルール（2026-10-06 本人の指示）
Thinking_Math と同じ方式で進める。
- 初稿は本人が書く。AIは答え・定義・式を代わりに書かない。
- AIは `Thinking_Math/ai-check-protocol.md` の BLOCK 0〜7 に沿って、先生のスタイルで質問を一つずつ投げる。本人が答えてから次へ進む。
- 誤答・つまずきもそのまま記録に残す。
- AIが例や選択肢を先に出してしまった場合は、採用するかどうかを本人が判断し、記録に残す。

## 記録の形式（2026-10-22 から、本人の決定）
旧10ファイル形式を使う。日付フォルダ `YYYY-MM-DD/` に `0_checklist.md`〜`9_next-actions.md` を置き、トップの `latest-understanding.md` に骨格だけを累積する。
- 作った日付フォルダ：`scripts/create_topic_day_folder.sh SERVICE_QUALITY_RELATIONAL YYYY-MM-DD`（作成先は 2026-10-22 に `learning/topics` へ修正済み）
- **埋めるのは、実際に作業した分だけ。** 使わなかったファイルは空のまま置いてよい。空のひな形は活動の記録には数えない。
- 日付フォルダの `5_ai-vs-self.md` に、自分の理解とAIの理解を分けて書く。AIが説明・代行した箇所は明記する。
- 10/6〜14 の経過は `records/` に残してある（過去分。新しい日は日付フォルダを使う）。
- 注意：ゼミの新しい共通ルール（10/7〜）は「新しい通常学習では旧10ファイル一式を作らない」としている。本人が選んで使っている。重くなって続かなくなりそうなら、最小限（`2_current-understanding.md` と `9_next-actions.md` だけ）に絞る。
