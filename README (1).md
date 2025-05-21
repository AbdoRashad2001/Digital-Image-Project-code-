
# Python-Based Image Processing Project

## 🎯 Project Overview
This project demonstrates fundamental image processing techniques using Python and OpenCV. It processes a batch of images through a modular pipeline consisting of color adjustment, filtering, edge detection, noise reduction, and simple feature extraction.

---

## 🧩 Techniques Implemented
- **Color Adjustment**: Brightness and contrast modification
- **Filtering**: Gaussian Blur for detail reduction
- **Edge Detection**: Canny Edge Detector
- **Noise Reduction**: Non-local Means Denoising
- **Feature Extraction**: Simple mean color features (B, G, R)

---

## 📂 Input/Output Handling
- **Supported formats**: `.jpg`, `.png`, `.tif`
- **Error Handling**: Skips unreadable or unsupported files
- **Output Naming**: Processed images saved with suffixes (e.g., `_blurred`, `_edges`, `_denoised`)

---

## 🚀 How to Run

1. Place your zipped image folder (e.g., `MMIL.zip`) in the working directory.
2. Extract the zip so images are inside `unzipped/` and in a subfolder.
3. Run `main.py`:

```bash
python main.py
```

The script will:
- Process all images
- Save results in `processed/`
- Print and display example before/after image
- Print simple feature descriptors

---

## 📁 Project Structure

```
project/
│
├── main.py               # Main script with all processing functions
├── README.md             # Project documentation
├── MMIL.zip              # Your dataset (uploaded separately)
├── unzipped/             # Unzipped images (after extraction)
└── processed/            # Output images (created automatically)
```

---

## ⚙️ Dependencies

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- Matplotlib

Install with:

```bash
pip install opencv-python numpy matplotlib
```

---

## 📝 Notes

- This project uses simple feature extraction. For classification-ready output, further processing or integration with ML models is needed.
- The image display will only work in environments with GUI or notebook (e.g., Jupyter, Colab).

