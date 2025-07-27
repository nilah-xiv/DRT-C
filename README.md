# 🎲 DRTC - Death Roll Tournament  
### *Challonge-Integrated Bracket Plugin for FFXIV*
### *Now with an authorized user list!*

---

## ⚙ Prerequisites

- 🟣 **XIVLauncher / Dalamud**
- 🧪 **Challonge Account** (Free)  
  👉 Grab your API Key from [https://challonge.com/settings/developer](https://challonge.com/settings/developer)

---

### Enable Experimental Plugins  
In Dalamud, go to `Settings → Experimental` and add this repo URL:

```plaintext
https://raw.githubusercontent.com/nilah-xiv/DRT-C/main/repo.json
```


## 🧾 Parsing Users from Discord

1. **Copy** and **paste** entries from Discord into the plugin.
2. Open the plugin with `/drtc`.
3. Click **“Paste from Clipboard”** then **“Parse Entries.”**
4. The parser:
   - Removes timestamps, tags, and noise.
   - Can extract multiple entries per post.
5. ✨ **Manually verify or adjust** entries as needed for best results.

> 💡 You can edit the parsed list and re-parse as many times as you need!



**Example:**  
![Parsing Screenshot](https://github.com/user-attachments/assets/1285d1dc-70bc-4e32-99e4-e2c5e8b9b958)

---

## 🏁 Starting a Tournament

Once you’re happy with the user list:

1. Scroll down and click **“Create Tournament.”**
2. Wait ~3–10 seconds for Challonge to generate the bracket.
3. The bracket will:
   - Display rounds
   - Let you expand round views
   - Handle byes and randomization automatically

**Screenshots:**
- Userlist to Bracket  
  ![Create Screenshot](https://github.com/user-attachments/assets/bc4e4063-159a-4929-88d4-a6b76f81828b)
- Tournament Result View  
  ![Bracket Screenshot](https://github.com/user-attachments/assets/13d570d1-4f78-4a1a-ac41-622afeede7ce)
- Bye Logic (e.g., No `Me vs TBD`)  
  ![Bye Screenshot](https://github.com/user-attachments/assets/96f2c391-96d6-4181-9b3b-e3d1a88af472)

---

## 🧵 Plugin Commands

| Command            | Description                         |
|--------------------|-------------------------------------|
| `/drtc`            | Opens the Main Plugin UI            |
| `/drtc bracket`    | Opens Bracket Window (if available) |

---

## 💬 Notes

> Parsing will never be 100% perfect due to Discord’s formatting. Manual adjustments are expected and encouraged to ensure clean brackets.
