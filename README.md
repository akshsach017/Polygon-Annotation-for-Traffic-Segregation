# 🎥 Polygon Annotation on Video Datasets

This project processes video datasets to generate **polygon-based annotations** for object detection tasks using `Detectron2`. It supports classes like **person**, **bicycle**, and **car**, and generates annotated snapshots for efficient visual verification and downstream use.

---

## 🚀 Features

- Frame-wise video segmentation and polygon annotation  
- Supports multiple object classes (person, bicycle, car)  
- Generates overlay visualizations for quick validation  
- Structured outputs using OpenCV and Pandas  

---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/polygon-video-annotation.git
cd polygon-video-annotation
pip install -r requirements.txt
```

---

## 🧪 Usage

```bash
python annotate_video.py --video_path ./data/video.mp4 --output_dir ./outputs
```

**Arguments:**

- `--video_path`: Path to the input video file  
- `--output_dir`: Directory where annotated frames and JSON data will be saved  

---

## 📦 Sample Output

- `/outputs/annotated_frames/` – PNG images with overlaid polygons  
- `/outputs/annotations.json` – Frame-wise object detection with polygon points and class labels  

---

## 💡 Use Cases

- Automated object tracking for surveillance or mobility solutions  
- Preprocessing for custom object detection datasets  
- Visual quality check in annotation pipelines  
- Smart city and traffic monitoring applications  

---

## 🔮 Future Improvements

- Add support for more COCO classes and custom classes  
- Integrate active learning feedback to prioritize difficult frames  
- Improve mask accuracy using ensemble or hybrid models  
- Create an interactive UI for annotation review and correction  
