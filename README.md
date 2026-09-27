# 🥭 Precision Fruit Counting & Yield Estimation with YOLOv10

**Computer vision platform for fruit detection, counting, and revenue estimation — comparing YOLOv9, YOLOv10, and Faster R-CNN.**

Team project (4 members) — EPITA MSc Data Science & Analytics.

---

## 🎯 What It Does

- **Detects and counts fruits** in orchard images using state-of-the-art object detection models
- **Estimates yield and revenue** by combining detection results with:
  - 🌦️ Live **weather data** (OpenWeatherMap API)
  - 💰 Live **market prices** (API-based)
- **Compares three model architectures** to identify the best trade-off between speed and accuracy

## 🤖 Models Compared
   Model | mAP | Speed | Notes |
 |---|---|---|---|
 | YOLOv9 | _TBD_ | _TBD_ | Baseline YOLO variant |
 | YOLOv10 | **0.88** | _TBD_ | Best overall — used in final pipeline |
 | Faster R-CNN | _TBD_ | _TBD_ | Two-stage detector comparison |

## 🛠 Tech Stack

- **Detection:** YOLOv9, YOLOv10, Faster R-CNN
- **Backend:** Python, FastAPI
- **Database:** PostgreSQL
- **APIs:** OpenWeatherMap, market price API
- **Deployment:** Docker

## 📁 Repository Structure

<!-- Adjust to match your actual folders -->
 | Folder | Description |
 |---|---|
 | `models/` | Model training scripts and weights |
 | `src/` | Detection & counting pipeline |
 | `api/` | FastAPI endpoints |
 | `db/` | PostgreSQL schema and queries |

## 🚀 Getting Started

```bash
# Clone
git clone https://github.com/Sreecharan-lagudu/YOLOV10.git
cd YOLOV10

# Run with Docker
docker-compose up
