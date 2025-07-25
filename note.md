# 🧠 [Room Name]
🗓️ Date: YYYY-MM-DD  
🔗 Room URL: https://tryhackme.com/room/room-name  
🏷️ Tags: [Reconnaissance], [Blue Team], [Offensive Security], [SIEM], etc.

---

## 🧭 Overview
A short summary of what this room is about, including your learning goals.

> Example:  
> This room introduces basic directory enumeration and brute-force techniques using gobuster. It simulates a safe environment to explore hidden web paths.

---

## 🛠 Tools & Commands Used

| Tool | Purpose | Sample Command |
|------|---------|----------------|
| gobuster | Directory brute-force | `gobuster dir -u http://target -w wordlist.txt` |
| nmap | Network scanning | `nmap -sV targetIP` |
| curl | Quick HTTP testing | `curl -I http://target/path` |

🧑‍💻 *Feel free to include only relevant tools for this room.*

---

## 🔍 Key Observations / What I Learned

- [ ] How to use gobuster to discover hidden web directories
- [ ] Importance of HTTP status codes (e.g., 200 vs 301)
- [ ] How attackers might leverage hidden endpoints
- [ ] Why directory enumeration matters in early recon

✍ Example insight:
> One of the discovered directories returned a 200 OK response. While I won't detail the exact path or function here, it led to functionality that was key to completing the challenge.

---

## 💡 Reflections / Next Steps

- Would like to try using different wordlists (e.g., SecLists)
- Need to better understand how HTTP redirection (301/302) affects scanning
- Want to explore how gobuster compares to ffuf in similar use cases

---

## 🖼️ (Optional) Screenshot or Network Diagram

> Place here any screenshot that helps you remember what happened (mask any solution).

---

## ⚠ Disclaimer

These notes are for personal learning purposes. No answers or flags are shared. All tasks are completed by me and any observations are based on legal, sandboxed exercises.

