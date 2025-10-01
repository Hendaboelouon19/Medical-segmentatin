# Medical-segmentatin
Medical image segmentation and 3D visualization for Liver, Kidney, and Lungs using AI models (MedSAM, TotalSegmentator, U-nest ). Includes evaluation metrics (Dice, IoU, Hausdorff) and interactive PyVista GUI for 2D/3D analysis
README.md

# 🧬 Medical Segmentation Project

Medical image segmentation and 3D visualization for Liver, Kidney, and Lungs using AI models (**MedSAM, TotalSegmentator, U-Nest**).  
Includes evaluation metrics (**Dice, IoU, Hausdorff**) and an interactive GUI with PyVista + PyQt5 for 2D/3D analysis.

---

## 🚀 Features
- Segmentation with multiple models:
  - MedSAM (fast, flexible medical SAM)
  - U-Nest (nested skip connections, high accuracy)
  - TotalSegmentator (whole-body CT, >100 structures)
- Supported Organs:
  - Liver (whole + 8 Couinaud segments)
  - Kidney (left/right, 3 subparts: cortex, medulla, pelvis)
  - Lungs (5 lobes)
- Evaluation:
  - Dice, IoU, Hausdorff Distance
- Visualization:
  - 2D overlays
  - 3D interactive rendering with color/opacity toggles

---

---

## ⚙️ Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/Hendaboeloun19/Medical-segmentation.git
   cd Medical-segmentation

pip install -r requirements.txt

📊 Results
 • Liver segmentation (8 Couinaud segments in 3D)
 • Kidney segmentation (cortex, medulla, pelvis)
 • Lung segmentation (all 5 lobes visualized interactively)

👩‍⚕️ Team

Developed by Biomedical Engineering students @ Cairo University presented by Malak osama , Hend aboelouon , Hadeel Amin , suty fady .
