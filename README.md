# Invisibility-Cloak-using-OpenCV-Python
👇  🧥 Invisibility Cloak using OpenCV &amp; Python  This project implements the famous “Invisibility Cloak” effect (inspired by Harry Potter 🪄) using Python, OpenCV, and NumPy. The idea is to make a red-colored cloth (or object) disappear and replace it with the pre-captured background, creating an invisibility illusion in real-time.
🚀 Features

Real-time webcam feed processing 🎥

Detects red-colored cloak using HSV color masking 🎨

Removes cloak region and replaces it with background image

Morphological transformations to clean noisy mask ✨

Easy-to-run Python script (no extra dependencies except OpenCV & NumPy)

🛠️ Tech Stack

Python 3.x

OpenCV (cv2)

NumPy

📌 How It Works

1. Capture a clean background image without the person.

2. Start the webcam feed and convert frames from BGR → HSV color space.

3. Detect the red cloak region using color thresholds.

4. Replace cloak area with the saved background.

5. Display the final output where the cloak looks invisible! 👻
