# Netflix Rating Buddy 🎬⭐  
**Chrome Extension for Streaming Platforms**  

Netflix Rating Buddy is a Chrome extension that overlays **real-time IMDb ratings** on movies and shows while browsing **Netflix** and **Prime Video**. It fetches ratings from the IMDb API, matches titles using fuzzy algorithms, and displays a clean overlay directly on each title card.  

---

## 🚀 Features  
- ✅ **Platform Support** – Works on Netflix and Prime Video.  
- ✅ **Real-Time IMDb Ratings** – Displays score + vote count on each title card.  
- ✅ **Smart Title Extraction** – Uses DOM parsing and platform-specific selectors for accurate detection.  
- ✅ **Fuzzy Matching Engine** – Matches streaming titles to IMDb results using **Levenshtein, Jaro, substring, and word-overlap** similarity (>90% accuracy).  
- ✅ **Optimized API Service** – Request queuing, caching (30-day expiry), and rate-limiting to avoid redundant calls.  
- ✅ **Custom UI Overlays** – Styled with CSS animations for a seamless, responsive, non-intrusive experience.  

---

## 🛠 Tech Stack  
- **JavaScript (ES6+)**  
- **Chrome Extensions API (Manifest V3)**  
- **IMDb API** (`imdbapi.dev`)  
- **CSS3** (custom overlays with animations)  
- **Fuzzy String Matching Algorithms** (Levenshtein distance, Jaro similarity, etc.)  

---

## 📦 Installation  

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/Netflix-Rating-Buddy.git
   cd Netflix-Rating-Buddy
   
## 🚀 Load the Extension in Chrome  

1. Open Chrome and go to: chrome://extensions/
2. Enable **Developer mode** (toggle in the top-right corner).  
3. Click **Load unpacked**.  
4. Select the **project folder** (the one containing `manifest.json`).

## 📸 Screenshots  
<img width="2532" height="830" alt="Screenshot 2025-09-21 195640" src="https://github.com/user-attachments/assets/91ea98d9-3b65-46e9-ac22-e84202e77df0" />



