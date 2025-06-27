# Re-identification in Single Feed

This project focuses on consistent object (player/ball) tracking using YOLO and ByteTrack in a single video feed, tailored for sports applications such as football. It leverages detection, tracking, and annotation tools to maintain consistent IDs across frames.

---

## 🎯 Objective

To detect and track players and the ball in a football match video using computer vision techniques. The system ensures consistent identity (re-ID) assignment for each player throughout the video.

---

## 📂 Project Structure

├── best.pt # YOLOv8 model weights (not included due to size)
link:https://drive.google.com/file/d/1CZNvhRruEGgcl30uESCnHI1Q4ZYpfT4H/view?usp=sharing
├── 15sec_input_720p.mp4 # Input video (example)
├── 15sec_output_720p.mp4 # Output with annotated tracking
├── notebook.ipynb # Colab notebook (detection + tracking)
├── utils/ # (Optional) helper scripts



## 🚀 Features

- ✅ YOLOv8-based player and ball detection
- ✅ ByteTrack for consistent object tracking
- ✅ Supervision for drawing annotations
- ✅ ID consistency across frames (re-identification)
- ✅ Ellipse, triangle, and label visual overlays




## 🔧 Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/charan1814/Re-identification-in-single-feed.git
   cd Re-identification-in-single-feed

2.  ## Install Dependencies
   !pip install ultralytics supervision opencv-python tqdm

3.  ## Add your YOLOv8 weights

   Upload best.pt to the repo root or modify the path in the notebook.

## Input Frame                                                  |
![Screenshot (59)](https://github.com/user-attachments/assets/453d97bf-62f0-4f09-80be-d88a2eba99c9)
                                        
## Output Frame
 ![Screenshot (58)](https://github.com/user-attachments/assets/e6c979c1-2aeb-42ea-8576-d26e5d356c4d)



## Resources
YOLOv8 Docs

ByteTrack

Supervision

## Acknowledgments
Ultralytics YOLOv8

Supervision library

## Author
Charan1814 – GitHub

ByteTrac




   
