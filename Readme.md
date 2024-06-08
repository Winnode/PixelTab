# PixelTab

PixelTab is a script for a bot designed for the PixelVerse Project. The bot interacts with the PixelVerse Project API to retrieve user data, mining progress, and claim mining rewards.

## Features
- Fetch user data including username, Telegram ID, and clicks count.
- Retrieve mining progress data such as max available and currently available.
- Claim mining rewards and update the clicks count accordingly.

## Dependencies
- Axios: For making HTTP requests.
- fs: For reading the accounts.json file.

## Setup
1. Clone this repository to your local machine:
    ```
    git clone https://github.com/Winnode/PixelTab.git
    ```
2. Install dependencies using `npm install`.
3. Make sure you have an `accounts.json` file in the same directory as the script. This file should contain an array of account objects with the following structure:
    ```json
    [
      {
        "initData": "YOUR_INIT_DATA",
        "secret": "YOUR_SECRET",
        "tgId": "YOUR_TELEGRAM_ID",
        "username": "YOUR_USERNAME"
      },
      {
        ...
      }
    ]
    ```
   Replace `YOUR_INIT_DATA`, `YOUR_SECRET`, `YOUR_TELEGRAM_ID`, and `YOUR_USERNAME` with the appropriate values for your accounts.
4. Run the script using `node script.js`.

## Example

![Example](https://github.com/Winnode/PixelTab/blob/main/ex.png)

## Notes
- Make sure your accounts have the necessary permissions to interact with the PixelVerse Project API.
- The script will continuously fetch user data and claim mining rewards for each account in the `accounts.json` file.

## Support
For support or inquiries, you can reach out to the creator of this bot:
- Telegram: [t.me/Winnodexx](https://t.me/Winnodexx)
- Github: [@Winnode](https://github.com/Winnode)
- Ethereum Address: 0xde260429ef7680c7a43e855b5fcf619948f34e2a
