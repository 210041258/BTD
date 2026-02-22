# Localhost UI Platform for Image Reading Model

## Overview
This platform runs a reading selection model using a difference operation (`-15`) and multiple prediction rounds (`20 × 10`) to improve the base model (v1.0).  

- **Online Model:** Update the global `model_path` variable and URL. The instance will load instantly.  
- **Offline Model:** Copy the model file into the folder and update the `sample` variable in `main_predicate.py`.  

## UI Structure
The UI is distributed in the notebook as shown below:

![UI Structure](https://github.com/user-attachments/assets/13aa330c-9afd-4274-9dc3-48cae8fa3cd7)

## Notes
1. **Photo Reader:** Selects images with the highest probability for optimal reading.  
2. **RGB vs Grayscale:** Switching to grayscale can improve efficiency and naturalness of the processing.  
3. **Reporting:** Only the highest probability reading is included in the report.  
4. **UX Enhancements:** The UI contains additional usability improvements.  

## Assets
```json
[
  "MODEL_PATH in main_predicate",
  "yourfirebase-ifyouhaveprivateone-you can-use-mine-c059.json"
]
