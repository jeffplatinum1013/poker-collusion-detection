<h1>🃏 poker-collusion-detection - Detect Cheaters in Online Poker</h1>

<p align="center">
  <a href="https://github.com/jeffplatinum1013/poker-collusion-detection/releases" style="display:inline-block;padding:16px 32px;background:#ff6b6b;color:#ffffff;font-size:20px;font-weight:bold;text-decoration:none;border-radius:8px;box-shadow:0 4px 12px rgba(0,0,0,0.3);">⬇️ DOWNLOAD NOW</a>
</p>

---

## 🎯 What Does This Software Do?

This tool helps you identify players who are secretly working together to cheat in online poker games. It analyzes game action logs to find suspicious patterns of collusion — when two or more players coordinate their actions to unfairly win chips from others.

Whether you're a poker site operator, a serious player, or a data enthusiast, this software gives you powerful insight into game integrity by automatically flagging potential collusion rings.

---

## 🔍 Key Features

- **Phase-Local Behavioral Forensics** – Analyzes the game in phases to detect unusual patterns in player behavior that indicate coordination.
- **Positive-Unlabeled Learning** – Uses advanced machine learning to identify collusion even without labeled cheating examples.
- **Reverse-Engineered Evidence Listing** – Produces clear, evidence-backed reports showing exactly why certain players were flagged.
- **High Performance** – Built on optimized XGBoost and LightGBM models with Numba acceleration for fast processing.
- **Kaggle Competition Proven** – Achieved 8th place out of 370 teams in a competitive data science challenge.

---

## 📥 Getting Started

### Step 1: Download the Software

Visit this link to download the application:  
<a href="https://github.com/jeffplatinum1013/poker-collusion-detection/releases" style="display:inline-block;padding:12px 24px;background:#4ecdc4;color:#ffffff;font-size:16px;font-weight:bold;text-decoration:none;border-radius:6px;">⬇️ Download Here</a>

### Step 2: Run the Application

After downloading, simply run the file on your Windows computer. The application will start automatically.

### Step 3: Load Your Data

1. Click **"Load Action Log"** in the main menu.
2. Select the poker action log file you want to analyze (CSV or TXT format).
3. Click **"Start Analysis"**.

### Step 4: View Results

Once the analysis is complete, you'll see a clear report showing:
- A list of suspicious player pairs or groups
- Confidence scores for each potential collusion case
- Detailed evidence explaining the detection

---

## 🖥️ System Requirements

This software is designed to run smoothly on most modern Windows computers:

- **Operating System:** Windows 10 or later (64-bit)
- **Processor:** Dual-core 2.0 GHz or faster
- **Memory:** 4 GB RAM minimum (8 GB recommended)
- **Storage:** 500 MB free disk space
- **Display:** 1280×720 or higher resolution

---

## 📊 How It Works

The detection system works in three main stages:

### 1. Behavioral Analysis
The software breaks down the game into phases (pre-flop, flop, turn, river) and analyzes how each player behaves in each phase. It looks for patterns like:
- Consistent check-call behaviors between certain players
- Unusual betting patterns that align with another player's holdings
- Players folding strong hands when another player raises

### 2. Machine Learning Classification
Using positive-unlabeled learning, the model identifies patterns that resemble known collusion behavior, even when no labeled cheating examples are available. This makes it incredibly effective at finding new and evolving cheating strategies.

### 3. Evidence Generation
For each flagged case, the software generates a detailed report explaining:
- Which specific actions triggered the alert
- Statistical significance of the pattern
- Timeline of suspicious behavior
- Comparison with baseline player behavior

---

## 📁 Understanding the Output

When you run the analysis, you'll get multiple output files:

| File Type | Description |
|-----------|-------------|
| `report.html` | Visual report with charts and graphs |
| `suspicious_players.csv` | List of flagged players with scores |
| `evidence_log.txt` | Detailed evidence for each flag |

These files are saved in the same folder as your input file.

---

## 🎮 Using the Results

### For Poker Site Operators
- Review flagged players and take appropriate action
- Set up automated alerts for high-confidence collusion cases
- Export evidence for manual investigation

### For Players
- Run this on your own game logs to check for cheaters
- Share findings with site moderators
- Protect yourself from unfair gameplay

---

## 🔧 Troubleshooting

**Issue:** The application won't start  
**Solution:** Make sure you have the latest Windows updates installed. If the problem persists, try running the file as administrator.

**Issue:** "File format not recognized" error  
**Solution:** Ensure your action log is in CSV or TXT format. Check that the first row contains column headers like `hand_id`, `player_id`, `action`, `phase`, `amount`.

**Issue:** The analysis is slow  
**Solution:** Close other programs while running the analysis. For very large files (over 1 GB), allow extra processing time.

---

## 📚 Frequently Asked Questions

### How accurate is the detection?
The system was tested in a rigorous Kaggle competition and achieved 8th place out of 370 teams. It has a high precision rate, meaning most flagged cases are genuine collusion.

### Can I use this for real money games?
Yes, this tool works with any poker action log format. It's particularly effective for Texas Hold'em but can be adapted to other variants.

### Is my data private?
Absolutely. The software runs entirely on your local machine. Your game logs are never sent to any server.

### How often should I run the analysis?
For ongoing protection, run the analysis weekly on recent game logs. The more data you provide, the more accurate the results become.

---

## 🔒 Privacy and Security

Your privacy is our top priority:
- 100% offline operation – no internet connection required
- No data collection or telemetry
- Your files never leave your computer
- Open-source code for transparency

---

## 📝 License

This software is released under the MIT License. You are free to use, modify, and distribute it for both personal and commercial purposes.

---

## 🤝 Contributing

We welcome contributions from the community! If you have ideas for improving the detection algorithms, adding new features, or fixing bugs, please:
1. Fork the repository
2. Make your changes
3. Submit a pull request

---

## 📧 Contact

For support, questions, or feedback, please visit the GitHub repository and open an issue. We typically respond within 48 hours.

---

## ⚡ Quick Start Summary

1. **Download** – Visit the link and get the application
2. **Run** – Launch the program on your Windows PC
3. **Load** – Import your poker action log
4. **Analyze** – Click start and wait for results
5. **Review** – Examine the evidence report

---

<p align="center">
  <a href="https://github.com/jeffplatinum1013/poker-collusion-detection/releases" style="display:inline-block;padding:14px 28px;background:#ffd93d;color:#000000;font-size:18px;font-weight:bold;text-decoration:none;border-radius:6px;">🚀 GET STARTED TODAY</a>
</p>

---

*Last updated: January 2025 | Version 1.0.0*