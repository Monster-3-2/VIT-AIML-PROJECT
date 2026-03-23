# VIT-AIML-PROJECT
NLP based AIML PROJECT to diagnose automobile issues

## 🔧 Car Doctor: Your AI Car Mechanic
Hey there! Ever had a weird noise coming from your car and didn't know if you should pull over or keep driving? I wrote this little Python script called **cardoc** to help with exactly that. 

It’s a simple, text-based chatbot that acts like a "first-aid kit" for car problems. You tell it what’s wrong in plain English, and it gives you a quick diagnosis, a danger rating, and some handy tips on what to do next.

---

### 🚀 What can it do?
The bot is trained to recognize a bunch of common car headaches, including:
* **Starting Issues:** Dead batteries, clicking sounds, or keys that won't turn.
* **Overheating:** What to do when you see steam or the temp gauge spikes.
* **Brakes & Tyres:** Squeaky pads, spongy pedals, or flat tires.
* **Fluids:** Low oil warnings or transmission/gear shifting grinds.
* **Dash Lights:** Explaining that "Check Engine" light or the battery icon.
* **Efficiency:** Helping you figure out why your fuel mileage has suddenly tanked.

---

### 🛠️ How it works
The logic is pretty straightforward:
1.  **Listen:** You type in a sentence (e.g., *"Help, my engine is smoking!"*).
2.  **Match:** The bot scans your text for "clue words" like *smoke*, *hot*, or *overheating*.
3.  **Diagnose:** It finds the problem with the most matches and tells you how urgent it is.
4.  **Advise:** It prints out a list of "Quick Tips" to help you stay safe.

---

### 🚥 The "Danger" Meter
To make things easy to read, the bot uses a color-coded system:
* 🟢 **Low:** Not urgent. You can keep driving, but check it out later.
* 🟡 **Medium:** Fix it soon. Don't ignore it, or it might get expensive.
* 🔴 **High:** **STOP.** Pull over. Driving further might be dangerous or destroy your engine.

---

### 💻 How to run it
Since this is a simple Python script, you don't need to install anything fancy.
1.  Make sure you have **Python** installed on your computer.
2.  Save the code as `cardoc.py`.
3.  Open your terminal or command prompt.
4.  Run it by typing:
    ```bash
    python cardoc.py
    ```
5.  Start chatting! Type `bye` when you're done.

---

### ⚠️ A friendly heads-up
I’m just a script! While these tips are based on common mechanical knowledge, I can’t actually see your car. Always trust a real-life mechanic over a piece of code if your gut (or your car) is telling you something is wrong.

**Drive safe!** 🚗💨

---
