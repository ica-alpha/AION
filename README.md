🔥 AION – Free Fire Like Bot API 🔥

(Formerly known as Free Fire Like Bot – Now upgraded to AION for better performance and reliability!)

This API (AION) allows you to automatically send likes to Free Fire profiles using guest accounts, with improved speed and stability.
🚀 Quick Start Guide
1️⃣ Clone the Repository
bash

git clone https://github.com/your-repo/aion-freefire-like-bot
cd aion-freefire-like-bot

2️⃣ Set Up Virtual Environment
bash

python -m venv aion_env

    Windows:
    bash

.\aion_env\Scripts\activate

Linux/macOS:
bash

    source aion_env/bin/activate

3️⃣ Install Dependencies
bash

pip install -r requirements.txt

(Includes Flask, aiohttp, requests, pycryptodome, and more for optimal performance.)
4️⃣ Configure Guest Accounts

Navigate to the config folder and set up:

    ind_config.json (India server)

    br_config.json (Brazil/US/South America)

    europe_config.json (Europe/Other regions)

📌 Example:
json

[
  {
    "uid": "1234567890",
    "password": "guest123"
  }
]

5️⃣ Run AION API
bash

flask run --port 5000

(Auto-killer script included to prevent port conflicts!)
⚡ API Endpoints
🔹 GET /like

Send a like to a Free Fire profile.

✅ Parameters:

    uid (required) – Target player UID.

📡 Example Request:
http

GET /like?uid=1234567890

🛠 Advanced Features

✔ Auto-Kill Previous Processes – Ensures smooth startup.
✔ Multi-Region Support – Works with IND, BR, EU, and more.
✔ Guest Account Rotation – Prevents rate-limiting.
📜 Credits & License

👨‍💻 Developed by [AAYAN]