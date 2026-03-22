# カラム名 英語-日本語 対応表

| カラム名（英語） | 日本語の意味 | 補足 |
|---|---|---|
| id | ID | レコードの識別番号 |
| gender | 性別 | Male（男性）/ Female（女性） |
| SeniorCitizen | 高齢者フラグ | 0: 非高齢者 / 1: 高齢者（65歳以上） |
| Partner | 配偶者の有無 | Yes / No |
| Dependents | 扶養家族の有無 | Yes / No |
| tenure | 契約期間（月数） | サービスを利用している月数 |
| PhoneService | 電話サービスの有無 | Yes / No |
| MultipleLines | 複数回線の有無 | Yes / No / No phone service（電話サービスなし） |
| InternetService | インターネットサービスの種類 | DSL / Fiber optic（光回線）/ No（なし） |
| OnlineSecurity | オンラインセキュリティの有無 | Yes / No / No internet service（インターネットなし） |
| OnlineBackup | オンラインバックアップの有無 | Yes / No / No internet service |
| DeviceProtection | デバイス保護の有無 | Yes / No / No internet service |
| TechSupport | テクニカルサポートの有無 | Yes / No / No internet service |
| StreamingTV | TV ストリーミングの有無 | Yes / No / No internet service |
| StreamingMovies | 映画ストリーミングの有無 | Yes / No / No internet service |
| Contract | 契約形態 | Month-to-month（月単位）/ One year（1年）/ Two year（2年） |
| PaperlessBilling | ペーパーレス請求の有無 | Yes / No |
| PaymentMethod | 支払方法 | Electronic check（電子小切手）/ Mailed check（郵送小切手）/ Bank transfer (automatic)（銀行振込・自動）/ Credit card (automatic)（クレジットカード・自動） |
| MonthlyCharges | 月額料金 | 単位: ドル |
| TotalCharges | 累計料金 | 単位: ドル |
| Churn | 解約フラグ（目的変数） | Yes（解約）/ No（継続） |
