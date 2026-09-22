# 🎮 **Ophelia - Complete Features Guide**

> *Everything Ophelia can do for your Discord server!*

---

## 📚 **Table of Contents**

1. [Fun & Entertainment](#fun--entertainment)
2. [Utility Tools](#utility-tools)
3. [Social Features](#social-features)
4. [Games System](#games-system)
5. [Creative Tools](#creative-tools)
6. [Moderation Suite](#moderation-suite)
7. [Server Configuration](#server-configuration)
8. [Leveling & Rewards](#leveling--rewards)
9. [Dashboard Features](#dashboard-features)

---

## 🎉 **Fun & Entertainment**

### **Meme & Humor**
- **`/meme`** - Fetch random memes from Reddit
  - Support for custom subreddings
  - NSFW filter option
  - Multiple meme formats
  
- **`/joke`** - Get random jokes from multiple categories
- **`/roast`** - AI-powered roasts (light-hearted fun!)
- **`/advice`** - Random life advice
- **`/quote`** - Inspirational quotes database

### **Social Interaction**
- **`/ship`** - Calculate compatibility between two users
  - Percentage match
  - Generated ship name
  - Heart visualization bar
  
- **`/action`** - Anime-style roleplay actions
  - Actions: hug, kiss, slap, pat, cuddle, poke, tickle, etc.
  - High-quality GIFs from Tenor/Giphy
  - Target specific users
  
- **`/truthordare`** - Interactive game
  - Button-based responses
  - Custom difficulty levels
  - Group play support

- **`/mimic`** - Fun webhook messages
  - Send messages as other users (fun mode)
  - Configurable per-server
  - Permission-based access

### **Pranks & Fun**
- **`/leak`** - Fake "search history" leak prank
- **`/fakenitro`** - Fake Nitro gift animation
- **`/fontstyle`** - Convert text to fancy fonts (𝒻𝒶𝓃𝒸𝓎 𝓉𝑒𝓍𝓉)
- **`/selflock`** - Timeout yourself (for focus mode)

---

## 🛠️ **Utility Tools**

### **Information Commands**
| Command | Output |
|---------|--------|
| `/ping` | Bot latency in ms |
| `/avatar @user` | Full resolution avatar + banner |
| `/userinfo @user` | Complete user profile data |
| `/serverinfo` | Server stats, members, roles, channels |
| `/roleinfo @role` | Role details and permissions |

### **Search & Knowledge**
| Command | Description |
|---------|-------------|
| `/translate <text>` | Translate to any language (100+) |
| `/translate_msg` | Translate a message in-place |
| `/weather <city>` | Current weather + forecast |
| `/wiki <query>` | Wikipedia summary |
| `/define <word>` | Dictionary definition |
| `/math <expression>` | Calculator (supports complex math) |
| `/country <name>` | Country facts and info |
| `/news` | Latest headlines |
| `/robloxstats <user>` | Roblox profile stats |

### **Generators & Tools**
| Command | Description |
|---------|-------------|
| `/qrcode <text/url>` | Generate scannable QR code |
| `/screenshot <url>` | Capture website screenshot |
| `/ocr` (reply to image) | Extract text from images |
| `/shorturl <url>` | Create short URL |
| `/embed` | Build custom rich embeds |
| `/emoji <emoji>` | Enlarge emoji (custom supported) |
| `/emojikitchen <emoji1> <emoji2>` | Combine two emojis! |
| `/emojisteal <emoji>` | Steal custom emoji from server |
| `/morse <text>` | Encode/decode Morse code |
| `/tempmail` | Generate disposable email |
| `/card @user` | Generate user info card |

### **Productivity**
| Command | Description |
|---------|-------------|
| `/afk <reason>` | Set AFK status (auto-nickname) |
| `/afklist` | View all AFK users |
| `/remind <time> <msg>` | Set reminders |
| `/tldr <url/text>` | Summarize long content |
| `/firstmessage` | Get channel's first message |
| `/record` | Start recording voice chat |
| `/watch <channel>` | Monitor channel updates |
| `/dailychallenge` | Daily activity challenge |
| `/timecapsule <date> <msg>` | Future message delivery |
| `/myquotes` | Personal quote collection |
| `/confess <message>` | Anonymous confession |
| `/birthday set <date>` | Set your birthday |
| `/entertainment` | Get entertainment suggestions |
| `/invites` | Track invite statistics |
| `/extractText` | Extract text from various sources |

---

## **Social Features**

### **Profile System**
- **`/profile`** - Your complete Discord profile
  - XP and Level display
  - Rank in server/global
  - Achievement badges
  - Join date
  - Activity stats
  
- **`/leaderboard`** - Multiple leaderboard types
  - XP Leaderboard
  - Reputation Leaderboard
  - Voice Chat Leaderboard
  - Game-specific leaderboards
  
- **`/wrapped`** - Annual Discord recap (Spotify-style!)

### **Reputation System**
- Give/take reputation via context menu
- Daily rep limits
- Reputation leaderboard
- Special badges for top reputations

### **AFK System**
- Automatic nickname prefix (`[AFK]`)
- Optional AFK role assignment
- Ping collection while AFK
- AFK reason display
- Auto-remove on message

### **Social Features**
- **Birthdays** - Track and celebrate birthdays
- **Confessions** - Anonymous messaging channel
- **Time Capsules** - Send messages to future self
- **Quotes Collection** - Save favorite quotes

---

## 🎮 **Games System**

### **UNO Card Game**
- Full UNO rules implementation
- Beautiful card UI
- Color and Draw Wild cards
- Skip, Reverse, Draw Two cards
- 60-second turn timer
- Multiplayer support (2-10 players)
- Win/loss tracking

### **Trivia Quiz**
- 9 categories: Science, History, Sports, etc.
- 3 difficulty levels: Easy, Medium, Hard
- Timed answers (15 seconds)
- Score tracking
- Category-specific leaderboards

### **Word Chain Game**
- Connect words by last letter
- XP rewards for valid words
- Level system (8 ranks)
- Streak bonuses
- Daily challenges
- Server-wide leaderboard

### **Counting Game**
- Server counting challenge
- Milestone celebrations
- High score tracking
- Streak system
- Reset on wrong number

### **Guess The Number (GTN)**
- 1-1000 number range
- Hint system (higher/lower)
- Guess tracking
- Win statistics
- Minimum guess competitions

### **Boss Fights (Dragon Battles)**
- Real-time Socket.IO battles
- Multiple dragon types
- Class system: Warrior, Healer, Tank
- Co-op gameplay (up to 10 players)
- Damage tracking
- Reward system
- Live battle viewer on dashboard

### **Other Games**
- **Slots** - Casino slot machine
- **Coinflip** - 50/50 chance
- **Roll Dice** - Custom dice (d6, d20, etc.)
- **Debates** - 1v1 structured debates with voting
- **Stories** - Interactive choose-your-own-adventure
- **Polls** - Create and vote on polls

---

## 🎨 **Creative Tools**

### **AI Features**
- **`/imagine <prompt>`** - AI Image Generation
  - Powered by Pollinations.ai
  - Various art styles
  - Free to use (10/day)

### **Emoji Kitchen**
- **`/emojikitten`** - Combine emojis
- **Examples:** 
  - 😂 + ❤️ = 😂‍❤️ (laughing with heart)
  - 🤔 + 💡 = 🤔‍💡 (thinking with lightbulb)
- 1000+ combinations possible

### **Media Tools**
- **`/image <query>`** - Search and share images
- **`/sendmedia <url>`** - Send media from URL
- **`/screenshot <url>`** - Website screenshots
- **`/ocr`** - Text extraction from images

### **Text Tools**
- **`/fontstyle`** - Fancy text generator
  - 𝒻𝒶𝓃𝒸𝓎 fonts
  - 𝐛𝐨𝐥𝐝 𝐢𝐭𝐚𝐥𝐢𝐜
  - 𝕄𝕠𝕟𝕠𝕤𝕡𝕒𝕔𝕖
  - And more!
  
- **`/embed`** - Custom embed builder
- **`/morse`** - Morse code converter
- **`/tldr`** - Content summarizer

---

## 🛡️ **Moderation Suite**

### **Basic Moderation**
| Command | Usage | Description |
|---------|-------|-------------|
| `/ban @user [reason]` | Ban permanently | Remove problematic users |
| `/unban @user` | Lift ban | Forgive banned users |
| `/kick @user [reason]` | Kick user | Temporary removal |
| `/timeout @user [duration]` | Mute user | Silence temporarily |
| `/warn @user [reason]` | Add warning | Track infractions |
| `/purge [count]` | Delete messages | Clean up spam |
| `/slowmode [seconds]` | Set slowmode | Reduce spam speed |

### **Advanced Moderation**
| Command | Description |
|---------|-------------|
| `/snipe` | See recently deleted message |
| `/snipelist` | View snipe history |
| `/sticky [message]` | Pin message to channel bottom |
| `/pin / unpin` | Pin/unpin messages |
| `/nick @user [name]` | Change nicknames |
| `/forcenickname @user [name]` | Force nickname |
| `/say [message]` | Bot speaks |
| `/note @user [note]` | Add user notes |
| `/case @user [#id]` | View mod cases |
| `/history @user` | Full mod history |
| `/transcript [#channel]` | Generate chat log |
| `/tempban @user [duration]` | Temporary ban |
| `/temprole @user @role [duration]` | Temporary role |
| `/massrole @role [add/remove]` | Bulk role manage |
| `/sban @user` | Softban (delete + ban) |
| `/setbounty @user [amount]` | Fun bounty system |

### **Auto-Moderation**
- **Anti-Spam** - Detect and handle spam
- **Anti-Link** - Block unwanted links
- **Word Filter** - Block profanity/custom words
- **Anti-Scam** - Known scam link detection
- **Mass-join Protection** - Raid prevention
- **Mod Logging** - Complete audit trail

---

## ⚙️ **Server Configuration**

### **Setup Wizard**
- **`/setup`** - Guided configuration
  - Step-by-step setup
  - Recommended defaults
  - Can be customized later

### **Welcome System**
- **`/welcome`** - Welcome/leave messages
  - Customizable templates
  - Canvas image generation
  - User count display
  - Embed or plain text
  - DM or channel welcome

### **Role Management**
- **`/autorole`** - Automatic role on join
  - Multiple roles support
  - Human/Bot separation
  - Delay options
  
- **`/reactionrole`** - Reaction role buttons
  - Customizable buttons
  - Multiple roles per message
  - Limited to one option
  - Remove on unreact

### **Leveling Configuration**
- **`/level`** - XP system settings
  - XP per message
  - XP per voice minute
  - Level-up announcements
  - Role rewards for levels
  - XP cooldown settings

### **Channel Systems**
- **`/jtcsetup`** - Join-to-Create voice
  - Auto-create voice channels
  - Custom naming templates
  - User limit options
  - Auto-delete when empty
  
- **`/starboard`** - Starboard system
  - ⭐ reaction threshold
  - Custom starboard channel
  - Link to original message

### **Other Config**
- **`/wordChainConfig`** - Word chain settings
- **`/mood`** - Bot personality
- **`/socials`** - Server social links
- **`/verify`** - Verification system
- **`/webhook-create`** - Easy webhook creation

---

## 📊 **Leveling & Rewards**

### **XP System**
```
Message XP:     2-5 XP per message (configurable)
Voice XP:       1 XP per minute in voice
First Message:  +10 XP bonus daily
Game Wins:      +20-50 XP depending on game
Reputation:     +5 XP per rep received
```

### **Level Calculation**
- **Formula:** `XP required = level² × 100`
- **Example:** Level 5 = 2,500 XP, Level 10 = 10,000 XP
- **No max level** - Keep growing!

### **Rewards**
- **Level Roles** - Auto-assign roles at levels
- **Level-up Messages** - Celebrate achievements
- **Badges** - Unlock for milestones
- **Special Perks** - Configurable per server

### **Leaderboards**
- **Server Leaderboard** - Top users in your server
- **Global Leaderboard** - Across all servers
- **Weekly/Monthly** - Time-based rankings
- **Category Specific** - Per-game, per-activity

### **Discord Wrapped** 🎁
Every December/January, get your personalized:
- Total messages sent
- Favorite channels
- Most used commands
- Voice chat hours
- Top friends (by interactions)
- Unique achievements
- Year-in-review stats

---

## 🌐 **Dashboard Features**

### **Access & Authentication**
- Secure Discord OAuth2 login
- HttpOnly, secure cookies
- Session management
- Permission-based access

### **Public Pages**
| Page | URL | Description |
|------|-----|-------------|
| Home | `/` | Bot info, stats, quick links |
| Commands | `/commands` | Complete command reference |
| Leaderboard | `/leaderboard` | Global rankings |
| TOS | `/tos` | Terms of service |
| Privacy | `/privacy-policy` | Privacy policy |

### **Authenticated Pages**
| Page | URL | Description |
|------|-----|-------------|
| My Stats | `/my-stats` | Personal statistics |
| My Servers | `/servers` | Servers you manage |
| Server Dashboard | `/dashboard/:id` | Analytics & management |
| Server Config | `/config/:id` | Settings panel |
| User Profile | `/user/:id` | View any user's public stats |

### **Guild-Requiring Pages**
| Page | URL | Description |
|------|-----|-------------|
| Birthdays | `/birthdays/:id` | Server birthday calendar |
| AFK List | `/afklist` | Currently AFK users |
| Mimic List | `/mimiclist` | Mimic permissions |
| Boss Fight | `/fight?token=xxx` | Live battle viewer |

### **Real-Time Features (Socket.IO)**
- **Live DM Progress** - See DM campaign status
- **Admin Room** - Real-time notifications
- **Battle Viewer** - Live boss fight updates
- **User Search** - Instant user lookup
- **Stats Updates** - Live statistics

---

## **Conclusion**

Ophelia is designed to be the **only bot you'll ever need** for your Discord server. With 120+ commands, beautiful dashboard, active development, and amazing community support, we're here to make your server the best it can be!

**Ready to get started?**

👉 [Invite Ophelia](https://discord.com/oauth2/authorize)  
👉 [Join Support Server](https://discord.gg/BD9Xx48WZd)  
👉 [Open Dashboard](https://queen-ophelia.duckdns.org/)

---

*For more information, check out the main [README.md](README.md)*
