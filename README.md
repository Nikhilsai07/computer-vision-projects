# Computer Vision Projects

OpenCV face detection and a face-recognition example.

- `src/` — Python scripts
- `datasets/` — Face images and Haar cascade XML classifier

## Setup
```bash
python -m venv .venv
# Windows: .venv\\Scripts\\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
```
Run scripts from this folder so image and cascade paths resolve. `OpenCVFace3.py` uses the default webcam; face recognition loads Olivetti Faces via scikit-learn and may need internet access.