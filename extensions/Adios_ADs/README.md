```
 /$$$$$$$$ /$$                        /$$$$$$  /$$$$$$$        /$$$$$$$              /$$               /$$                          
|__  $$__/| $$                       /$$__  $$| $$__  $$      | $$__  $$            | $$              | $$                          
   | $$   | $$$$$$$   /$$$$$$       | $$  \ $$| $$  \ $$      | $$  \ $$ /$$   /$$ /$$$$$$    /$$$$$$$| $$$$$$$   /$$$$$$   /$$$$$$ 
   | $$   | $$__  $$ /$$__  $$      | $$$$$$$$| $$  | $$      | $$$$$$$ | $$  | $$|_  $$_/   /$$_____/| $$__  $$ /$$__  $$ /$$__  $$
   | $$   | $$  \ $$| $$$$$$$$      | $$__  $$| $$  | $$      | $$__  $$| $$  | $$  | $$    | $$      | $$  \ $$| $$$$$$$$| $$  \__/
   | $$   | $$  | $$| $$_____/      | $$  | $$| $$  | $$      | $$  \ $$| $$  | $$  | $$ /$$| $$      | $$  | $$| $$_____/| $$      
   | $$   | $$  | $$|  $$$$$$$      | $$  | $$| $$$$$$$/      | $$$$$$$/|  $$$$$$/  |  $$$$/|  $$$$$$$| $$  | $$|  $$$$$$$| $$      
   |__/   |__/  |__/ \_______/      |__/  |__/|_______/       |_______/  \______/    \___/   \_______/|__/  |__/ \_______/|__/      
```            
# **Because Ads Weren’t on Your To-Do List**

Meet **My Ad Blocker** — a tiny Chrome extension with one very simple mission:

> **Remove ads before they even realize they were invited.**

No debates.  
No hesitation.  
Just clean, uninterrupted browsing.

Powered by Chrome’s **Declarative Net Request (DNR)** API, it blocks known ad domains at the browser level to keep your browsing sharp and uncluttered.


🚀 Features

Blocks ad networks like:

- doubleclick.net

- googleadservices.com

- Zero background scripts — fast and lightweight

- Minimal rule set — easy to understand and modify

- Chrome applies the rules natively — no JS required

🧠 How It Works (Zero Boredom Version)

Chrome basically lets you say:

“See this domain?”
“Yeah?”
“Block it.”
“Say no more.”

Your rules_1.json contains the list of domains Chrome should launch into the void.

📦 Files You Actually Care About
manifest.json

Defines the extension, icons, permissions, and tells Chrome:
“I’m about to block some things.”

rules_1.json

Contains the ad domains.
Basically the extension’s hit list.

🔧 Installation (For Devs)
```
┌───────────────────────────────────────────────┐
│ 1. Open Chrome and go to:                     │
│      chrome://extensions                      │
├───────────────────────────────────────────────┤
│ 2. Enable "Developer mode" (top right).       │
├───────────────────────────────────────────────┤
│ 3. Click the "Load unpacked" button.          │
├───────────────────────────────────────────────┤
│ 4. Select your project folder.                │
├───────────────────────────────────────────────┤
│ 5. The extension appears and starts blocking. │
└───────────────────────────────────────────────┘
```
⚠️ Disclaimer

This extension is simple.
Really simple.
Like “my first bullet list” simple.

It blocks a couple of known ad domains — and it does that job well —
but it’s not trying to compete with uBlock Origin (yet).

🌟 Why This Exists

Sometimes you don’t want a 20,000-rule ad blocker.
Sometimes you just want something:

- tiny

- readable

- hackable

- yours

Now… you have it.

🤝 Contributing

PRs welcome.
New rules welcome.
Bad jokes in PR descriptions extra welcome.
