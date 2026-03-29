# EA-FC26-Bug-Reports
Professional QA bug reports for EA FC 26 — logged with full reproduction steps, severity and platform details
# EA FC 26 Bug Reports
### QA Portfolio — Arbaz Khan

Structured bug reports logged during independent 
gameplay testing of EA FC 26.

---

## Bug 1 — Pro Clubs Server Connection Error
**Platform:** PlayStation 5
**Severity:** High
**Frequency:** Consistent

**Steps to Reproduce:**
1. Launch EA FC 26
2. Navigate to Pro Clubs mode
3. Select Join or Create a Club
4. Attempt to connect

**Expected:** Connects to lobby successfully
**Actual:** EA server error — mode inaccessible

---

## Bug 2 — Controller Input Lag
**Platform:** PlayStation 5
**Severity:** High
**Frequency:** Consistent

**Steps to Reproduce:**
1. Start any online match
2. Press pass button (X)

**Expected:** Instant response
**Actual:** 1-2 second delay

---

## Bug 3 — Finesse Shot PlayStyle Weak Output
**Platform:** PlayStation 5
**Severity:** High
**Status:** Acknowledged by EA on Trello

**Steps to Reproduce:**
1. Select player with Finesse Shot PlayStyle
2. Get into shooting position
3. Press R1 + Circle

**Expected:** Fast accurate finesse shot
**Actual:** Shot noticeably slower and weaker



 ##4 Bug Report: Match Result Not Recorded After Online Game Completion

## 🎮 Game
EA Sports FC 26

## 🖥️ Platform
PS5 (Reproducible on PC as well)

## 🌐 Environment
- Online Mode (Ultimate Team – Division Rivals / Champions)
- Stable internet connection
- Occurs during peak server load

## ⚠️ Severity
High

## 🔥 Priority
High

## 📝 Description
After completing an online match, the game fails to record the match result due to a server disconnection error. The player is returned to the main menu without receiving rewards or progress updates.

## 🔁 Steps to Reproduce
1. Launch EA Sports FC 26
2. Navigate to Ultimate Team
3. Start an online match (Rivals/Champions)
4. Play the match until completion
5. Wait for post-match result screen

## ❌ Actual Result
- Error message: **"Lost connection to EA servers"** appears
- Match result is not saved
- Player is redirected to the main menu
- Rewards (coins, XP, rank progression) are not granted

## ✅ Expected Result
- Match result should be recorded successfully
- Player should receive rewards and progression updates
- No disconnection error should occur after match completion

## 🔄 Frequency
Intermittent (more frequent during peak hours)

## 📉 Impact
- Loss of player progress
- Negative user experience
- High frustration during competitive modes

## 🧠 Possible Cause (Analysis)
Potential server-side issue where match completion data fails to sync between client and backend services. This may be caused by session timeout or server overload during peak usage.

## 📎 Attachments (Suggested)
- not available 
