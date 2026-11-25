# Integration-Test-Design
- Github Coplotでのテスト設計をサポートするテンプレート

# ディレクトリ
## ディレクトリ構造
```text
Integration-Test-Design/
│
├── AGENTS.md
│
├── .github/
│   └── skills/
│       ├── specification-analysis/
│       ├── document-analysis/
│       ├── test-design/
│       ├── excel-generation/
│       └── test-review/
│
├── input/
│   ├── specifications/
│   ├── templates/
│   └── guidelines/
│
├── intermediate/
│
├── output/
│
├── scripts/
│   ├── common/
│   └── validation/
│
├── requirements.txt
└── README.md
```

## プロジェクト全体の設定
| ファイル | 説明 |
|---|---|
| `AGENTS.md` | AIエージェントに守らせる基本的なルールを定義する |
| `README.md` | フォルダ階層や本テンプレートの概要を記載する |
| `requirements.txt` | Pythonで使用するライブラリの一覧 |

## Skills
- .github/skills/:AIに仕事の進め方を教える場。AIに特定の作業をさせるための手順書のようなもの
- それぞれのフォルダにあるSKILL.mdにAIへの指示を書く

| Skill | 担当する仕事 |
|---|---|
| `document-analysis` | Word・Excelの分析 |
| `specification-analysis` | システムから出力したJSON仕様の分析 |
| `test-design` | テスト観点・テストケースの設計 |
| `test-review` | テスト観点やテストケースのレビュー |
| `excel-generation` | Excelテンプレートへの書き込み |

