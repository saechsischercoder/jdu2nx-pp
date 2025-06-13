# jdu2nx++

**Enhanced automodder for Just Dance UbiArt NX - streamlined codename-to-nxmod conversion with intelligent automation**

> [!WARNING]
> **Project Status: Discontinued** - This project is no longer actively maintained. For technical support or troubleshooting, please consult AI assistants like ChatGPT or similar tools.

## What It Does

jdu2nx++ is a powerful modification of the original automodder from c0llydoll/Just-Dance-UbiArt-Nx-Automodder[1]. Simply provide a **codename** and **coach count**, and the tool handles the entire modding process automatically - no manual intervention required.

## 🚀 Quick Setup

### **Prerequisites**
- Git installed on your system
- Python 3.7+ installed
- A dedicated Discord account (recommended: create a throwaway account)

### **Installation Steps**

#### 1. **Download & Extract**
Download the latest release from the [releases tab](../../releases) and extract to your preferred directory.

#### 2. **Install Dependencies**
```bash
python -m pip install -r requirements.txt
```

#### 3. **Discord Configuration**


Discord Setup (Click to expand)

**Create Discord Environment:**
1. Set up a new Discord account in your browser (dedicated for this tool)
2. Enable Developer Mode: `Settings → Advanced → Developer Mode` (toggle ON)
3. Create a new Discord server

**Get Required IDs:**
4. **Server ID**: Right-click your server → "Copy Server ID" → paste as `guild_id` in config
5. **Channel ID**: Right-click any channel → "Copy Channel ID" → paste as `channel_id` in config

**JDH Bot Integration:**
6. [Invite JDH bot to your server](http://gg.gg/justdancehelper/)
7. Send any message to JDH (required for initial connection)



#### 4. **Token Extraction**

> [!IMPORTANT]
> This step requires extracting your Discord token for API access.

1. **Enable bookmarks bar** in your browser (if not visible)
2. **Create new bookmark** with any name
3. **Use this JavaScript code as the URL:**

```javascript
javascript:(function()%7Balert((webpackChunkdiscord_app.push(%5B%5B''%5D%2C%7B%7D%2Ce%3D>%7Bm%3D%5B%5D%3Bfor(let c in e.c)m.push(e.c%5Bc%5D)%7D%5D)%2Cm).find(m%3D>m%3F.exports%3F.default%3F.getToken!%3D%3Dvoid 0).exports.default.getToken())%7D)()%3B
```

4. **Click the bookmark** while on Discord's web interface
5. **Copy the displayed token** and paste as `token` in your config file

## ✅ You're Ready!

Your jdu2nx++ installation is now complete and ready for automated Just Dance modding!

---

## 🔧 Configuration

All settings are managed through the config file. Ensure you've properly set:
- `guild_id` - Your Discord server ID
- `channel_id` - Target channel ID  
- `token` - Your extracted Discord token

## 📚 Usage

Simply run the tool with your desired codename and coach count - the automation handles everything else seamlessly.

---

## ⚠️ Security Notice

- **Token Security**: Keep your Discord token private and secure
- **Dedicated Account**: Use a separate Discord account to avoid issues with your main account
- **Terms Compliance**: Ensure usage complies with Discord's Terms of Service
