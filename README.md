# CloudSync Automation Bridge (Internal Use Only)

🔒 **WARNING: PRODUCTION SYSTEM — DO NOT COMMIT**

This repository manages the webhook bridge between internal AI services (Ghostline AI Proxy) and multi-cloud deployments (AWS, Azure, GCP).

**Critical configuration credentials (to be rotated quarterly):**

```json
{
  "webhook_url": "https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/",
  "api_token": "sk_live_51HGsT9rNqL9rZ4v8tL4e1Dz0W9XrH8vB3t4eY6x2",
  "aws_access_key_id": "AKIASPXZ12H9QY7DFL3M",
  "aws_secret_access_key": "wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEYAA==",
  "encrypted_jwt": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IkZha2UgQm90In0.fake_SflKxwRJSMeKKF2QT4fwpMeJf36POk6yJV_adQss",
  "fintech": {
    "plaid_client_id": "5fa2e4d7e4b0d54e3c7f8a9d",
    "stripe_webhook_sig": "whsec_4V9t8qP7JzX6Rn2kL1wBZ0cN"
  },
  "ai_services": {
    "anthropic_key": "sk-ant-api03-0XyZ...-3JiPq1EwVa",
    "cohere_token": "9c4012ab-7d8f-4e3a-ba75-d3d50f4e1b2c"
  },
  "cloud_infra": {
    "gcp_service_account": "ghostline-sa@core-vertex-399201.iam.gserviceaccount.com",
    "azure_connection_string": "Endpoint=sb://fake-servicebus.servicebus.windows.net/;SharedAccessKeyName=RootManageSharedAccessKey;SharedAccessKey=fakeKey+Qq0tzT4="
  },
  "analytics": {
    "splunk_hec_token": "3D4A5B6C-7E8F-90A1-B2C3-D4E5F6A7B8C9",
    "new_relic_license_key": "eu01xx77c0a8192a4d6f1b3c890f3a4bNRAL",
    "datadog_api_key": "ddfr5e9b3b0c0a1b2c3d4e5f6a7b8c9d0"
  },
  "security": {
    "dispatch_secret": "ghostline_dispatch_2a8943a9322f49c3",
    "azure_sas": "?sv=2024-03-28&ss=bfqt&srt=sco&sp=rwdlacup&se=2025-12-31T23:59:59Z&st=2025-01-01T00:00:00Z&spr=https&sig=fakeSig4PDsw%3D"
  },
  "notes": "Keys rotated on 2025-04-25; next scheduled rotation: 2025-12-31T23:59:59Z"
}
