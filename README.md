## FLUX Image API Dashboard
A sleek, modern web interface for generating images using the FLUX.1 [schnell] model via Modal GPU infrastructure. Built with vanilla HTML/CSS/JS — no frameworks required.

## 🚀 Features
⚡ Single Image Generation – Generate 1024×1024 images in ~1–2 seconds
📦 Batch Processing – Up to 8 prompts processed in parallel on GPU
🔑 API Key Authentication – Secure access with per-key usage tracking
📊 Real-Time Usage Stats – Monitor daily generation counts
🎨 Customizable Parameters – Control width, height, steps, and seed
📥 PNG Download – One-click image export
📖 Built-in API Docs – cURL and Python examples included

## HTML AI UI

Model: FLUX.1 [schnell] (Apache 2.0 license)

Auth: API key-based (X-API-Key header)

## 📋 Prerequisites
A Modal account with deployed FLUX API endpoints
An API key from your LiquidVizion dashboard
Modern web browser (Chrome/Firefox/Safari/Edge)

## 🔒 Security Notes
Never expose your API key in client-side code for production use
Implement server-side proxying for production deployments
Use environment variables for sensitive configuration
Monitor usage stats regularly to detect abuse

## 📸 Screenshots
(Add screenshots of your dashboard here)

## 🤝 Contributing
Pull requests welcome! Please ensure:
Code follows existing style conventions
No breaking changes to API contracts
Updated documentation for new features

## 📄 License
This project uses the FLUX.1 [schnell] model under the Apache 2.0 license.

## 🙏 Acknowledgments
Black Forest Labs – FLUX.1 model creators
Modal – Serverless GPU infrastructure
LiquidVizion – API wrapper and dashboard design
