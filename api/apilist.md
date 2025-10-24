# API一覧

| No  | API名                                     | エンドポイント                      | メソッド | 系統 | 認証要否 | 備考 |
| --- | ----------------------------------------- | ----------------------------------- | -------- | ---- | -------- | ---- |
| 101 | [ログイン](./auth_login.md)               | `/api/v1/auth/login`                | `POST`   | 認証 | 不要     |      |
| 102 | [ログアウト](./auth_logout.md)            | `/api/v1/auth/logout`               | `POST`   | 認証 | 要       |      |
| 201 | [サービス一覧](./user_services_list.md)   | `/api/v1/user_services/list`        | `POST`   | 取得 | 要       |      |
| 202 | [サービス詳細](./user_services_detail.md) | `/api/v1/user_services/{serviceId}` | `GET`    | 取得 | 要       |      |
| 301 | [契約一覧](./contracts_list.md)           | `/api/v1/contracts/list`            | `POST`   | 取得 | 要       |      |
| 302 | [契約詳細](./contracts_detail.md)         | `/api/v1/contracts/{contractId}`    | `GET`    | 取得 | 要       |      |
| 401 | [サービス契約](./contracts_create.md)     | `/api/v1/contracts/create`          | `POST`   | 登録 | 要       |      |
| 402 | [サービス解約](./contracts_cancel.md)     | `/api/v1/contracts/cancel`          | `PUT`    | 更新 | 要       |      |
