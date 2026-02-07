# X Query Search 🚀

Advanced X.com search query builder and manager. This Chrome extension helps you find high-quality content on X.com using powerful search templates and a custom query builder.

![Extension Preview](public/icons/icon128.png)

## Features

- **🔍 Search Templates**: Predefined search patterns for different regions (Chinese, English, Japanese, etc.) and topics.
- **🛠️ Custom Query Builder**: Easily build complex queries using keywords, languages, time ranges, and minimum like counts.
- **⚡ Advanced Filters**: Toggle filters for media types (images/videos) and exclusions (retweets, replies, links).
- **🔖 Favorites Manager**: Save your frequently used search queries and trigger them with a single click.
- **🔗 Deep X Integration**: Navigates directly to the live search results on X.com.
- **💻 Premium Design**: Built with a sleek, Twitter/X-native aesthetic.

## Tech Stack

- **Framework**: React 18
- **Build Tool**: Vite + @crxjs/vite-plugin
- **Styling**: Tailwind CSS
- **State Management**: Zustand (with chrome.storage persistence)
- **Language**: TypeScript
- **Testing**: Vitest + React Testing Library

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/jarodise/XQuery.git
   cd XQuery
   ```

2. **Install dependencies**:
   ```bash
   pnpm install
   ```

3. **Build the extension**:
   ```bash
   pnpm build
   ```

4. **Load in Chrome**:
   - Open Chrome and go to `chrome://extensions`.
   - Enable **Developer mode**.
   - Click **Load unpacked** and select the `dist` folder in this repository.

## Usage

1. Open [x.com](https://x.com).
2. Click the extension icon in your Chrome toolbar to open the search sidebar.
3. Switch between **Templates**, **Custom**, and **Favorites** tabs to manage your searches.

## Development

- **Development server**: `pnpm dev`
- **Run tests**: `pnpm test`
- **Type check**: `npx tsc`

## License

MIT
