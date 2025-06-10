# 🌐 Network Module

A lightweight and reusable networking module for handling API requests and real-time communication.

## 🚀 Features
- Simple REST API client (GET, POST, etc.)
- Token-based authentication support
- Optional WebSocket/Socket.IO integration
- Timeout and retry handling

## ⚙️ Technologies
- Python (`httpx` or `requests`)
- JavaScript (`axios`)
- Optional: WebSocket support

## 🧪 Example

```python
from network.api_client import APIClient

client = APIClient("https://api.example.com", token="your_token")
response = client.get("/data")
print(response.json())
