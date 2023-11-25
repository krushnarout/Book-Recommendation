# Random Password Generator Chrome Extension

This Chrome extension generates random passwords to enhance the security of your online accounts. The extension provides a simple interface and allows users to customize password length and include various character types.

## Installation

1. Clone this repository or download the ZIP file.
   ```bash
   git clone https://github.com/your-username/random-password-generator-chrome-extension.git
   ```

2. Open Chrome and navigate to `chrome://extensions/`.

3. Enable "Developer mode" in the top right corner.

4. Click on "Load unpacked" and select the root folder of the cloned/downloaded repository.

5. The extension should now be installed and visible in the Chrome toolbar.

## Usage

Click on the extension icon in the Chrome toolbar to open the popup interface. Customize the password length and character types, then click the "Generate Password" button. The generated password will be copied to your clipboard automatically.

## Features

- **Random Password Generation:** Generates strong and secure passwords.
- **Customization:** Allows users to specify password length and include/exclude character types (uppercase letters, lowercase letters, numbers, special characters).
- **Clipboard Integration:** Copies the generated password to the clipboard for easy use.

## Folder Structure

```
random-password-generator-chrome-extension/
│
├── icons/
│   ├── icon.png
│   └── icon48.png
├── manifest.json
├── popup.html
└── popup.js
```

- **icons:** Contains the extension icons in different sizes.
- **manifest.json:** Describes the extension and its properties.
- **popup.html:** HTML file for the extension's popup interface.
- **popup.js:** JavaScript file containing the logic for password generation and interaction with the popup interface.

## Contributing

Contributions are welcome! If you have ideas for improvement or find any issues, please open an issue or submit a pull request.
