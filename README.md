<div align="center">

<img src="https://raw.githubusercontent.com/nonxe/a1/main/aashif-banner.svg" width="800" alt="AASHIF-MD"/>

# 🤖 AASHIF-MD

*A powerful multi-device WhatsApp bot built with [baileys🌙](https://www.npmjs.com/package/gifted-baileys)*

[![Node.js](https://img.shields.io/badge/Node.js-20+-green?logo=node.js)](https://nodejs.org)
[![License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)
[![Version](https://img.shields.io/badge/Version-5.0.0-orange)](package.json)

</div>

---

## 📋 Table of Contents

- [Features](#-features)
- [Requirements](#-requirements)
- [Environment Variables](#-environment-variables)
- [Deployment](#-deployment)
  - [Heroku](#1-heroku-recommended)
  - [Railway](#2-railway)
  - [Koyeb](#3-koyeb)
  - [Docker](#4-docker--vps)
  - [Local](#5-local-machine)
- [Commands](#-commands)

---

## ✨ Features

### 🤖 AI & Chat
Multi-model AI chat accessible directly in WhatsApp. Switch between providers without leaving the conversation.

| Command | Description |
|---|---|
| `giftedai` | Built-in GiftedAI assistant |
| `chatai` | General AI chat interface |
| `gpt` / `gpt4` / `gpt4o` / `gpt4o-mini` | OpenAI GPT variants |
| `gemini` | Google Gemini AI |
| `venice` | Venice AI model |
| `letmegpt` | LetMeGPT integration |

### 📥 Downloaders
Download media from major platforms with a single command.

| Command | Platform |
|---|---|
| `ytv` / `yts` | YouTube video / audio search |
| `tiktok` | TikTok videos |
| `fb` | Facebook videos |
| `ig` | Instagram media |
| `twitter` | Twitter/X videos |
| `spotify` | Spotify tracks |
| `gdrive` | Google Drive files |
| `mediafire` | MediaFire files |
| `apk` | APK downloads |
| `snack` | SnackVideo |
| `pastebin` | Pastebin content |
| `gitclone` | Clone a GitHub repo as ZIP |
| `download` | Universal media downloader |

### 👥 Group Management
Full-featured admin toolkit for managing WhatsApp groups.

- **Member control** — `add`, `kick`, `promote`, `demote`
- **Group settings** — `mute`, `unmute`, `groupname`, `gcdesc`, `gcpp`, `resetlink`
- **Join requests** — `accept`, `reject`, `acceptall`, `rejectall`, `listrequests`
- **Tagging** — `everyone`, `tagall`, `tagadmins`, `hidetag`
- **Anti-abuse** — `antilink`, `antipromote`, `antidemote`, `antigroupmention` with configurable warn limits
- **Auto events** — welcome messages, goodbye messages, group event logging
- **Utility** — `newgroup`, `killgc`, `link`, `online`, `togroupstatus`

### 🛠️ Tools
Productivity and utility commands for everyday use.

| Command | Description |
|---|---|
| `ssweb` / `ssphone` / `sstab` / `sspc` | Screenshot a URL in different viewports |
| `createqr` / `readqr` | Generate or decode QR codes |
| `createpdf` | Convert content to PDF |
| `web2zip` | Download an entire website as ZIP |
| `domaincheck` | WHOIS / availability check |
| `remini` | AI image enhancement |
| `photoeditor` | Photo editing tools |
| `emojimix` | Mix two emojis together |
| `fetch` | Raw HTTP fetch |
| `ebinary` / `debinary` | Encode / decode binary |
| `ebase` / `dbase` | Encode / decode Base64 |
| `ttp` / `fancy` | Stylish text rendering |
| `define` | Dictionary definitions |
| `rename` | Rename a sent file |

### 🔄 Converters
Convert between media formats without any third-party app.

| Command | Description |
|---|---|
| `sticker` | Image or video → WhatsApp sticker |
| `toimg` | Sticker → image |
| `toaudio` | Video → audio |
| `tovideo` | Audio / sticker → video |
| `toptt` | Video → push-to-talk voice note |
| `ptv` | Convert to video note |
| `circle` | Make a circular sticker/image |
| `take` | Take / steal a sticker |
| `extract` | Extract media from a message |

### 🔍 Search
Search the web and popular services directly from WhatsApp.

| Command | Description |
|---|---|
| `google` | Google web search |
| `ggleimage` | Google image search |
| `unsplash` | High-res stock photos |
| `wallpapers` | Wallpaper search |
| `yts` | YouTube search |
| `spotifysearch` | Spotify track search |
| `stickersearch` | Search sticker packs |
| `shazam` | Identify a song from audio |
| `lyrics` | Fetch song lyrics |
| `weather` | Current weather by location |
| `npm` | Search npm packages |
| `wattpad` | Search Wattpad stories |
| `happymod` / `apkmirror` | APK search |
| `szsearch` | SauceNAO reverse image search |

### ⚽ Sports
Live sports data and betting tools.

| Command | Description |
|---|---|
| `livescore` | Live match scores |
| `upcomingmatches` | Upcoming fixtures |
| `standings` | League standings |
| `topscorers` | Top scorer lists |
| `sportnews` | Latest sports news |
| `gamehistory` | Past match results |
| `surebet` | Sure-bet finder |

### 🎮 Games
Multiplayer games playable inside any WhatsApp group.

| Game | Commands |
|---|---|
| **Tic Tac Toe** | `tictactoe`, `tttjoin`, `tttboard`, `tttend`, `tttai` (vs AI) |
| **Word Chain Game** | `wcg`, `wcgjoin`, `wcgbegin`, `wcgend`, `wcgscores`, `wcgai` |
| **Dice** | `dice`, `dicejoin`, `roll`, `diceend`, `diceai` |
| **Hangman** | `hangman` |

### 📝 Notes
Per-group note management system with admin controls.

`addnote`, `allnotes`, `delnote`, `updatenote`, `delallnotes`, `admindelnote`, `adminupdatenote`, `adminclearnotes`

### 📬 Temp Mail
Disposable email addresses, right inside WhatsApp.

`tempmail`, `tempinbox`, `delmail`, `tempmailhelp`

### 🕌 Religion
`bible` — Bible verse lookup and more religious content commands.

### 🎨 Logo Generator
Generate stylized text logos in dozens of creative themes, including Fire, Galaxy, Devil, Snow, Thunder, Underwater, Typography, Blackpink, Arena of Valor, and many more. All logo commands accept custom text as input.

### ⚙️ Owner & Bot Settings
Full bot customisation available to the owner/sudo users.

- **Mode** — `setmode` (public / private)
- **Prefix** — `setprefix`
- **Persona** — `setbotname`, `setownername`, `setbotpic`, `setownernumber`
- **Auto features** — `setautoread`, `setautolikestatus`, `setautoreact`, `setautoreply`, `setautobio`, `setchatbot`, `setchatbotmode`
- **Protections** — `setantidelete`, `setantiedit`, `setantilink`, `setautoblock`, `setpmpermit`
- **Sticker pack** — `setpackname`, `setpackauthor`
- **Sudo management** — `setsudo`, `delsudo`, `getsudo`
- **Misc** — `setprefix`, `settimezone`, `setwelcome`, `setgoodbye`, `setcaption`, `setuploadcaption`, `setbotrepo`

### 🔒 Auto-Protections
Runs silently in the background to keep groups clean:

- **Anti-link** — warns or kicks members posting links
- **Anti-delete** — re-sends deleted messages to the group
- **Anti-edit** — logs message edits
- **Anti-promote / anti-demote** — reverts unauthorized role changes
- **Anti-group-mention** — restricts mass-mention abuse
- **Auto-read / auto-like status** — views and reacts to contacts' statuses automatically
- **Auto-reply** — customisable auto-response in DMs
- **PM Permit** — blocks unknown DMs, sends an approval message

---

## 📦 Requirements

- **Node.js** 20+
- **FFmpeg** (for media conversion)
- **PostgreSQL** database *(optional — falls back to local SQLite)*
- A WhatsApp account to pair with the bot

---

## 🔑 Environment Variables

| Variable | Required | Default | Description |
|---|---|---|---|
| `SESSION_ID` | ✅ Yes | — | Pairing session ID from the session page |
| `MODE` | ✅ Yes | `public` | `public` — anyone can use the bot; `private` — bot owner only |
| `TIME_ZONE` | ✅ Yes | `Africa/Nairobi` | Your timezone (e.g. `Asia/Kolkata`, `America/New_York`) |
| `AUTO_READ_STATUS` | No | `true` | Auto-view contacts' WhatsApp statuses (`true` / `false`) |
| `AUTO_LIKE_STATUS` | No | `true` | Auto-like contacts' statuses (`true` / `false`) |
| `DATABASE_URL` | No | *(SQLite fallback)* | PostgreSQL connection string. Free options: [Neon](https://neon.tech), [Supabase](https://supabase.com), [Aiven](https://aiven.io) |

---

## 🚀 Deployment

### 1. Heroku *(recommended)*

The `app.json` is pre-configured with a free PostgreSQL add-on and the FFmpeg buildpack.

1. Click **Deploy Now** below (or use your own fork URL):

   [![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/ityee/wa)

2. Fill in the required config vars (`SESSION_ID`, `MODE`, `TIME_ZONE`).
3. Click **Deploy App** and wait for the build to finish.
4. Open the app URL — the bot will start and display a QR / pairing code.

> The `heroku-postgresql:essential-0` add-on is auto-attached. `DATABASE_URL` is set automatically.

---

### 2. Railway

Railway can provision a Postgres database and link it automatically.

```bash
# 1. Push your fork to GitHub, then import it at railway.app
# 2. In your project: "+ New" → "Database" → "PostgreSQL"
#    Railway sets DATABASE_URL automatically via variable reference.
# 3. In your service "Variables" tab, add:
SESSION_ID=<your-session-id>
MODE=public
TIME_ZONE=Africa/Nairobi
AUTO_READ_STATUS=true
AUTO_LIKE_STATUS=true
```

Railway uses `railway.toml` and `Dockerfile` automatically — no extra configuration needed.

---

### 3. Koyeb

Koyeb does not include a built-in database, so create a free one first.

**Get a free PostgreSQL database:**
- [Neon.tech](https://neon.tech) — generous free tier
- [Supabase](https://supabase.com) — free tier
- [Aiven](https://aiven.io) — free trial

```bash
# Deploy via CLI:
koyeb app init aashif-md --config koyeb.yaml

# Or via the dashboard:
# "Create App" → "GitHub" → select your repo → set env vars
```

Set `DATABASE_URL` to your external Postgres connection string, along with the other variables listed above.

---

### 4. Docker / VPS

Run anywhere Docker is available.

```bash
# Build the image
docker build -t aashif-md .

# Run with environment variables
docker run -d \
  -e SESSION_ID=your_session_id \
  -e MODE=public \
  -e TIME_ZONE=Africa/Nairobi \
  -e AUTO_READ_STATUS=true \
  -e AUTO_LIKE_STATUS=true \
  -e DATABASE_URL=postgresql://user:pass@host/db \
  -p 5000:5000 \
  aashif-md
```

Or with `docker-compose`:

```yaml
version: "3.9"
services:
  bot:
    build: .
    ports:
      - "5000:5000"
    environment:
      SESSION_ID: your_session_id
      MODE: public
      TIME_ZONE: Africa/Nairobi
      AUTO_READ_STATUS: "true"
      AUTO_LIKE_STATUS: "true"
      DATABASE_URL: postgresql://user:pass@db/aashifmd
    restart: unless-stopped
```

---

### 5. Local Machine

```bash
# Clone the repository
git clone https://github.com/ityee/wa
cd wa

# Install dependencies
npm install

# Copy and fill in your environment variables
cp .env.example .env
# Edit .env with your SESSION_ID, MODE, TIME_ZONE, etc.

# Start the bot
npm start

# Or with PM2 for persistent background running:
npm install -g pm2
pm2 start index.js --name aashif-md
pm2 save
pm2 startup
```

> **Note:** FFmpeg must be installed on your system for media conversion commands to work.
> - Ubuntu/Debian: `sudo apt install ffmpeg`
> - macOS: `brew install ffmpeg`

---

## 📖 Commands

Send `.cmd` to the bot in any chat to get a full interactive command list, or `.help <command>` for details on a specific command.

---

<div align="center">

Made with ❤️ by **Aashif Ser** · Powered by [gifted-baileys](https://www.npmjs.com/package/gifted-baileys)

</div>

