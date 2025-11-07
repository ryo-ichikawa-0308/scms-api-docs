# Simple contract management system API設計標準仕様書

本書は、[simple-contract-management-system](https://github.com/ryo-ichikawa-0308/simple-contract-management-system)におけるAPIの定義と設計に関するルールを記載した標準仕様書である。

APIはNestJS(TypeScript)で実装することを前提とし、[API設計マニュアル](./api-docs-tutorial.md)と、個別APIの設計サンプルで構成される。

## 構成要素

| ファイル/ディレクトリ                        | 役割                     | 備考                                                                                                                  |
| -------------------------------------------- | ------------------------ | --------------------------------------------------------------------------------------------------------------------- |
| [api-docs-tutorial.md](api-docs-tutorial.md) | API設計マニュアル        | 本ドキュメントのメインコンテンツ。API設計書の記載手順(設計原則、RESTfulルール、エラーハンドリングなど)を定義する。    |
| [api](./api/)                                | 設計書サンプル           | API設計マニュアルに従って記載した、各エンドポイントの具体的な仕様書を格納する。                                       |
| [ai-generated](./ai-generated/)              | 設計書サンプル(JSON)     | 定義サンプルを、[scms-prompts](https://github.com/ryo-ichikawa-0308/scms-prompts)プロンプトによって処理した出力結果。 |
| README.md(本書)                              | ドキュメントの概要と構成 |                                                                                                                       |

## 設計書のファイル構成

- **[api-docs-tutorial.md](./api-docs-tutorial.md)** API設計マニュアル。本プロジェクトのメインコンテンツ。

---

- **[apilist.md](./api/apilist.md)** API一覧。システムで提供するエンドポイントの概要を定義する。
- **[auth_login.md](./api/auth_login.md)** ログインAPI。
- **[auth_logout.md](./api/auth_logout.md)** ログアウトAPI。
- **[user_services_list.md](./api/user_services_list.md)** サービス一覧API。
- **[user_services_detail.md](./api/user_services_detail.md)** サービス詳細API。
- **[contracts_list.md](./api/contracts_list.md)** 契約一覧API。
- **[contracts_detail.md](./api/contracts_detail.md)** 契約詳細API。
- **[contracts_create.md](./api/contracts_create.md)** サービス契約API。
- **[contracts_cancel.md](./api/contracts_cancel.md)** サービス解約API。

---

- **[api.json](./ai-generated/api.json)** API設計書をJSON変換プロンプトで変換したJSONファイル。

(C)2025 Ryo ICHIKAWA
