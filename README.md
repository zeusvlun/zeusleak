# ZeusLeak

ZeusLeak is a browser extension that automatically detects leaked secrets and credentials in code while browsing.

## Features

- Detects various types of leaked credentials (API keys, OAuth tokens, private keys, etc.).

- Supports major platforms like AWS, Google, GitHub, Slack, and more.

- Provides real-time alerts and notifications for detected leaks.

- Allows users to manage and export findings in CSV format.

- Offers customization options to enable/disable specific detection rules.

## Installation

Clone this repository:

'git clone https://github.com/zeusvuln/zeusleak.git'

Open your browser's extensions page:

Chrome: Navigate to chrome://extensions/

Firefox: Navigate to about:addons

Enable "Developer Mode" (if required by the browser).

Click on "Load Unpacked" and select the cloned zeusleak directory.

## Usage

Once installed, ZeusLeak runs automatically in the background.

If any leaked secrets are found, they will appear in the extension popup.

Users can export findings as a CSV file.

Adjust settings via the popup to enable or disable specific detections.

## Supported Patterns

ZeusLeak detects secrets such as:

AWS keys

Google API keys

GitHub OAuth tokens

Slack Webhooks

Stripe API keys

Telegram bot tokens

SSH/RSA private keys

And more...

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.

