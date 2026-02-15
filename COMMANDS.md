# iQ™ Command Reference

_All iQ™ slash commands are grouped below by category. For privacy and terms, see [PRIVACY.md](./PRIVACY.md) and [TOS.md](./TOS.md)._

---

## 🤖 AI & Intelligence

- `/web [query]` — Search the internet for current information.
- `/summarize [message_count]` — Summarize recent conversation (default: 50 messages).
- `/serverinsights` — View comprehensive server analytics and member activity.
- `/analyze` — Get AI-powered server recommendations.
- `/expert [topic]` — Find knowledgeable members on any topic (auto-learned).
- `/expert_config [enabled]` — Enable/disable expert finder tracking.
- `/heatmap [days]` — View server sentiment heatmap over time.
- `/heatmap_config [enabled]` — Enable/disable sentiment tracking.
- `/channelinsights` — Cross-channel activity analysis.
- `/insights_config [enabled]` — Enable/disable insights.
- `/helpers` — View top community helpers leaderboard.
- `/helperscan [enabled]` — Enable/disable helper tracking.

**Automatic AI Features:**
- React 🧠 on any message → ELI5 simplification (auto-enabled)
- Upload image + @iQ → Vision analysis
- Upload PDF/CSV/TXT + @iQ → File analysis

---

## 🗂️ Community Management

- `/debate [action] [topic]` — Structured debate with AI moderation.
  - `action:start` — Begin debate
  - `action:moderate` — AI summarizes arguments
  - `action:end` — Conclude debate
- `/icebreaker [enabled] [intensity]` — Auto conversation starters (1-5 intensity).
- `/weeklydigest` — Generate weekly server activity report.
- `/digest_config [enabled]` — Enable/disable weekly digest.
- `/bookmark [message_url] [note]` — **Staff Only** Save important messages.
- `/bookmarks` — View saved bookmarks.
- `/bookmark_delete [bookmark_id]` — **Staff Only** Remove a bookmark.

---

## 🎂 Member Recognition

- `/birthday [action] [user] [date]` — Manage member birthdays.
  - `action:add` — Add birthday (format: MM-DD)
  - `action:delete` — Remove birthday
  - `action:list` — View all birthdays
- `/birthday_config [enabled]` — Enable/disable birthday announcements.

**Automatic:** Birthday announcements post at midnight server time.

---

## ⏰ Reminders & Scheduling

- `/remind [message] [time]` — Set a reminder.
  - Time examples: "10 minutes", "2 hours", "tomorrow 9am"
- `/reminders` — View your active reminders.
- `/cancelreminder [reminder_id]` — Cancel a specific reminder.

**Features:** Supports recurring reminders and precise scheduling.

---

## 💰 Economy

- `/balance` — View your balance.
- `/daily` — Daily currency bonus.
- `/gamble [amount]` — Play to win or lose currency.
- `/slots` — Slot machine game.
- `/bankrobbery` — Risky group timed event.
- `/reflexes` — Quick reflex mini-game.
- `/work` — Simulated jobs with animated progress.
- `/beg` — Limited daily request for currency.
- `/transfer [user] [amount]` — Send currency to another user.
- `/leaderboard` — Global economy leaderboard.
- `/profile` — Personal economy page.

---

## 📈 Leveling & Reputation

- `/lv` — See your current level and XP.
- `/rep [user]` — Give reputation to other users.

---

## 🎮 Games & Fun

- `/8balliq [question]` — Magic 8-ball with visual responses.
- `/coin` — Coin flip.
- `/quote` — Random inspirational quote.
- `/joke` — Random joke.
- `/fact` — Random interesting fact.
- `/hug [user]` — Send a virtual hug.
- `/horoscope [sign]` — Daily sign-based reading.

---

## 🔧 Utility

- `/ping` — Check bot response time (with color feedback).
- `/avatar [user]` — Show member's avatar.
- `/userinfo [user]` — Extended profile information.
- `/serverinfo` — Information about this server.
- `/membercount` — Server member statistics.
- `/weather [location]` — Local weather look-up.
- `/define [word]` — Dictionary definition.
- `/translate [text] [to_language]` — Multilingual translation.
- `/calculate [expression]` — Simple math calculator.
- `/timer [duration]` — Set a countdown timer.
- `/afk [reason]` — Set away-from-keyboard status.

---

## 🛡️ Moderation

- `/mute [user] [duration] [reason]` — Mute member.
- `/kick [user] [reason]` — Remove user from server.
- `/ban [user] [reason]` — Ban user from server.
- `/softban [user] [reason]` — Ban/unban to clear message history.
- `/unban [user_id]` — Unban user.
- `/warn [user] [reason]` — Issue a warning.
- `/warnings [user]` — View user's warnings.
- `/clearwarns [user]` — Clear all warnings for a user.
- `/lock [channel] [reason]` — Restrict channel.
- `/unlock [channel]` — Release channel restrictions.
- `/slowmode [seconds]` — Set channel slowmode.
- `/purge [count]` — Bulk message removal.
- `/role [user] [role]` — Adjust user's roles.
- `/report [user] [reason]` — Escalate member to staff.
- `/setreportchannel [channel]` — Direct reports to specific channel.
- `/raidclean [duration]` — Cleanup accounts younger than specified time.
- `/raidstop` — End raid alert mode.
- `/automod [enabled] [toxicity_threshold]` — Configure auto-moderation.

---

## 📢 Server Management

- `/announce [channel] [message]` — Channel-wide broadcast.
- `/sticky [channel] [message]` — Add sticky message.
- `/unsticky [channel]` — Remove sticky messages.
- `/giveaway [duration] [winners] [prize]` — Host a giveaway.
- `/poll [question] [options]` — Create a poll.

---

## 🖼️ Image Generation

- `/generate [prompt] [style]` — Generate AI images.
  - Styles: photorealistic, anime, digital_art, oil_painting, sketch, 3d_render
- `/setimagechannels [channels]` — Restrict image gen to specific channels.
- `/listimagechannels` — View allowed image channels.

---

## 🧠 Bot Memory System

- `/memory` — **Owner Only** View iQ's persistent memory.
- `/remember [content] [category]` — **Owner Only** Save to memory.
- `/forget [search_term]` — **Owner Only** Remove from memory.

**Categories:** preference, fact, instruction, user_info

---

## 🌐 Guild Management (Owner Only)

- `/guilds` — List all servers iQ is in (paginated).
- `/guildinfo [guild_id]` — Detailed info about a specific server.
- `/guildleave [guild_id] [reason]` — Remove iQ from a server.

---

## 📰 RSS Feeds

- `/rssstatus` — Check all feeds' status.
- `/rsslogs` — Show feed logs.
- `/rsscheck` — Verify feed operation.
- `/rssclear` — Remove all feeds.
- `/rsserrors` — List RSS problems.

---

## 🔧 Bot Administration

- `/refresh` — **Owner Only** Full AI context refresh.
- `/setstatus [status]` — **Owner Only** Change iQ status message.
- `/resync` — **Owner Only** Manual command reload.

---

## Command Permissions Legend

- **No label** — Available to all members
- **Staff Only** — Requires Mod/Staff/Admin role
- **Owner Only** — Bot owner only

---

_For suggestions or feedback: [ROSY Discord](https://discord.gg/rosy) | Email: support@sereneinteractive.com_
