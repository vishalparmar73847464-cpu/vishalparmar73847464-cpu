
from pathlib import Path
from docx import Document
import pypandoc

md = """# 👋 Hi, I'm Vishal Parmar

## 🛡️ Cybersecurity Researcher | Ethical Hacker

Welcome to **Vishal Infosec AI**.

### 🌐 Connect
- Website: https://ethical-hackers.lovable.app/
- LinkedIn: https://www.linkedin.com/in/vishal-parmar-112992363
- Instagram: https://www.instagram.com/vishal.infosec.ai
- Telegram: https://t.me/+6gGFn5_CmIc5OTA1
- Freelancer: https://www.freelancer.com/u/hackerse

## 💻 Skills
- Python
- Linux
- Burp Suite
- Nmap
- Wireshark
- Metasploit
- Docker
- Git

## 📊 GitHub Stats

Add your preferred GitHub stats widgets here.

## 🚀 Featured Projects

- PhoneTrace Pro
- Vishal Infosec AI
- Android Security Research

## 📫 Contact

Feel free to connect for collaboration and cybersecurity research.
"""
# enlarge a bit
for i in range(1,101):
    md += f"\n### Section {i}\n- Placeholder content for premium README customization.\n"

out="/mnt/data/README.md"
Path(out).write_text(md,encoding="utf-8")
print(out)
