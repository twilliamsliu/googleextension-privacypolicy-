# FakeSmith Test Data Generator Privacy Policy

Last Updated: November 25, 2025

This policy explains how the FakeSmith Chrome extension (hereinafter referred to as "this tool") handles and protects user data. By installing and using this tool, you agree to the following terms.

## 1. Product Scope

This tool covers the following features:
- Default data generators and custom data generators
- Data Exporter and Data Encoder (encryption/decryption converter)
- Quick Paste Notes and Sidepanel
- Popup / Options / Sidepanel UI and right-click menu functionality

## 2. Data Collection and Transmission

- **No personal data is collected, transmitted, or stored on remote servers**. All data is processed locally in the browser.
- Content entered by users in generators or quick paste notes is only stored in `chrome.storage.local` or browser memory.
- This tool does not require account login and does not collect cookies, analyze fingerprints, or track behavior.

## 3. Permission Usage

| Permission | Purpose | Notes |
| --- | --- | --- |
| `storage` | Store default/custom generator settings, quick paste notes, preferences, etc. | Only uses `chrome.storage.local` |
| `contextMenus` | Provide quick paste menu in web page input fields | No background data transmission |
| `sidePanel` | Display sidebar tools and sync with storage | Only active when user opens it |
| `scripting` (if required by Manifest) | Inject necessary scripts when needed | Limited to functional scripts only |

## 4. Third-Party Services

- This tool does not integrate any third-party tracking or analytics services.
- If users click reference links provided in settings (such as libphonenumber, MOE character table, Buy Me a Coffee), the browser will directly visit those external websites, and their privacy policies are the responsibility of those websites.

## 5. User Data Control

- All generators, history records, preferences, and quick paste notes can be cleared at once via Settings → Reset.
- Individual data can also be manually deleted (e.g., quick paste notes, generators, export records).
- Uninstalling the extension will remove all locally stored data.

## 6. Security Measures

- The codebase has undergone static analysis and manual security review to ensure data protection and prevent vulnerabilities.
- Important operations (such as leaving unsaved edits) provide prompts to prevent accidental data loss.
- This tool does not perform network transmission, reducing the risk of data leakage.

## 7. User Responsibility

- Generated or stored data is for testing purposes only. If it contains personal information or sensitive data, please comply with relevant laws and company regulations.
- If importing third-party data or scripts, please verify their security first.

## 8. Policy Updates

If features or authorization scope change in the future, this policy will be updated accordingly and announced in version release notes. We recommend checking the latest version periodically.

## 9. Contact Information

If you have any questions or suggestions regarding this policy, please contact us through:
- Threads: https://www.threads.com/@twilliamsliu
- Buy Me a Coffee: https://buymeacoffee.com/twilliamslp

Thank you for using FakeSmith. Your data security is our top priority.
