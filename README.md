# Simple Telegram Bot

This is a simple Telegram bot built with Node.js. It allows you to send messages to a specified phone number. Follow the instructions below to set up and run the bot on your system.

## Requirements

- Termux installed on your Android device.
- Node.js and Git installed on your system.

## Installation

### Step 1: Install Dependencies

1. Update and upgrade your system packages to ensure everything is up to date:
    ```
    pkg update -y && pkg upgrade -y
    ```

2. Install Node.js (JavaScript runtime) and Git (version control system):
    ```
    pkg install -y nodejs git
    ```

3. Clone the GitHub repository into your local machine:
    ```
    git clone https://github.com/coderxsa/nebula.git
    ```

4. Change into the directory of the cloned repository:
    ```
    cd nebula
    ```

5. Install the necessary dependencies for the project defined in `package.json`:
    ```
    npm install
    ```
    
6. Edit Bot.js:
    ```
    nano bot.js
    ```
    
7. Run the Node.js application, passing a specific phone number you want to use and get the login code:
    ```
    node index.js
    ```

### Step 2: Relink Bot (If Necessary)

- If Termux disconnects, you can simply relink the bot by running the following commands:
    ```
    cd nebula
    node index.js
    ```

- If you removed the linked device, you need to follow **Step 1** again and reinstall the bot. To clear data on Termux:
    - Go to Android settings > Apps > Termux > Clear Data

- Reinstall the bot:
    ```
    git clone https://github.com/coderxsa/nebula.git
    cd nebula
    npm install
    node index.js
    ```

