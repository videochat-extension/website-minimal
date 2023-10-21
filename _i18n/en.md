# Videochat Extension
**Videochat Extension (Chatruletka Extension)** is an **[independent](https://github.com/qrlk/videochat-extension#policy-of-neutrality-acceptable-use-and-functional-limitations){:target="_blank"}** browser extension that expands the functionality in the following video chats:
* **Chatruletka**, **Ome.tv**, **Minichat**, **Chatrulez**.
* **Omegle (work-in-progress)**.
* **Coomeet Free (bot recognition only)**.  

<div>
<img src="{{site.url}}/assets/img/example.png">
</div>
<br>
**With this extension installed, you can find out where your interlocutors are from, filter them by gender, search for a specific city, enable dark mode, and much more!**

### Install:
{% include_relative _includes/stores.md %}

---

### Key Features

* ✓ IP Locator — determines the stranger's approximate location
* ✓ World map
* ✓ Ban unwanted countries
* ✓ Search for specific locations
* ✓ Gender Filter
* ✓ Dark Mode
* ✓ Automation
* ✓ Blacklist
* ✓ Stats
* ✓ Shortcuts/hotkeys
* ✓ Streamer Mode
* ✓ Simple Mode — essential features only
* ✓ Customizable — configure features as you like
* ✓ Open source — freedom and transparency
* ✓ Indie project — community-supported development
* ✓ Private and secure — we don't collect/sell your data
	
---

### Links

* **[Patreon](https://patreon.com/videochat_extension){:target="_blank"}**
* **[Discord](https://discord.gg/7DYWu5RF7Y){:target="_blank"}**
* **[GitHub](https://github.com/videochat-extension){:target="_blank"}**
* **[Roadmap](https://videochat-extension.canny.io){:target="_blank"}**
* **[Neutrality policy](https://github.com/qrlk/videochat-extension#policy-of-neutrality-acceptable-use-and-functional-limitations){:target="_blank"}**

---

### Simple Mode

* a minimalistic mode that includes only essential features:
  * ome.tv, chatruletka, minichat, chatrulez: displaying IP geolocation data in the chat area.
  * omegle: IP Locator & Dark Mode.
  * coomeet free: displaying the stranger's country, bot recognition and volume control.

---

### Complete list of features

* **geolocation (IP Locator)**
  * determines the stranger's IP address used for WebRTC connection.
  * uses the IP geolocation service to get the information about that IP address.
  * displays the stranger's approximate location (city/region/country), ISP, and whether they use a cellular network.
  * integration with the 'map' module: IP geolocation data is displayed on the world map.
  * integration with the 'streamer mode' module: IP geolocation data can be displayed in the OBS's text source.
  * determines if a stranger is using a proxy/tor/vpn connection to hide their real IP.
  * option to auto-skip predefined countries/regions/cities.
  * option to search for specific countries/regions/cities.
  * iknowwhatyoudownload integration that allows you to open a list of torrents possibly downloaded by a stranger.
  * option to select the language of ip geolocation data from English, Deutsch (German), Español (Spanish), Português (Portuguese), Français (French), 日本語 (Japanese), 中国 (Chinese), and Русский (Russian).
  * option to select which ip geolocation services will be used.

* **map**
  * IP geolocation data is displayed on a world map embedded in the UI.
  * displays the approximate area where the stranger you are talking to may be located.
  * displays a marker popup with information about the stranger's approximate location.
  * different options to customize map's behavior.

* **faceapi (gender recognition)**
  * AI-powered client-side gender recognition.
  * option to auto-skip strangers if their gender does not meet your expectations.
  * integration with the 'blacklist' module: option to automatically add strangers that were skipped by facepi to the blacklist.
  * integration with the 'stats' module: counts the statistics of how many men and women you met and how many were auto-skipped.

* **interface**
  * dark mode (dark theme).
  * option to hide your own camera to make conversation more natural.
  * option to hide/show logo, banner, header, and watermark (not on all platforms).
  * option to cancel camera reflection (not on all platforms).
  * option to disable cropping stranger's video (not on all platforms).

* **automation**
  * option to auto-skip strangers that take more than 4 seconds to connect
  * option to auto-skip if you were looking for someone from X country but the video chat found you someone from Y country (not on all platforms)
  * option to automatically close 'make yourself visible' (not on all platforms)

* **blacklist**
  * you can add a stranger's IP address to the blacklist so that the extension can automatically skip them.
  * integration with the 'hotkeys' module: hotkey to add stranger to the blacklist and skip.
  * option to avoid adding cellular IPs to the blacklist.
  * option to play a sound when the extension auto-skips a blacklisted IP.
  * option to clear the blacklist.

* **stats**
  * counts the number of people you've met.
  * counts how much time you've spent in conversations.
  * counts various statistics for other modules such as faceapi / blacklist.

* **controls**
  * improvised control panel that acts as the extension UI.
  * it consists of a header, a content block, and tabs that select what will be displayed in the content block.
  * list of tabs: 'IP', 'Map', 'Bans', 'Stats', 'Settings', 'Info'.
  * the 'Info' tab contains helpful information about the extension: useful links, credits, version history, etc.
  * the header contains the extension name/version, and blocks with buttons for the extension functionality.
  * use the header's buttons to take a screenshot of the cameras / open the camera in picture-in-picture mode.
  * provides control buttons for other modules such as 'streamer mode'.

* **hotkeys**
  * local hotkeys: use the keyboard arrows to skip/skip+blacklist/stop/report.
  * global hotkeys: browser-level shortcuts to skip/skip+blacklist/stop.
  * global hotkeys: browser-level shortcuts to make remote/local screenshots.
  * global hotkeys: browser-level shortcut to switch between the last non-chat tab and the chat tab.
  * provides hotkeys functionality for other modules such as 'streamer mode'.

* **settings**
  * this module is responsible for the functionality of the 'Settings' tab in the UI.
  * all settings are grouped by their module.
  * if you hover over a setting, detailed information about what this setting does will be displayed.

* **streamer mode**
  * a section of specialized features that help streamers broadcast video chats on YouTube and other services.
  * OBS integration - allows you to display IP geolocation data in the text source and control the visibility of the image, which covers the video while you look for a suitable interlocutor.
  * blur & cover - allows you to cover the interlocutor's camera with a blur/picture/gif and look at it through picture-in-picture mode to decide if the interlocutor is suitable to show to your audience.
  * integration with the 'hotkeys' module: local shortcuts to toggle mute/blur/cover.
  * integration with the 'controls' module: header buttons to toggle mute/blur/cover.

**Not all extension features are available on all platforms.**

---

### Supported chats

* **Chatruletka (full support):**
{% include_relative _includes/platform_chatruletka.md %}

* **Ome.tv (full support):**
{% include_relative _includes/platform_ometv.md %}

* **Minichat (full support):**
{% include_relative _includes/platform_minichat.md %}

* **Chatrulez (full support):**
{% include_relative _includes/platform_chatrulez.md %}

* **Omegle (work-in-progress):**
{% include_relative _includes/platform_omegle.md %}

* **Coomeet Free (bot recognition & interface tweaks):**
{% include_relative _includes/platform_freecm.md %}

---

### Privacy

* **Your privacy and security are very important to us**
  * We do not log your geolocation requests.
  * We do not disclose to your interlocutor that you are using the extension.
* **Analytics**
  * We do not analyze your activity or behavior.
  * For analytics we use in-house analytics of extension stores, which gives us all information we need (number of installations, deletions and active users in different countries).
* **Error Collection**
  * The extension enables automatic collection of anonymised error information by default, this feature can be disabled in the settings or in the window that is shown after installation.
* **Transparency**
  * The source code of the project is publicly available on the **[GitHub](https://github.com/videochat-extension){:target="_blank"}**.