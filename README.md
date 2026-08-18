AI Job Match System Export
Contents
frontend/ : static frontend dashboard
backend-workflow.json : importable n8n workflow
Frontend
Serve the frontend folder with any static server.

Example:

cd frontend
python -m http.server 4173
Open: http://localhost:4173

Backend
Import backend-workflow.json into n8n.

After import, reconnect these credentials on the target system:

Groq
Google Drive
Google Sheets
Gmail
Important note
The workflow currently includes a fixed Google Drive download node for the resume source. The frontend collects resume_path and profile_text, but the backend may ignore them until that n8n flow is changed.

<!--
**Saniha26/Saniha26** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
