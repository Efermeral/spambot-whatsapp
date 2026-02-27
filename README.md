# spambot-whatsapp
This script imports PyAutoGUI and time to automate messaging. It prompts for a message and how many times to send it, then waits 5 seconds to allow focus on the target window. It loops, typing the message with pyautogui.write(msg) and pressing Enter with pyautogui.press("enter"), pausing 0.5 seconds between repeats.
