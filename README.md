# Discord Server Nuker  
*by pomoci*

---

## How to use:

1. **Create a Discord Bot and enable these settings:**

![Bot Settings](https://user-images.githubusercontent.com/103531974/178571775-5a315922-0c35-4672-9723-0630a584fb8e.png)

2. **Run the installer:**  
   - Start `install.bat` to install dependencies.  
3. **Start the bot:**  
   - Run `run.bat` or use the command:  
     ```bash
     python main.py
     ```
4. **Enter your bot token when prompted.**  
   (If you need help finding your bot token, watch this tutorial: [YouTube: How to get your Bot Token](https://www.youtube.com/watch?v=jvvc-uy_Myw))

5. **Invite the bot to your server and type `!start` in any channel.**

6. **Done! Your bot is up and running.**

---

## Demo Video

![Demo](https://user-images.githubusercontent.com/103531974/178593372-8186856c-07a8-45fb-b371-1ad24d9c498f.mp4)

---

## What you need:

- Python: [Download Python](https://www.python.org/downloads/)

---

## Extra customization:

You can change the command prefix by adding this input section to `main.py`:

```python
prefixinput = input("Enter your BOT's prefix: ")
PREFIX = prefixinput
