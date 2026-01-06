<div align="center">
<h1>🌌 Welcome to Corvette YouTube Downloader 🚀</h1>
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&size=32&pause=1000&color=BB86FC&center=true&vCenter=true&width=600&lines=Corvette+YouTube+Downloader;Fast+%26+Simple+Audio+%26+Video+Download;Crafting+the+Future+with+Code+and+Flair" alt="Typing SVG" />
</div>

---

<div align="center">
  <h2>👾 About zr1-ytdl</h2>
  <p><strong>zr1-ytdl</strong> is a Node.js package to download YouTube videos and audio easily, fetch transcripts, and search YouTube content programmatically. Powered by <strong>Corvette</strong> and crafted with love for developers.</p>
</div>

---

## 🔧 Installation

```bash
npm install zr1-ytdl
```

---

## 📺 Usage Examples

### 1️⃣ YouTube Search

**JavaScript:**
```javascript
const { search } = require('zr1-ytdl');

search('Corvette coding tutorial').then(results => {
  console.log(results);
});
```

**Python:**
```python
import subprocess, json

command = 'node -e "const { search } = require(\'zr1-ytdl\'); search(\'Corvette coding tutorial\').then(console.log)"'
result = subprocess.getoutput(command)
data = json.loads(result)
print(data)
```

---

### 2️⃣ Download YouTube Audio (MP3) with Random Quality

**JavaScript:**
```javascript
const { ytmp3 } = require('zr1-ytdl');

ytmp3('https://youtube.com/watch?v=VIDEO_ID').then(console.log);
```

**Python:**
```python
import subprocess, json

command = 'node -e "const { ytmp3 } = require(\'zr1-ytdl\'); ytmp3(\'https://youtube.com/watch?v=VIDEO_ID\').then(console.log)"'
result = subprocess.getoutput(command)
data = json.loads(result)
print(data)
```

---

### 3️⃣ Download YouTube Audio (MP3) with Specific Quality

**JavaScript:**
```javascript
const { ytmp3 } = require('zr1-ytdl');

ytmp3('https://youtube.com/watch?v=VIDEO_ID', 128).then(console.log);
```

**Python:**
```python
import subprocess, json

command = 'node -e "const { ytmp3 } = require(\'zr1-ytdl\'); ytmp3(\'https://youtube.com/watch?v=VIDEO_ID\', 128).then(console.log)"'
result = subprocess.getoutput(command)
data = json.loads(result)
print(data)
```

---

### 4️⃣ Download YouTube Video (MP4) with Random Quality

**JavaScript:**
```javascript
const { ytmp4 } = require('zr1-ytdl');

ytmp4('https://youtube.com/watch?v=VIDEO_ID').then(console.log);
```

**Python:**
```python
import subprocess, json

command = 'node -e "const { ytmp4 } = require(\'zr1-ytdl\'); ytmp4(\'https://youtube.com/watch?v=VIDEO_ID\').then(console.log)"'
result = subprocess.getoutput(command)
data = json.loads(result)
print(data)
```

---

### 5️⃣ Download YouTube Video (MP4) with Specific Resolution

**JavaScript:**
```javascript
const { ytmp4 } = require('zr1-ytdl');

ytmp4('https://youtube.com/watch?v=VIDEO_ID', 360).then(console.log);
```

**Python:**
```python
import subprocess, json

command = 'node -e "const { ytmp4 } = require(\'zr1-ytdl\'); ytmp4(\'https://youtube.com/watch?v=VIDEO_ID\', 360).then(console.log)"'
result = subprocess.getoutput(command)
data = json.loads(result)
print(data)
```

---

## ⚡ Features

- Download YouTube audio in multiple qualities (32kbps – 320kbps)  
- Download YouTube video in multiple resolutions (144p – 1440p)  
- Fetch transcripts and AI summaries of YouTube videos  
- Search YouTube programmatically  

---

## 🛠️ Developed By Corvette

<div align="center">
  <p><strong>Corvette</strong> | Full-Stack Developer & Bot Maestro</p>
  <p>🌍 Location: Ratnapura/Sabaragamuwa/Sri Lanka</p>
  <p>🌱 Exploring: AI, Web3, Next.js, immersive UI/UX</p>
  <p>🎯 Goal: Build code that inspires and captivates</p>
</div>

