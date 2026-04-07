# MyBroadband Super Filter (Beta)

A powerful browser extension for Google Chrome and Brave designed to give you complete control over your MyBroadband forum experience. This tool allows you to filter out unwanted content, mute specific users, and block annoying social media embeds without breaking the forum's layout.

## Features

* **ID-Based Blocking:** Hide specific threads and entire forum sections reliably using their unique numerical IDs.
* **User Muting & Blocking:** Choose how you handle specific users. You can completely block their threads and posts from appearing, or use the "Mute" feature to hide their message content while keeping their threads visible in the forum list.
* **Social Media Embed Removal:** Automatically removes X (Twitter) and Facebook embeds. The extension destroys the underlying HTML to prevent dynamic scripts from breaking the layout, replacing the content with a clean, single placeholder.
* **Legacy Import/Export:** Easily export your blocklists to save your settings. The import function is fully backwards compatible and will automatically map data from older versions.
* **Master Toggle:** Instantly turn all filtering rules on or off with a single sliding switch.
* **Visual Feedback:** A badge counter on the extension icon shows exactly how many items were blocked or muted on the current page.

## Installation Instructions

Since this is a beta version, you will need to install it manually using Chrome or Brave's Developer Mode.

1. Download the extension package: `mybb-super-filter-dev.zip`.
2. Extract the contents of the zip file to a dedicated folder on your computer.
3. Open your browser and navigate to the extensions page:
   * **Chrome:** Type `chrome://extensions/` in the address bar and press Enter.
   * **Brave:** Type `brave://extensions/` in the address bar and press Enter.
4. In the top right corner of the extensions page, toggle the **Developer mode** switch to the "On" position.
5. Click the **Load unpacked** button that appears in the top left.
6. Select the folder where you extracted the zip file contents.
7. The MyBB Super Filter extension will now appear in your list of installed extensions. It is highly recommended to "pin" the extension to your toolbar for easy access.

## How to Use

Click the extension icon in your browser toolbar to open the control panel.

### Advanced Settings
Click the gear icon in the top right corner to access the Advanced Settings menu. Here you can toggle the "Replace X/Facebook Embeds" feature and the "Mute User Posts" feature.

### Blocking Users
Enter the exact username of the person you wish to block into the Username field and click "Block User".

### Blocking Threads and Sections
To block a thread or section, you must use its unique ID number found in the MyBroadband URL.
* **Thread ID:** In the URL `mybroadband.co.za/forum/threads/example-thread-name.123456/`, the ID is **123456**.
* **Section ID:** In the URL `mybroadband.co.za/forum/forums/example-section.789/`, the ID is **789**.

Enter the ID into the corresponding field. You can also add an optional description (e.g., "Crypto Thread" or "Weather") to help you remember why you blocked it.

### Managing Data
Use the "Export Data" button at the bottom of the panel to save your current lists as a JSON file. Use the "Import Data" button to restore your settings from a previous backup.
