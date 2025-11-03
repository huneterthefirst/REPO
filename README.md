# 🧩 R.E.P.O. Monster Codename Reference

Welcome to the **R.E.P.O. Codename Mapping Project** — a community-driven reference for modders, dataminers, and curious players who want to peek behind the curtain of the game’s monsters.  

This repo collects **internal codenames** and their corresponding **in‑game monsters**, along with tiers and known sub‑components (like animation controllers, directors, and particle systems). If you’re building mods, debugging, or just exploring the game’s guts, this is your one‑stop cheat sheet.  

---

## 🎯 Purpose
- Help modders quickly find the **codename** for any monster they want to tweak or reference.  
- Document **all known namespace references** (e.g., EnemySpinnyAnim, EnemyBangBomb) so you don’t have to dig through the codebase.  
- Provide a **tier‑sorted monster list** for clarity.  

---

## 📖 How to Use
Each monster entry is structured like this:

# Monster Name  
## Codename: EnemyX  
### Tier: #  
- EnemyX  
- EnemyXAnim  
- EnemyXDirector  
- EnemyXParticle  

- **Monster Name** = what you see in‑game.  
- **Codename** = what the prefab/script is called internally.  
- **Tier** = the danger level (1 = common, 2 = advanced, 3 = elite).  
- **References** = all known sub‑components tied to that monster.  

---

## ✅ Why This Matters
R.E.P.O. uses quirky internal names (Spinny, Oogly, Elsa) that don’t always match the in‑game monster names. Without a map, modding can feel like guesswork. This repo bridges that gap so you can:  
- Spawn monsters directly by codename.  
- Hook into their animation or particle systems.  
- Build custom encounters or tweak AI behavior.  

---

## 🕷️ Example Highlight
- **Loom** → Codename: EnemyOogly  
  - Tier: 3  
  - References: EnemyOogly (plus jaw/hand/teleport systems in code)  
  - Fun fact: Loom’s jaw animation is cosmetic — its real attack is the **hand clap shockwave**.  

---

## 🚀 Contributing
Found a missing codename, reference, or behavior? Open a PR or issue! This project thrives on community knowledge.  

---

## ⚠️ Disclaimer
This repo is **for educational and modding purposes only**. All game assets and code belong to their respective developers.  
Any mod's that are linked here are most likely mine and please if you use it or sample it give me some credit - Null (Yes that's my nickname)
