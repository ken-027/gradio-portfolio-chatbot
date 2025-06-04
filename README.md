---
title: portfolio_chatbot
app_file: __main__.py
sdk: gradio
sdk_version: 5.32.1
---
### Setup environment variables
---

```md
OPENAI_API_KEY=<your-openai-key>
PUSHOVER_USER=<your-pushover-user-key>
PUSHOVER_TOKEN=<your-pushover-token>
RATELIMIT_API="https://ratelimiter-api.ksoftdev.site/api/v1/counter/fixed-window"
REQUEST_TOKEN=<any-token>
```

### Installation
1. Clone the repo
---
```cmd
git clone httsp://github.com/ken-027/gradio-portfolio-chatbot.git
```

2. Create and set a virtual environment
---
```cmd
python -m venv agent
agent\Scripts\activate
```

3. Install dependencies
---
```cmd
pip install -r requirements.txt
```

4. Run the app
---
```cmd
py .
```
