# Installation

## Requirements
- Python 3.12+
- Windows 10/11
- cloudflared

## Run

    python main.py --dev --port 8452
    cloudflared tunnel --protocol http2 --url http://127.0.0.1:8452 --no-autoupdate

Important: always use --protocol http2