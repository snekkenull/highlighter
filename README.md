# Highlighter Browser Extension

**Intelligently highlight important webpage content using OpenAI GPT.**

This browser extension automatically identifies and highlights key information on web pages using the power of OpenAI Compatible APIs.

## Preview
[Tweet](https://x.com/AnnioDance/status/1892475171182649772)

## Key Features

- **Intelligent Content Highlighting:** Automatically identifies and highlights important content on web pages.
- **OpenAI API BASE:** Using the OpenAI API format with any providers for intelligent content analysis.
- **Website Whitelist:** Manage which websites the extension operates on.
- **Customizable Highlighting:**  Personalize highlight colors and animation effects.
- **Local Cache:** Improves performance by locally caching highlighting results.
- **Real-time & Animated:** Highlights content in real-time with engaging animations.

## Installation

- git clone or download this repo to unextract the `dist` folder to local disk.

- Chrome Browser, Open `chrome://extensions/`, Choose `Load Unpacked` and select the `dist` folder.

## Configuration

1. After installing the extension, click the extension icon to access the settings page.
2. Enter your provider's API Key.
3. Configure the following options:
   - API Base URL (Default: https://api.openai.com)
   - GPT Model (Default: gpt-3.5-turbo)
   - Highlight Color
   - Animation Speed
   - Website Whitelist

## Usage

1. Configure your API key and other settings in the extension options.
2. Add the websites you want to automatically highlight to the whitelist.
3. Visit whitelisted websites, and the extension will automatically analyze and highlight content.
4. You can interact with the extension by clicking the icon to:
   - Toggle highlighting on/off.
   - Clear all highlights from the current page.
   - View the highlighting status.

## Technical Features

- **Efficient Page Content Monitoring:** Implemented using Intersection Observer for efficient page content tracking.
- **Accurate Text Location:** Employs a fuzzy text matching algorithm to improve text positioning accuracy.
- **Performance Optimization:** Utilizes local storage to cache highlighting results for improved performance.
- **Optimized Rendering:** Supports batch DOM operations for optimized rendering performance.
- **Robust API Handling:** Built-in request rate limiting and retry mechanisms for reliable API interactions.

## Privacy Policy

- The extension only runs on whitelisted websites.
- Content analysis is solely performed using the OpenAI API.
- Highlight data is stored only in your local browser storage.


## Development Tools
Mode with [TraeAI](https://trae.ai)
