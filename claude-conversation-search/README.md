# Claude Conversation Search

A beautiful, privacy-focused web application for browsing and searching through your exported Claude conversations. Features a familiar chat-style interface with powerful search capabilities and Claude-inspired design.

![Claude Conversation Search Screenshot](screenshot.png)

## ✨ Features

### 🔍 **Powerful Search**
- **Full-text search** across all conversations and messages
- **Real-time filtering** as you type
- **Smart highlighting** of search terms in both sidebar and chat view
- **Auto-scroll to matches** - click a search result to jump directly to the first mention
- **Search-optimized browsing** - cmd+f starts in the chat content, not the sidebar

### 💬 **Chat-Style Interface**
- **Claude-inspired design** with warm color palette matching the official Claude interface
- **Proper message formatting** with markdown rendering (bold, code blocks, lists, etc.)
- **Smart timestamps** showing "Today", "Yesterday", or full dates
- **Right-aligned user messages** for familiar chat app experience
- **Responsive layout** that works on desktop and mobile

### 📁 **Smart Organization**
- **Dual sorting options**: Sort by "Last Modified" or "Created Date"
- **Rich conversation previews** with creation and modification dates
- **Match counters** showing number of search results per conversation
- **Easy navigation** between conversations

### 🔒 **Privacy First**
- **100% local processing** - your conversations never leave your computer
- **No data uploads** - everything runs in your browser
- **No tracking or analytics** - completely private and secure

## 🚀 Quick Start

### 1. Export Your Claude Data
1. Go to [Claude Settings → Data Privacy Controls](https://claude.ai/settings/data-privacy-controls)
2. Click **"Export data"** in the "Data controls" section
3. Confirm by clicking **"Export data"** again
4. Check your email for the download link (may take a few minutes)
5. Download and **unzip** the file

### 2. Load Your Conversations
1. Download or clone this repository
2. Open `index.html` in your web browser
3. Click **"Choose File"** and select `conversations.json` from your unzipped export
4. Start browsing and searching your conversations!

## 📖 How to Use

### **Search**
- Type in the search box to find conversations containing specific terms
- Search results show contextual snippets around your search terms
- Click any conversation to jump directly to the first match

### **Browse**
- Toggle between "Last Modified" and "Created" sorting
- Click any conversation to read it in the chat interface
- Use your browser's find function (cmd+f / ctrl+f) to search within conversations

### **Navigation**
- **Clear search**: Click the × button in the search box
- **Help**: Click "📖 How to use this" for detailed instructions
- **Auto-scroll**: Search results automatically scroll to the first match

## 🛠 Technical Details

- **Pure HTML/CSS/JavaScript** - no dependencies or build process required
- **Markdown rendering** via marked.js for proper formatting
- **Cross-platform compatibility** - works on Windows, Mac, Linux, and mobile
- **Modern browser support** - works in Chrome, Firefox, Safari, Edge

## 🎨 Design Philosophy

This tool aims to recreate the familiar Claude conversation experience while adding powerful search and organization features. The interface uses Claude's warm color palette and thoughtful design patterns to feel like a natural extension of the Claude experience.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.

### Development
1. Clone the repository
2. Open `index.html` in your browser
3. Make changes and test locally
4. Submit a pull request

## 📄 License

MIT License - feel free to use, modify, and distribute.

## 🙏 Credits

- **Code**: [@jbenton](https://github.com/jbenton) and Claude Sonnet 4
- **Markdown rendering**: [marked.js](https://marked.js.org/)
- **Design inspiration**: [Anthropic's Claude](https://claude.ai)

## 📞 Support

- **Issues**: Please report bugs or feature requests via [GitHub Issues](../../issues)
- **Discussions**: Share feedback or ask questions in [GitHub Discussions](../../discussions)

---

**Privacy Note**: This tool processes your Claude conversations entirely within your browser. No data is sent to external servers, ensuring your conversations remain completely private.