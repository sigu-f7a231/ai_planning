# 個別アプリの仮仕様

各ファイルは、ポートフォリオ用アプリの仕様を検討するための初期案です。実装前に、使えるLLM環境・開発時間・利用者テストに合わせて見直します。

| アプリ | 技術 | 分析ファイル |
|---|---|---|
| 架空店舗FAQボット | Dify | [dify_faq.md](./dify_faq.md) |
| 自分のメモ検索 | LlamaIndex | [llamaindex_notes.md](./llamaindex_notes.md) |
| 家計CSVの説明 | LangChain | [langchain_budget.md](./langchain_budget.md) |
| 分岐型○×クイズ | LangGraph | [langgraph_quiz.md](./langgraph_quiz.md) |
| お出かけプラン作成 | CrewAI | [crewai_trip.md](./crewai_trip.md) |
| 買い物リスト整理 | Pydantic AI | [pydantic_shopping.md](./pydantic_shopping.md) |

共通方針は、追加費用を抑え、各アプリを独立したプロジェクト・GitHubリポジトリ・Docker Compose環境で作ることです。個人情報や秘密情報をサンプルデータに含めず、モックと実LLMで確認した範囲を明確にします。
