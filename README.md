# 📋 ML Changelog Tracker

**Automated WordPress Plugin Changelog Monitoring & Notification System**

[![Version](https://img.shields.io/badge/version-2.1.4-blue.svg)](https://github.com/wplaunchify/ml-changelog-tracker)
[![WordPress](https://img.shields.io/badge/WordPress-5.0%2B-blue.svg)](https://wordpress.org)
[![License](https://img.shields.io/badge/license-GPL--2.0%2B-green.svg)](https://www.gnu.org/licenses/gpl-2.0.html)

## 🚀 What It Does

ML Changelog Tracker is a **"set it and forget it"** WordPress plugin that automatically:

- 🔍 **Discovers** all your installed plugins
- 📊 **Monitors** them for changelog updates
- 🔔 **Notifies** you when updates are available
- 🤖 **Integrates** with AI assistants for plugin recommendations
- 📋 **Displays** a beautiful public changelog page

## ✨ Key Features

### 🔄 Automated Monitoring
- **Zero Configuration**: Automatically scans installed plugins on activation
- **Daily Updates**: Checks for new plugin versions and changelog updates
- **Smart Notifications**: Admin notices and dashboard widgets for updates
- **WordPress.org Integration**: Seamless integration with official plugin repository

### 🤖 AI Assistant Integration
- **Ultra-Simple Setup**: Copy-paste instructions for any AI (ChatGPT, Claude, Gemini)
- **No Technical Skills**: Works without Node.js, JSON configs, or complex setup
- **Universal Compatibility**: Works with current and future AI assistants
- **Instant Access**: AI can immediately search your plugin database

### 🎨 Professional Frontend
- **Public Changelog Page**: Beautiful `/changelog-updates` endpoint
- **Advanced Search**: Filter by source, status, and plugin name
- **Responsive Design**: Works perfectly on all devices
- **Real-time Stats**: Live plugin counts and update notifications

### 🔧 Developer-Friendly
- **REST API**: Complete API for external integrations
- **Simple URL Search**: `/plugin-search/TERM` for quick lookups
- **MCP Compatible**: Traditional MCP server support included
- **Extensible**: Easy to customize and extend

## 📦 Installation

1. **Upload** the plugin files to `/wp-content/plugins/ml-changelog-tracker/`
2. **Activate** the plugin through WordPress admin
3. **Done!** The plugin automatically starts monitoring your plugins

## 🎯 Quick Start

### For WordPress Admins
1. Go to **Tools → ML Changelog Tracker**
2. Click **"📋 Get Copy-Paste Instructions"**
3. Copy the generated text
4. Paste into any AI chat (ChatGPT, Claude, etc.)
5. AI can now search your plugin database!

### For Developers
- **REST API**: `/wp-json/mlct/v1/`
- **Search API**: `/wp-json/mlct/v1/search?q=woocommerce`
- **Stats API**: `/wp-json/mlct/v1/stats`
- **Simple Search**: `/plugin-search/security`

## 🔗 Available Endpoints

| Endpoint | Purpose | Example |
|----------|---------|----------|
| `/changelog-updates` | Public plugin list | View all monitored plugins |
| `/plugin-search/TERM` | Simple search | `/plugin-search/woocommerce` |
| `/llm-setup` | AI instructions | Copy-paste setup for AI |
| `/wp-json/mlct/v1/search` | REST search | API integration |
| `/wp-json/mlct/v1/stats` | Statistics | Plugin counts and stats |

## 📊 Version History

### v2.1.4 (Current)
- Enhanced stability and performance
- Improved AI integration instructions
- Better error handling and logging

### v2.1.3
- **Ultra-Simple Copy-Paste MCP**: Revolutionary zero-setup AI integration
- **Universal AI Compatibility**: Works with ChatGPT, Claude, Gemini, any AI
- **Admin Interface Overhaul**: Beautiful new design with clear instructions

### v2.1.2
- Universal AI API implementation
- Enhanced REST endpoints
- Improved documentation

*Complete version history with detailed changelogs available in `/old-versions/` directory.*

## 🛠️ Technical Requirements

- **WordPress**: 5.0 or higher
- **PHP**: 7.4 or higher
- **MySQL**: 5.6 or higher
- **Permissions**: Plugin installation and activation rights

## 🤝 AI Assistant Integration

### Supported AI Platforms
- ✅ ChatGPT (OpenAI)
- ✅ Claude (Anthropic)
- ✅ Gemini (Google)
- ✅ Perplexity
- ✅ Any AI chat interface
- ✅ Future AI platforms (universal compatibility)

### Setup Process
1. Visit your WordPress admin
2. Go to **Tools → ML Changelog Tracker**
3. Click **"📋 Get Copy-Paste Instructions"**
4. Copy the entire text block
5. Paste into any AI chat
6. AI can now search your plugin database!

## 📈 Use Cases

### For Agencies & Freelancers
- **Client Recommendations**: AI-powered plugin suggestions
- **Update Monitoring**: Stay informed about plugin changes
- **Professional Service**: Offer advanced plugin consultation

### For Site Owners
- **Automated Monitoring**: Never miss important plugin updates
- **Smart Notifications**: Get alerts for critical changes
- **Easy Management**: Beautiful interface for plugin oversight

### For Developers
- **API Integration**: Build custom tools and integrations
- **Monitoring System**: Track plugin ecosystem changes
- **Research Tool**: Analyze plugin trends and updates

## 🔒 Security & Privacy

- **No External Data**: All data stored locally in your WordPress database
- **Secure API**: Proper authentication and authorization
- **Privacy Focused**: No tracking or external data sharing
- **WordPress Standards**: Follows all WordPress security best practices

## 🐛 Troubleshooting

### Common Issues

**Plugin not scanning automatically?**
- Click "Force Initialize" in the admin interface
- Check WordPress cron is working properly

**AI integration not working?**
- Ensure you copied the complete instructions
- Try regenerating the instructions
- Check your site's URL accessibility

**Missing plugins in database?**
- Use "Scan Installed Plugins" button
- Check plugin is properly installed and recognized by WordPress

## 📞 Support

- **Documentation**: Complete guides in `/old-versions/README.md`
- **Version History**: Detailed changelogs for all versions
- **GitHub Issues**: Report bugs and request features
- **WordPress Forums**: Community support available

## 🤝 Contributing

We welcome contributions! Please:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📄 License

This plugin is licensed under the GPL v2 or later.

```
This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.
```

## 🙏 Acknowledgments

- WordPress community for the amazing plugin ecosystem
- AI assistant platforms for enabling new integration possibilities
- All contributors and users who help improve this plugin

---

**Made with ❤️ for the WordPress community**

*Automate your plugin monitoring and never miss an important update again!*