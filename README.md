# 🔗 Webhook Tester

Test and debug webhooks with ease. Generate curl commands, view payload examples, and debug webhook integrations.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://turtles-ai-lab.github.io/webhook-tester)

## ✨ Features

- 🚀 **cURL Command Generator** - Generate ready-to-use webhook test commands
- 📦 **Payload Examples** - Common webhook payload templates
- 🔍 **Request Inspector** - Inspect headers, body, and response
- 📋 **Copy to Clipboard** - One-click copy for commands and payloads
- 🎯 **Multiple HTTP Methods** - Support for POST, GET, PUT, DELETE
- 📱 **Mobile Friendly** - Test webhooks from any device
- ⚡ **No Backend Required** - Pure client-side tool

## 🚀 Quick Start

### Use Online
Visit: **[https://turtles-ai-lab.github.io/webhook-tester](https://turtles-ai-lab.github.io/webhook-tester)**

### Run Locally
```bash
git clone https://github.com/Turtles-AI-Lab/webhook-tester.git
cd webhook-tester
open index.html
```

## 📖 How to Use

1. Enter your webhook URL
2. Select HTTP method (POST, GET, PUT, DELETE)
3. Add headers if needed
4. Customize the JSON payload
5. Copy the generated cURL command
6. Run in terminal or use the built-in tester

## 💡 Use Cases

- **API Development** - Test webhook endpoints during development
- **Integration Testing** - Verify webhook handlers
- **Debugging** - Troubleshoot webhook issues
- **Documentation** - Generate example webhook calls
- **Learning** - Understand webhook structure and format

## 🔧 Common Webhooks Supported

- GitHub webhooks
- Stripe webhooks
- Slack webhooks
- Discord webhooks
- Custom API webhooks
- Generic JSON payloads

## 📋 Example cURL Command

```bash
curl -X POST https://your-webhook-url.com/endpoint \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer your-token" \
  -d '{
    "event": "test",
    "data": {
      "message": "Hello from Webhook Tester"
    }
  }'
```

## 📄 License

MIT License - see [LICENSE](LICENSE) file

## 🏢 About

Built by **Turtles AI Lab**

📧 Contact: jgreenia@jandraisolutions.com

---

**Free tool for developers and API integrators**
