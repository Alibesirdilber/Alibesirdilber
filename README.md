Hi there 👋

I'm Ali! I'm just getting started with software development and I'm currently learning Python.
I'm especially interested in building small study assistant projects to practice and improve my skills.

🌱 Currently Learning
-Python fundamentals
-Algorithms & problem-solving
-Simple automation and helper applications

🔭 What I'm Working On
-My own study assistant project

🤝 Open to Collaborations
-Beginner-friendly Python projects
-Learning-focused mini applications

💬 Ask Me About
-Python learning resources
-Beginner project ideas

📘Following these resources:
https://learn.microsoft.com/en-us/shows/intro-to-python-development/
https://learn.microsoft.com/en-us/shows/more-python-for-beginners/
https://learn.microsoft.com/en-us/shows/even-more-python-for-beginners-data-tools/
# === ALI BESIR DILBER - NEON SAFE MODE ===
# This version is optimized for GitHub and will save without errors.

import time, sys, os

colors = [
    "\033[95m", "\033[96m", "\033[92m",
    "\033[93m", "\033[94m"
]
RESET = "\033[0m"

def neon_line(text):
    for c in colors:
        sys.stdout.write("\r" + c + text + RESET)
        sys.stdout.flush()
        time.sleep(0.12)
    print("\r" + text + RESET)

def neon_slow(text):
    for ch in text:
        sys.stdout.write(ch)
        sys.stdout.flush()
        time.sleep(0.002)
    print()

os.system("cls" if os.name == "nt" else "clear")

# Neon header
neon_line("==============================================")
neon_line("      ALI BESIR DILBER - NEON CONSOLE")
neon_line("==============================================")

print()
neon_slow("👑 Name: Ali Beşir Dilber")
neon_slow("📧 Mail: alibesirdilber@icloud.com")
neon_slow("📸 Instagram: alibesirdilber99")
print()

neon_line("Slogan:")
neon_slow("   debugging life, one line at a time")

print()
neon_line("==============================================")

print("\n")
📫You can find me on:
Linkedin: https://www.linkedin.com/in/ali-be%C5%9Fir-dilber-2429a6355/
📍Türkiye

---

🇹🇷 Kısaca Ben

Yazılıma yeni başlayan, öğrenmeye istekli ve bu alanda kendini geliştirmeyi hedefleyen biriyim. Şu anda Python öğreniyor ve küçük projelerle pratik yapıyorum.
