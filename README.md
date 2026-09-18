# ZQ Suno Farmer

> **Made by ZappyQ**

**ZQ Suno Farmer** is a Python-based console automation tool designed to help you passively earn credits on [Suno](https://suno.com) through their "Listen and Rank" system.

Instead of manually listening to clips and voting for hours, this script uses Selenium WebDriver to automate the entire process: playing the tracks, waiting for the exact required duration, casting a random vote, and collecting your credits.

## Features

* **Fully Automated Farming:** Automatically plays Clip A and Clip B, waits for the required listening time, randomly selects a vote (A, B, or Neither), and submits it.

* **Smart Detection:** Doesn't just use blind timers. The script actively looks for Suno's internal UI checkmarks (SVG icons) to know exactly when a clip has been listened to long enough.

* **Persistent Sessions:** Creates a local `chrome_profile` folder so you only have to log into your Suno account once. Returning sessions will automatically bypass the login screen.

* **Cross-Platform Support:** Automatically detects your Google Chrome installation whether you are on Windows, macOS, or Linux.

## Prerequisites

Before running the program, ensure you have the following installed on your system:

**Google Chrome** installed on your computer.

## Installation

**Clone or Download the Repository:** Download the `ZQ Suno Farmer.exe` file to an empty folder on your computer.

*(Note: If Windows SmartScreen shows a warning, click **More info** -> **Run anyway**).*

## Usage

1. Run the program

2. **First Run (Login):**

   * When you select `1. Start` from the menu, the script will open a new Google Chrome window.

   * You will be prompted in the console to manually log into your Suno account in that browser window.

   * Once you are successfully logged in, return to the console and press **Enter**.

3. **Farming:**

   * The script will automatically navigate to the `listen-and-rank` page, click "Start", and begin the loop.

   * You can leave it running in the background. It will automatically stop and notify you when there are no more tasks available for the day.

## ⚠️ Disclaimer & Warning

**Use this tool at your own risk.**
This is an unofficial automation script. Using bots or automated tools to farm credits may violate Suno's Terms of Service. The creator (ZappyQ) is not responsible if your Suno account is suspended, banned, or penalized for using this software. This project is for educational purposes and proof-of-concept only.
