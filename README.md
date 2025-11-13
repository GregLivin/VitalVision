# VitalVision – Contactless Monitoring of Temperature, Heart Rate, Mood, and Trends

### Student: Gregory Livingston Jr  
### Course: ITAI 1378 – Computer Vision & AI  
### Tier: Tier 2 (Multimodal Vision System)

---

## 🔍 Project Overview
VitalVision is a computer vision prototype that estimates:

- Contactless temperature category (normal vs possible fever)
- Heart rate (BPM) from face video using rPPG
- Mood classification from facial expressions
- Trend tracking for temperature, heart rate, and mood over time

This is an educational demo only and **not a medical device**.

---

## 🧠 Technical Approach

### Temperature Classification
- Dataset: Public thermal fever screening images
- Model: ResNet18 or small CNN
- Output: Normal / Possible Fever

### Heart Rate Estimation (rPPG)
- Detect face with OpenCV
- Extract green-channel intensity over time from forehead region
- Apply FFT or peak detection to estimate BPM

### Mood Classification
- Dataset: FER-style emotion dataset
- Labels: Happy, Neutral, Distressed
- Model: MobileNet or ResNet

### Trend Tracking
- Log each reading with timestamp to CSV
- Plot temperature, BPM, and mood state over time with Matplotlib

---

## 📊 Success Metrics
- Temperature classification accuracy ≥ 85%
- Emotion classification accuracy ≥ 80%
- Heart rate estimation error ≤ ±15 BPM

---

## 📅 Week-by-Week Plan

**Week 10** — Collect datasets & set up repo  
**Week 11** — Train temperature + mood models  
**Week 12** — Implement rPPG heart-rate estimation  
**Week 13** — Build trend tracking & charts  
**Week 14** — Create demo + finalize code  
**Week 15** — Final presentation  

---

## 📂 Repository Structure

