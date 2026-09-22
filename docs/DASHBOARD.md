# 🌐 **Dashboard Complete Guide**

> *Tour of Ophelia's Web Dashboard - [queen-ophelia.duckdns.org](https://queen-ophelia.duckdns.org/)*

---

## **Table of Contents**

1. [Getting Started](#getting-started)
2. [Public Pages](#public-pages)
3. [Authenticated Pages](#authenticated-pages)
4. [Server Management](#server-management)
5. [Real-time Features](#real-time-features)
6. [Mobile Experience](#mobile-experience)

---

## **Getting Started**

### **Accessing the Dashboard**

**URL:** [https://queen-ophelia.duckdns.org/](https://queen-ophelia.duckdns.org/)

### **Login Process**

```
Step 1: Visit dashboard URL
    ↓
Step 2: Click "Login with Discord"
    ↓
Step 3: Authorize Ophelia (read-only permissions)
    ↓
Step 4: Redirected to dashboard with your servers
    ↓
Step 5: Select server to manage
```

### **What Login Gives You**
- ✅ View your personal statistics
- ✅ Manage your servers (if admin/mod)
- ✅ Access configuration panels
- ✅ View leaderboards and rankings
- ✅ Use real-time features

### **Without Login**
You can still view:
- Home page with bot info
- Commands list
- Public leaderboards
- Terms of service & privacy policy

---

## **Public Pages**

### **🏠 Home Page (`/`)**

**Access:** Public (no login required)

**What You'll See:**
```
┌─────────────────────────────────────────────┐
│  ┌─────────┐                                │
│  │  LOGO   │   🤖 OPHELIA BOT              │
│  │  (200px)│   Your Ultimate Discord       │
│  └─────────┘   Companion                   │
│                                             │
│  ─────────────────────────────────          │
│                                             │
│  📊 Servers: 150+                          │
│  👥 Users: 500,000+                        │
│  ⚡ Uptime: 99.9%                           │
│  🟢 Status: Online                         │
│                                             │
│  ┌──────────────┐  ┌──────────────┐        │
│  │ 🚀 Login     │  │ 📜 Commands  │        │
│  │ with Discord│  │              │        │
│  └──────────────┘  └──────────────┘        │
│                                             │
│  ─────────────────────────────────          │
│                                             │
│  ✨ Features:                               │
│  • 120+ Commands                            │
│  • Real-time Dashboard                      │
│  • AI Image Generation                      │
│  • Boss Fight System                        │
│  • Discord Wrapped                          │
└─────────────────────────────────────────────┘
```

**Features:**
- Bot statistics at a glance
- Quick login button
- Link to commands page
- Feature highlights
- Status indicator

---

### **📜 Commands Page (`/commands`)**

**Access:** Public

**Layout:**
```
┌─────────────────────────────────────────────┐
│  📜 COMMANDS REFERENCE                     │
│  ─────────────────────────────────          │
│                                             │
│  [All] [Fun] [Utility] [Mod] [Config]      │
│                                             │
│  ┌──────────────────────────────────┐       │
│  │ 🎮 FUN COMMANDS                  │       │
│  ├──────────────────────────────────┤       │
│  │ /meme      Get random memes     │       │
│  │ /trivia    Play trivia quiz     │       │
│  │ /ship      Ship two users       │       │
│  │ /uno       Play UNO game        │       │
│  │ /imagine   AI image generation  │       │
│  │ ...                              │       │
│  └──────────────────────────────────┘       │
│                                             │
│  ┌──────────────────────────────────┐       │
│  │ 🛠️ UTILITY COMMANDS              │       │
│  ├──────────────────────────────────┤       │
│  │ /translate Translate text        │       │
│  │ /weather   Weather lookup        │       │
│  │ /wiki      Wikipedia search      │       │
│  │ ...                              │       │
│  └──────────────────────────────────┘       │
└─────────────────────────────────────────────┘
```

**Features:**
- Category tabs (click to filter)
- Search functionality
- Command descriptions
- Usage examples
- Icons for each category
- Responsive design

**Categories Available:**
- 🎉 Fun (35+ commands)
- 🛠️ Utility (50+ commands)
- 🛡️ Moderation (22+ commands)
- ⚙️ Configuration (10+ commands)
- 📊 Social (15+ commands)

---

### **🏆 Leaderboard Page (`/leaderboard`)**

**Access:** Public

**Leaderboard Types:**
| Tab | What It Shows |
|-----|---------------|
| 📈 **XP** | Most active users by experience points |
| ❤️ **Reputation** | Most respected users |
| 🔢 **Counting** | Counting game champions |
| 🎯 **GTN** | Guess The Number masters |
| 🎙️ **Voice** | Voice chat hours leaders |
| ⚔️ **Dragon** | Boss fight heroes |

**Layout:**
```
┌─────────────────────────────────────────────┐
│  🏆 GLOBAL LEADERBOARD                     │
│  ─────────────────────────────────          │
│                                             │
│  [XP] [Rep] [Count] [GTN] [Voice] [Dragon] │
│                                             │
│  ┌──────────────────────────────────┐       │
│  │ #1  👤 UserOne      💎 Lv.45    │       │
│  │     125,400 XP  📈 +2,300 today │       │
│  ├──────────────────────────────────┤       │
│  │ #2  👤 UserTwo      💎 Lv.42    │       │
│  │     118,200 XP  📈 +1,800 today │       │
│  ├──────────────────────────────────┤       │
│  │ #3  👤 UserThree    💎 Lv.39    │       │
│  │     105,900 XP  📈 +1,500 today │       │
│  │ ...                              │       │
│  └──────────────────────────────────┘       │
│                                             │
│  Showing 1-20 of 15,000 users               │
│  [Load More]                               │
└─────────────────────────────────────────────┘
```

**Features:**
- Multiple leaderboard categories
- Rank numbers with special styling for top 3
- Level display with badges
- Daily/weekly change indicators
- Pagination for large lists
- Click user to see profile

---

## **Authenticated Pages**

### **👤 My Stats (`/my-stats`)**

**Requires:** Login

**Shows:**
```
┌─────────────────────────────────────────────┐
│  📊 MY STATISTICS                         │
│  ─────────────────────────────────          │
│                                             │
│  ┌─────────┐  👤 YourUsername              │
│  │ AVATAR  │  💎 Level 42                  │
│  │         │  📈 125,400 / 176,400 XP      │
│  └─────────┘  ████████░░░░ 71%             │
│                                             │
│  ─────────────────────────────────          │
│                                             │
│  📊 QUICK STATS                             │
│  ┌────────────────┬────────────────┐        │
│  │ Messages      │ 45,230         │        │
│  │ Voice Hours   │ 120h           │        │
│  │ Commands Used │ 8,450          │        │
│  │ Reputation    │ +250           │        │
│  └────────────────┴────────────────┘        │
│                                             │
│  🏆 ACHIEVEMENTS                            │
│  🥇 Top 10% Active Users                    │
│  🗣️ Voice Chat Enthusiast                   │
│  🎮 Gaming Champion                         │
│                                             │
│  📅 RECENT ACTIVITY                        │
│  • Used /meme in #general                  │
│  • Leveled up to 42!                       │
│  • Won UNO game                            │
└─────────────────────────────────────────────┘
```

**Data Displayed:**
- Profile picture and username
- Current level and XP progress bar
- Total messages sent
- Voice chat hours
- Commands used count
- Reputation score
- Achievement badges
- Recent activity feed
- Server membership info

---

### **👤 User Profile (`/user/:userId`)**

**Access:** Public (more data if own profile or logged in)

**Public Can See:**
- Username, avatar, discriminator
- Level and XP (no exact numbers)
- Badge display (icons only)
- Public achievements
- Servers in common (if logged in)

**Owner/Elite Can See:**
- Exact XP numbers
- Full command history
- All servers list
- Detailed stats breakdown
- Join dates per server

---

### **🖥️ My Servers (`/servers`)**

**Requires:** Login + Manage Server permission

**Shows:**
```
┌─────────────────────────────────────────────┐
│  🖥️ MY SERVERS                            │
│  ─────────────────────────────────          │
│                                             │
│  ┌──────────────────────────────────┐       │
│  │ 📛 Awesome Community            │       │
│  │    👥 1,234 members             │       │
│  │    [Manage] [Dashboard]         │       │
│  ├──────────────────────────────────┤       │
│  │ 📛 Gaming Hub                   │       │
│  │    👥 567 members               │       │
│  │    [Manage] [Dashboard]         │       │
│  ├──────────────────────────────────┤       │
│  │ 📛 Chill Zone                   │       │
│  │    👥 89 members                │       │
│  │    [Manage] [Dashboard]         │       │
│  └──────────────────────────────────┘       │
└─────────────────────────────────────────────┘
```

**Features:**
- List of servers you can manage
- Member counts
- Quick links to config/dashboard
- Server icons
- Online status indicator

---

## **Server Management**

### **⚙️ Server Config (`/config/:guildId`)**

**Requires:** Manage Server permission

**Configuration Sections:**
```
┌─────────────────────────────────────────────┐
│  ⚙️ SERVER CONFIGURATION                   │
│  ─────────────────────────────────          │
│  📛 Server Name                            │
│                                             │
│  ┌──────────────────────────────────┐       │
│  │ 📝 GENERAL SETTINGS             │       │
│  │                                  │       │
│  │ Prefix: /                        │       │
│  │ Language: English                │       │
│  │ Bot Mood: Friendly 😊            │       │
│  │ [Save Changes]                   │       │
│  └──────────────────────────────────┘       │
│                                             │
│  ┌──────────────────────────────────┐       │
│  │ 👋 WELCOME MESSAGES              │       │
│  │                                  │       │
│  │ Enable: [✓] ON                  │       │
│  │ Channel: #welcome               │       │
│  │ Message: Welcome {user}!        │       │
│  │ Canvas Image: [✓] Enabled       │       │
│  │ [Preview] [Save]                 │       │
│  └──────────────────────────────────┘       │
│                                             │
│  ┌──────────────────────────────────┐       │
│  │ 🎖️ LEVELING SYSTEM              │       │
│  │                                  │       │
│  │ Enable: [✓] ON                  │       │
│  │ XP Per Message: 2-5             │       │
│  │ XP Per Voice Min: 1             │       │
│  │ Level Up Channel: #levelups     │       │
│  │ [Save Changes]                   │       │
│  └──────────────────────────────────┘       │
│                                             │
│  [Welcome] [Leveling] [Autorole] [Mod]     │
│  [Reaction Roles] [Starboard] [More...]    │
└─────────────────────────────────────────────┘
```

**Configurable Features:**
- General settings (prefix, language, mood)
- Welcome/leave messages
- Leveling & XP system
- Auto-role assignment
- Reaction roles
- Starboard system
- Word chain game
- Moderation settings
- And more...

---

### **📊 Server Dashboard (`/dashboard/:guildId`)**

**Requires:** Manage Server permission

**Analytics Shown:**
```
┌─────────────────────────────────────────────┐
│  📊 SERVER DASHBOARD                      │
│  ─────────────────────────────────          │
│  📛 Server Name                            │
│                                             │
│  ┌──────────────────┐ ┌──────────────────┐ │
│  │ 📈 GROWTH CHART  │ │ 👥 MEMBER STATS  │ │
│  │    ▁▂▃▅▆▇      │ │ Total: 1,234    │ │
│  │                  │ │ Online: 456     │ │
│  │                  │ │ Bots: 12        │ │
│  │                  │ │ Humans: 1,222   │ │
│  └──────────────────┘ └──────────────────┘ │
│                                             │
│  ┌──────────────────────────────────┐       │
│  │ 🎯 TOP COMMANDS (7 days)         │       │
│  │                                  │       │
│  │ /meme      ██████████  2,340    │       │
│  │ /trivia    ████████░░  1,890    │       │
│  │ /profile   ███████░░░  1,567    │       │
│  │ /avatar    ██████░░░░  1,234    │       │
│  │ /ship      ████░░░░░░    987    │       │
│  └──────────────────────────────────┘       │
│                                             │
│  ┌──────────────────┐ ┌──────────────────┐ │
│  │ 🏆 TOP USERS     │ │ 🛡️ MOD ACTIONS  │ │
│  │ 1. UserOne       │ │ Bans: 12        │ │
│  │ 2. UserTwo       │ │ Kicks: 34       │ │
│  │ 3. UserThree     │ │ Warns: 56       │ │
│  └──────────────────┘ │ Purges: 7       │ │
│                       └──────────────────┘ │
└─────────────────────────────────────────────┘
```

**Available Analytics:**
- Member growth over time
- Command usage charts (7-day)
- Top active users
- Moderation action summary
- Channel activity heatmap
- Popular features usage
- Voice chat statistics

---

## **Guild-Requiring Pages**

### **🎂 Birthdays (`/birthdays/:guildId`)**

**Needs:** Guild ID (from server list or direct link)

**Displays:**
```
┌─────────────────────────────────────────────┐
│  🎂 BIRTHDAYS - Server Name               │
│  ─────────────────────────────────          │
│                                             │
│  🎉 TODAY'S BIRTHDAYS!                     │
│  ┌──────────────────────────────────┐       │
│  │ 🎂 UserOne - Turns 25 today!    │       │
│  │    [Send Birthday Wish]          │       │
│  └──────────────────────────────────┘       │
│                                             │
│  📅 UPCOMING BIRTHDAYS                    │
│  ┌──────────────────────────────────┐       │
│  │ Oct 22 - UserTwo (🎂 28th)      │       │
│  │ Oct 25 - UserThree (🎂 21st)    │       │
│  │ Nov 02 - UserFour (🎂 19th)     │       │
│  │ Nov 15 - UserFive (🎂 30th)     │       │
│  └──────────────────────────────────┘       │
│                                             │
│  📊 STATS                                 │
│  • Total Birthdays: 45                   │
│  • This Month: 3                          │
│  • Today: 1                               │
│  • Unique Months: 10                      │
└─────────────────────────────────────────────┘
```

**Features:**
- Today's birthdays highlighted
- Upcoming birthdays list
- Monthly grouping
- Age display (if set, hidden for non-elite)
- Birthday wish buttons
- Statistics summary

**Note:** Year and age are **hidden from public view** for privacy. Only visible to authenticated users with appropriate permissions.

---

### **😴 AFK List (`/afklist`)**

**Needs:** Guild ID

**Shows:**
```
┌─────────────────────────────────────────────┐
│  😴 AFK USERS - Server Name               │
│  ─────────────────────────────────          │
│                                             │
│  Currently AFK: 3 users                    │
│                                             │
│  ┌──────────────────────────────────┐       │
│  │ 👤 UserOne                       │       │
│  │    Reason: Eating dinner 🍕       │       │
│  │    Since: 15 minutes ago         │       │
│  │    Pings while AFK: 3            │       │
│  │    [Mention] [View Pings]         │       │
│  ├──────────────────────────────────┤       │
│  │ 👤 UserTwo                       │       │
│  │    Reason: Sleeping 😴            │       │
│  │    Since: 2 hours ago            │       │
│  │    Pings while AFK: 12           │       │
│  │    [Mention] [View Pings]         │       │
│  └──────────────────────────────────┘       │
│                                             │
│  [Refresh List]                            │
└─────────────────────────────────────────────┘
```

**Features:**
- Currently AFK users list
- AFK reasons
- Time since going AFK
- Ping collection count
- Quick mention button
- View pings link
- Auto-refresh option

---

### **⚔️ Boss Fight Live Viewer (`/fight?token=xxx`)**

**Needs:** Valid fight token (generated during battle)

**This is a REAL-TIME page using Socket.IO!**

```
┌─────────────────────────────────────────────┐
│  ⚔️ DRAGON BOSS FIGHT                    │
│  ─────────────────────────────────          │
│                                             │
│  ┌──────────────────────────────────┐       │
│  │  🐉 ANCIENT RED DRAGON           │       │
│  │                                  │       │
│  │  ████████████████████ 100% HP    │       │
│  │  10,000 / 10,000                │       │
│  └──────────────────────────────────┘       │
│                                             │
│  ⚔️ PARTICIPANTS (5 fighting)              │
│  ┌──────────────────────────────────┐       │
│  │ ⚔️ UserOne  Warrior  💚 100%    │       │
│  │    Damage: 1,230  Attacks: 5     │       │
│  ├──────────────────────────────────┤       │
│  │ ⚔️ UserTwo  Healer   💚 85%     │       │
│  │    Damage: 450   Heals: 12      │       │
│  ├──────────────────────────────────┤       │
│  │ ⚔️ UserThree Tank    💚 92%     │       │
│  │    Damage: 890   Blocked: 23    │       │
│  └──────────────────────────────────┘       │
│                                             │
│  ┌──────────────────────────────────┐       │
│  │  ⚔️ YOUR ACTIONS                 │       │
│  │  [⚔️ Attack] [💚 Heal] [🛡️ Defend]│       │
│  │  [💫 Special] [🏃 Flee]          │       │
│  │                                  │       │
│  │  Cooldowns: Attack: Ready        │       │
│  │             Heal: 15s            │       │
│  └──────────────────────────────────┘       │
│                                             │
│  📜 BATTLE LOG                            │
│  [14:32:01] UserOne attacks for 250 dmg!   │
│  [14:32:03] Dragon breathes fire!          │
│  [14:32:05] UserTwo heals party for 150    │
│  [Auto-scrolling log...]                   │
└─────────────────────────────────────────────┘
```

**Real-Time Features:**
- Live HP bars (update instantly)
- Participant status
- Action buttons with cooldowns
- Battle log (auto-scrolling)
- Damage tracking
- Victory/defeat screen
- Reward distribution

**How to Access:**
1. Start/join a boss fight in Discord
2. Bot sends fight viewer link
3. Click link (token auto-filled)
4. Watch battle in real-time!
5. No refresh needed - uses WebSocket

---

## **Real-time Features (Socket.IO)**

The dashboard uses **Socket.IO** for real-time updates:

### **Live DM Progress**
When sending DMs to multiple users:
- Progress bar updates live
- Success/failure counters
- Completion notification
- Error handling in real-time

### **Admin Notifications**
For authorized users:
- New error alerts
- System notifications
- Security warnings
- Update announcements

### **User Search**
- Instant results as you type
- No page reload needed
- Shows avatar, username, tag

### **Stats Updates**
- Leaderboard changes
- New achievements
- Level-up notifications

---

## **Mobile Experience**

The dashboard is **fully responsive**!

### **Mobile Optimizations:**
- ✅ Touch-friendly buttons (min 44px)
- ✅ Responsive grids (1-2 columns on mobile)
- ✅ Hamburger menu on small screens
- ✅ Swipe-friendly carousels
- ✅ Optimized images (lazy loading)
- ✅ Fast loading (<3s on 4G)

### **Mobile Layout Example:**
```
┌──────────────┐
│  ☰  OPHELIA  │
├──────────────┤
│              │
│  [Login]     │
│  [Commands]  │
│  [Support]   │
│              │
│  📊 Stats:   │
│  150 servers │
│  500K users  │
│              │
└──────────────┘
```

---

## **Dashboard Tips & Tricks**

### **⌨️ Keyboard Shortcuts**
| Shortcut | Action |
|----------|--------|
| `/` | Focus search |
| `Esc` | Close modals |
| `Enter` | Submit forms |

### **🔗 Bookmarking**
You can bookmark these pages for quick access:
- `/my-stats` - Your stats
- `/leaderboard` - Rankings
- `/commands` - Command reference

### **🔄 Auto-Refresh**
Some pages auto-update:
- Boss Fight viewer (real-time)
- DM progress (during send)
- Stats (optional toggle)

### **📱 Add to Home Screen**
On mobile browsers:
1. Visit dashboard
2. Tap share button
3. "Add to Home Screen"
4. Opens like an app!

---

## **Troubleshooting**

### **Login Issues**
- **Problem:** OAuth error
- **Solution:** Clear cookies, retry, check Discord status

### **Server Not Showing**
- **Problem:** Server missing from list
- **Solution:** Ensure you have "Manage Server" permission

### **Config Not Saving**
- **Problem:** Changes not applied
- **Solution:** Check bot has permissions, refresh page

### **Fight Viewer Blank**
- **Problem:** Nothing showing
- **Solution:** Token may be expired, get new link from Discord

---

## **Need Help?**

- 📚 **[Full Documentation](docs/FEATURES.md)**
- 🔒 **[Security Info](docs/SECURITY.md)**
- 💬 **[Support Server](https://discord.gg/BD9Xx48WZd)**
- 🌐 **[Dashboard](https://queen-ophelia.duckdns.org/)**

---

*Dashboard Version: 3.0.0*  
*Last Updated: September 2026*
