# Automated Leaf Area Calculation using Segment Anything Model (SAM)

## Overview

This project estimates the leaf area of plant images using computer vision techniques and Meta's Segment Anything Model (SAM). The workflow automatically segments the target leaf, detects a reference calibration square, calculates pixel areas, and estimates the actual leaf area using pixel-to-area conversion.

The notebook demonstrates an automated approach for leaf area measurement, reducing the need for manual measurements in plant phenotyping applications.

---

## Features

- Automatic leaf segmentation using Meta Segment Anything Model (SAM)
- Reference square detection using OpenCV
- Pixel-based leaf area calculation
- Conversion of pixel measurements into real-world area
- Visualization of segmented masks
- Supports multiple plant images

---

## Technologies Used

- Python
- Google Colab
- OpenCV
- PyTorch
- Segment Anything Model (SAM)
- NumPy
- Matplotlib

---

## Workflow

1. Upload plant image.
2. Load the Segment Anything Model (SAM).
3. Generate segmentation masks for the plant leaf.
4. Detect the calibration square using OpenCV.
5. Calculate:
   - Leaf pixels
   - Calibration square pixels
6. Convert pixel measurements into actual leaf area.
7. Display segmentation results and calculated area.

---

## Libraries

- OpenCV
- PyTorch
- Segment Anything
- NumPy
- Matplotlib

---

## Project Structure

```
Plant_Area/
│
├── Leaf_Areacalculation.ipynb
├── README.md
└── Sample Images
```

---

## Output

The notebook provides:

- Leaf segmentation mask
- Calibration square mask
- Leaf pixel count
- Calibration square pixel count
- Estimated leaf area

---

## Applications

- Plant phenotyping
- Precision agriculture
- Smart farming
- Greenhouse monitoring
- Agricultural research

---

## Future Improvements

- Process multiple images automatically.
- Develop a web-based interface.
- Integrate Raspberry Pi camera for real-time image acquisition.
- Improve segmentation for overlapping leaves.
- Deploy the workflow on edge devices.

---

## Author

**Harbans Kaur**

MCA, Thapar Institute of Engineering & Technology

LinkedIn: https://linkedin.com/in/harbans-kaur-76528a24a
