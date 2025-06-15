# LINE ChatGPT Bot

這是一個 Python Flask 後端，串接 LINE Bot 與 OpenAI GPT 模型。

## 使用方式

1. 設定 `.env` 檔案，或於 Render 上輸入下列變數：
   - `LINE_CHANNEL_SECRET`
   - `LINE_CHANNEL_ACCESS_TOKEN`
   - `OPENAI_API_KEY`

2. 安裝套件：

```bash
pip install -r requirements.txt