# Dobbe AI – Adaptive Image Preprocessing for IOPA X-rays

## 🔍 Problem Understanding
The task involves improving AI-readiness of IOPA dental X-rays through adaptive preprocessing that adjusts to variable imaging conditions across clinics.

## 📊 Dataset
Simulated DICOM files with differing:
- Brightness
- Contrast
- Sharpness
- Noise

## ⚙️ Methodology
1. **Static pipeline**: Histogram Equalization
2. **Adaptive pipeline**:
   - CLAHE if contrast < 40
   - Sharpening if sharpness < 100
   - Denoising (NLM) if noise > 0.01

## 📈 Results
- Quantitative metrics: brightness, contrast, sharpness, noise
- Visual comparisons provided in `results/`

## 🚀 Future Work
- Deep learning-based preprocessing (U-Net)
- Automatic parameter tuning via ML regression


