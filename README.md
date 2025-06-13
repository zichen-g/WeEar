# WeEar
BuildingBloCS June Hackathon Submission
>real-time ASL recognition (webcam) + speech_to_text pipeline

## quick start
```bash
# 1. Clone & enter
git clone <YOUR-REPO-URL>
cd <repo-folder>

# 2. Create + activate virtual-env (macOS / Linux)
python3 -m venv .venv
source .venv/bin/activate         # Windows: .venv\Scripts\activate

# 3. Install deps
#  – Apple-silicon Mac:
pip install tensorflow-macos==2.16.2 opencv-python numpy
#  – Intel Mac / Linux:
# pip install tensorflow==2.16.2 opencv-python numpy

# 4. Run the live ASL demo
python run_demo.py
# (first launch ~10 s; allow camera permission, press q to quit)



