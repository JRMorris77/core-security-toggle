# Core Security Toggle

*Enhance WordPress security by toggling core features like XML-RPC, REST API, Heartbeat, Emojis, Embeds, and more.*

![Core Security Toggle Screenshot](<img src="blob:chrome-untrusted://media-app/d9d44ab5-e6cc-41af-8909-5148f8ab7fb6" alt="Screenshot 2024-09-24 12.12.23 PM.png"/>![image](https://github.com/user-attachments/assets/8cd96afa-8ff1-49d5-8093-1e7d04eaaab3)
)

## Table of Contents

- [Core Security Toggle](#core-security-toggle)
  - [Description](#description)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Frequently Asked Questions](#frequently-asked-questions)
  - [Changelog](#changelog)
  - [Screenshots](#screenshots)
  - [Credits](#credits)
  - [License](#license)

## Description

**Core Security Toggle** is a powerful WordPress plugin designed to enhance your website's security and performance. It provides an easy-to-use interface for enabling or disabling various WordPress core features that are commonly targeted by attackers or can be optimized for better performance. By controlling these features, you can reduce potential security vulnerabilities and streamline your site’s functionality.

### Key Benefits

- **Enhanced Security:** Disable features that are frequently exploited by attackers.
- **Improved Performance:** Reduce unnecessary scripts and server load.
- **User-Friendly Interface:** Easily toggle features on and off without touching code.
- **Immediate Effect:** Changes take effect instantly, allowing you to manage your site's security in real-time.

## Features

The plugin offers toggles for the following WordPress core features:

1. **Disable XML-RPC**
   - Prevents brute force attacks and unauthorized access via the XML-RPC protocol.

2. **Disable REST API**
   - Restricts unauthorized access to your site's data endpoints.

3. **Disable Heartbeat on Front-end**
   - Reduces server load by stopping the Heartbeat API from running on the front-end.

4. **Prevent Author Enumeration**
   - Blocks attackers from identifying usernames through author archive pages.

5. **Disable Emojis**
   - Removes Emoji support to decrease page load times and eliminate unnecessary scripts.

6. **Disable Embeds**
   - Prevents embedding of external content, enhancing security against malicious content.

7. **Disable RSS Feeds**
   - Stops RSS feeds if they are not needed, preventing unauthorized content scraping.

8. **Disable Self-Pingbacks**
   - Prevents WordPress from sending pingbacks to itself, reducing potential attack vectors.

9. **Disable File Editing in Admin**
   - Stops administrators from editing plugin and theme files via the dashboard.

10. **Remove WordPress Generator Meta Tag**
    - Hides your WordPress version to prevent targeted attacks based on known vulnerabilities.

11. **Disable Post Revisions**
    - Limits or disables post revisions to save database space and reduce information leakage.

12. **Disable Automatic Updates**
    - Prevents WordPress from automatically updating core, plugins, and themes.

13. **Disable Gutenberg Block Patterns**
    - Removes default Gutenberg block patterns to streamline content creation.

14. **Remove Query Strings from Static Resources**
    - Enhances caching and security by removing query strings from static resource URLs.

15. **Disable Script Concatenation**
    - Helps in debugging and reduces server load by disabling the combining of scripts.

16. **Disable REST API Links in Headers**
    - Removes REST API links from site headers to obscure the presence of the REST API.

17. **Disable WordPress Version Display**
    - Removes WordPress version information from various parts of the site.

18. **Disable XML-RPC Methods**
    - Unsets specific XML-RPC methods to further secure the protocol.

19. **Disable OEmbed**
    - Prevents oEmbed auto-discovery by removing relevant headers.

20. **Disable Embarrassing REST API Endpoints**
    - Disables specific REST API endpoints that may expose sensitive information.

## Installation

### 1. Upload the Plugin Files

1. Download the `core-security-toggle.zip` file.
2. Log in to your WordPress admin dashboard.
3. Navigate to **Plugins > Add New**.
4. Click on the **Upload Plugin** button at the top.
5. Select the `core-security-toggle.zip` file you downloaded.
6. Click **Install Now** and then **Activate** the plugin.

### 2. Activate the Plugin

Once installed, activate the plugin to start using its features. You will find a new menu item labeled **Security Toggle** in your WordPress admin sidebar.

## Usage

1. **Access the Plugin Settings:**
   - Navigate to **Security Toggle** in the WordPress admin dashboard.

2. **Toggle Features:**
   - You will see a list of security and performance features with toggle switches.
   - Click on the switch to enable or disable a specific feature.

3. **Immediate Effect:**
   - Changes are applied instantly. There is no need to save or refresh the page.

### Example

To disable XML-RPC:

1. Go to **Security Toggle**.
2. Locate the **Disable XML-RPC** toggle.
3. Click the switch to turn it **ON**.
4. The XML-RPC feature is now disabled, enhancing your site's security against specific attack vectors.

## Frequently Asked Questions

### 1. **Will disabling these features break my website?**

Disabling certain features may affect functionalities that rely on them. For example, disabling the REST API can impact REST-based plugins or themes. It’s recommended to understand the purpose of each feature before toggling it.

### 2. **Can I selectively enable features for specific user roles?**

Currently, the plugin controls features globally across the site. Future updates may include more granular control based on user roles.

### 3. **Is this plugin compatible with all themes and plugins?**

The plugin is designed to work seamlessly with most themes and plugins. However, some functionalities might conflict with plugins that rely on the features being toggled. Always test changes in a staging environment first.

### 4. **Does the plugin affect site performance?**

Yes, by disabling unnecessary features and scripts, the plugin can help improve site performance and reduce server load.

### 5. **How does the plugin enhance security?**

By disabling features that are commonly exploited by attackers, the plugin reduces potential vulnerabilities, making your site more secure.

## Changelog

### 2.0

- **Initial Release**
  - Added 20 security and performance toggles.
  - User-friendly admin interface with native WordPress toggle switches.
  - AJAX-powered toggle functionality for real-time updates.
  - Comprehensive documentation included.

## Screenshots

1. **Admin Interface**
   - Overview of the Security Toggle settings page with all available toggles.

   ![Admin Interface](https://github.com/user-attachments/assets/6f0a7bde-3655-4c5f-84a0-02dc286637e2)
)
)

2. **Toggle Switches**
   - Demonstration of enabling and disabling a feature using the toggle switches.

   ![Toggle Switches](<img src="blob:chrome-untrusted://media-app/d9d44ab5-e6cc-41af-8909-5148f8ab7fb6" alt="Screenshot 2024-09-24 12.12.23 PM.png"/>![image](https://github.com/user-attachments/assets/117197d1-319b-4d59-b5c5-8fdf7ed25aba)
)

## Credits

**Core Security Toggle** was developed by [James Morris](https://kissws.com). Special thanks to the WordPress community for their continuous support and contributions.

## License

This plugin is licensed under the [GNU General Public License v2.0](https://www.gnu.org/licenses/gpl-2.0.html) or later.

---
