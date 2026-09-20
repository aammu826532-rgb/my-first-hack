# Day 03 - Linux Modules | TryHackMe | 100 Days of Hacking 🔥

*Date:* 20 Sep 2026
*Room:* Linux Modules (https://tryhackme.com/room/linuxmodules)
*Status:* 100% Completed ✅
*Tasks:* 14/14

---

### 🚀 What I Completed

- [x] Task 1-12 - Linux Basics, awk, sed, xargs, sort, uniq, curl, wget, xxd etc.
- [x] Task 13 - Other Useful Modules
- [x] Task 14 - Is it night yet? - Final Flag

### 🧠 Key Learnings - Task 13

| Question | Answer |
|----------|--------|
| systemctl experiment? | Wrong |
| Import PGP key | gpg --import key.gpg |
| netstat alternative? | ss -tulpn = Socket Statistics |
| Fix broken terminal? | reset |

### 🏁 Final Task - Task 14

- File Message: Y0u. C4n. D0. 1t.
- Decoded: You Can Do It!
- Flag: F - Press F to pay respect

### 💻 Commands Mastered Today

```bash
gpg --import key.gpg
ss -tulpn
reset
awk '{print $1}'
sed 's/old/new/'
xargs -I {}
sort | uniq
curl -O https://...
wget https://...
xxd file.txt


👉 [View Day 03 Post - 14/14 Tasks Completed](https://www.linkedin.com/posts/bhagya-bhagya-321983421_100daysofhacking-tryhackme-linux-ugcPost-7507419958524653568-d689)

📸 Screenshot: proof.png attached above
🔥 Streak: 3 Days | 296 Points
