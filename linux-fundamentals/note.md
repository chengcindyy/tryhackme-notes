# 🧠 
🗓️ Date: 2025-07-30  
🔗 Room URL: https://tryhackme.com/room/linuxfundamentalspart1
🏷️ Tags: 

---

## 🧭 Overview
Learn how to use linux

---

## 🛠 Tools & Commands Used



---

## 🔍 Key Observations / What I Learned
Linux Basic Command:
- echo: print something
- whoami: find the username
- ls: listing
- cd: change directory
- cat: concatenate是「concatenate（串接）」的縮寫，但最常見的用途是列印檔案的內容到終端機。
- pwd: print working directory

Linux Search Files Command:
- find -name: find the file
- grep: search the contents of files for specific values
- wc: word count

Output redirection: (輸出重定向操作符)
- &: Background Execution (當你在指令後面加上 &，這個指令就會在背景執行，你可以同時繼續在終端機執行其他操作，而不需要等它跑完。)
```
sleep 10 &
# 讓電腦「睡」10秒，但不會阻塞你的 terminal，你可以繼續打別的指令。
```

- &&: Execute second command only if the first succeeds (條件式執行: 這是「邏輯 AND 運算符」的意思，只有當前一個指令成功（exit code 為 0），才會繼續執行下一個。)
```
mkdir myfolder && cd myfolder
# 如果 mkdir myfolder 成功了，才接著執行 cd myfolder
# 如果 myfolder 已經存在，mkdir 會失敗（exit code ≠ 0），那 cd myfolder 就不會被執行。
```

- ||: logical OR
```
mkdir myfolder || echo "建立資料夾失敗"
# 如果 mkdir myfolder 失敗，就顯示錯誤訊息。

```

- >: overwrite
```
echo hi > welcome  # 會清空 welcome，再寫入 hi
echo hello >> welcome  # 不會清空，只是在最後再加一行 hello
```

- >>: append content to last line (追加輸出到檔案)
```
echo [內容] >> [檔案名稱]
echo hello >> welcome

Means append hello to welcome file
```

---

## 🖼️ (Optional) Screenshot or Network Diagram


---

## ⚠ Disclaimer

These notes are for personal learning purposes. No answers or flags are shared. All tasks are completed by me and any observations are based on legal, sandboxed exercises.

