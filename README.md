import time
import sys

def typing(text, speed=0.03):
    for char in text:
        sys.stdout.write(char)
        sys.stdout.flush()
        time.sleep(speed)
    print()

typing("Initializing profile...")
time.sleep(1)

typing("Accessing developer data...")
time.sleep(1)

typing("\n==============================")
typing("        DEVELOPER BIO")
typing("==============================\n")

bio = [
"Name: NITISH KUMAR PRADHAN",
"Role: Python Developer",
"",
"Skills:",
"  • Python",
"  • Automation Scripts",
"  • Data Analysis",
"  • Web Scraping",
"",
"About Me:",
"  I love building creative tools and automations.",
"  Turning ideas into code is my passion.",
"",
"GitHub: https://github.com/yourusername"
]

for line in bio:
    typing(line, 0.04)
    time.sleep(0.2)

typing("\n>>> Thanks for visiting my GitHub profile! 🚀")
