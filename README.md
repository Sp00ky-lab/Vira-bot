🦠 Vira Bot v2.0 - Advanced Desktop Pet
Vira Bot is an interactive, highly customizable desktop companion built with Python and Tkinter. Unlike static pets, Vira Bot features a sophisticated state machine, dynamic movement logic, and a full-featured context menu for real-time adjustments.

✨ Features
🎭 State-Driven Animations: Automatically switches between idle, walk, run, and scary modes based on movement speed and user interaction.

🖱️ Interactive Controls:

Left Click + Drag: Move Vira Bot anywhere on your screen.

Double Click: Trigger "Scary Mode" manually.

Hover Effect: The bot reacts when you move your mouse over it.

Right Click Menu: A professional, dark-themed GUI menu to control everything.

⚙️ Advanced Customization:

Speed Control: Set speeds from "Snail" (1) to "Lightning" (10).

Scale Adjustment: Resize the bot from 0.2x to 0.8x on the fly.

Dynamic Assets: Load entirely new character skins without restarting the app.

Behavior Logic: Toggle random behaviors or force specific movement patterns.

🛠️ Settings Panel: Fine-tune animation delays, movement fluidity, and ground offset heights.

🚀 Installation
Clone the repository:

Bash
git clone https://github.com/yourusername/vira-bot.git
cd vira-bot
Install Dependencies:
Vira Bot requires Pillow for image processing.

Bash
pip install Pillow
Prepare Assets:
Ensure your folder structure looks like this:

Plaintext
/assets
  /idle
    1.png, 2.png
  /walk
    1.png, 2.png
  /run
    1.png, 2.png
  /scary
    1.png, 2.png
Run the Bot:

Bash
python vira_bot.py
🎮 How to Use
Right Click on Vira Bot to open the Control Hub.

Use the Appearance menu to load your own custom sprites.

Check the Info section for real-time stats like coordinates and current speed.

🛠️ Built With
Python 3.x

Tkinter (GUI Framework)

Pillow (PIL) (Image Rendering)
