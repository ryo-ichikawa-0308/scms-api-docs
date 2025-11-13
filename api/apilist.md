# API一覧

| No  | API名                                                 | エンドポイント                      | リソース        | アクション | メソッド | ビジネスドメイン | 認証要否 | 備考 |
| --- | ----------------------------------------------------- | ----------------------------------- | --------------- | ---------- | -------- | ---------------- | -------- | ---- |
| 101 | [ログイン](./auth_login.md)                           | `/api/v1/auth/login`                | `auth`          | `login`    | `POST`   | 認証             | 不要     |      |
| 102 | [ログアウト](./auth_logout.md)                        | `/api/v1/auth/logout`               | `auth`          | `logout`   | `POST`   | 認証             | 要       |      |
| 103 | [トークンリフレッシュ](./auth_refresh.md)             | `/api/v1/auth/refresh`              | `auth`          | `refresh`  | `POST`   | 認証             | 不要     |      |
| 201 | [サービス一覧](./user_services_list.md)               | `/api/v1/user-services/list`        | `user-services` | `list`     | `POST`   | サービス         | 要       |      |
| 202 | [サービス詳細](./user_services_detail.md)             | `/api/v1/user-services/{serviceId}` | `user-services` | `detail`   | `GET`    | サービス         | 要       |      |
| 203 | [サービス登録](./services_create.md)                  | `/api/v1/services/`                 | `services`      | `create`   | `POST`   | サービス         | 要       |      |
| 204 | [ユーザー提供サービス登録](./user_services_create.md) | `/api/v1/user-services/`            | `user-services` | `create`   | `POST`   | サービス         | 要       |      |
| 301 | [契約一覧](./contracts_list.md)                       | `/api/v1/contracts/list`            | `contracts`     | `list`     | `POST`   | 契約             | 要       |      |
| 302 | [契約詳細](./contracts_detail.md)                     | `/api/v1/contracts/{contractId}`    | `contracts`     | `detail`   | `GET`    | 契約             | 要       |      |
| 401 | [サービス契約](./contracts_create.md)                 | `/api/v1/contracts/`                | `contracts`     | `create`   | `POST`   | 契約             | 要       |      |
| 402 | [サービス解約](./contracts_cancel.md)                 | `/api/v1/contracts/{contractId}`    | `contracts`     | `cancel`   | `PATCH`  | 契約             | 要       |      |
| 501 | [ユーザー登録](./users_create.md)                     | `/api/v1/users/`                    | `users`         | `create`   | `POST`   | ユーザー管理     | 不要     |      |
