# Azure AI Custom Vision Demo

This is another no-code image classification project using **Azure AI Custom Vision**. It explores how machine learning can recognize tagged objects from curated image datasets.

## What I Did

- Created a Custom Vision project in the Azure portal
- Uploaded images across 2 tags:
  - `Magic Item`
  - `Non-Magic`
- Trained a classifier with a small dataset (5 images per tag)
- Achieved 50% accuracy on initial training (and proud of it!)

## 🗂Repo Contents

| Folder     | Description                                  |
|------------|----------------------------------------------|
| `dataset/` | Input images for training across both tags   |
| `results/` | Screenshots and metrics from training output |

## Training Metrics

Quick training was completed using the free tier (`F0`).  
The precision, recall, and probability scores are stored in `results/performance.json`.

> The project uses a small sample for experimentation. Accuracy will improve with larger, balanced datasets.

## Source Image Safety

All image uploads used are safe for public sharing and do not contain personal data. Tags are poetic, playful, and intended for exploratory AI testing only.

## Next Steps

- Add more images per tag
- Try multi-tag classification or object detection
- Possibly script training pipeline in Python or PowerShell

---

**License**: MIT  
**Created by**: [Sharmaine Erika](https://www.linkedin.com/in/your-link)
