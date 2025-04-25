# 🚗 Nexar Dashcam Crash Prediction Challenge

## Project Overview
This project develops a deep learning model to predict vehicle collisions from dashcam footage, aiming to enhance road safety through early accident detection. The solution analyzes video sequences to identify imminent collisions and near-misses, providing critical reaction time for advanced driver assistance systems (ADAS).

## Dataset Description

### Key Characteristics:
- **1500 training videos** (40 sec each, 720p@30fps)
  - 750 collision/near-miss cases (positive class)
  - 750 normal driving sequences (negative class)
- **1344 test videos** (10 sec each)
- **Annotations**:
  - Event time (collision moment)
  - Alert time (earliest predictable moment)
  - Time-to-accident intervals (500ms/1000ms/1500ms)
