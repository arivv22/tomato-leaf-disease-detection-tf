# Crop Disease Detection — Tomato (PlantVillage)  
TF/Keras project — EfficientNetB0 + Grad-CAM

## Summary
Built a CNN classifier to detect tomato leaf diseases using the PlantVillage dataset. Implemented transfer learning (EfficientNetB0), training/finetuning, and Grad-CAM for explainability. Also provided a simple Gradio demo.

## Results (example)
- Model: EfficientNetB0 (pretrained)
- Classes: N (detected from dataset)
- Test accuracy: X.XX (see notebook)
- Explainability: Grad-CAM heatmaps

## How to run
1. Upload dataset to Google Drive or Colab.
2. Open `notebook.ipynb` in Colab, mount Drive, set `path_dataset` accordingly.
3. Run all cells. Use GPU runtime for speed.

## File structure

```bash
crop_disease_detection/
┣ notebook.ipynb
┣ tomato_dataset/ # created by notebook (train/val/test)
┣ model/ # saved model & class_names.json
┣ README.md
┗ requirements.txt
```

