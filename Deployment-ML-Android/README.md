
### Overview
- The APK contains an application integrated with **Google Firebase** for real-time database operations.  
- The app supports **general and specific item search** via the main tab at the top of the UI.  
- A **FAQ section** is included to refresh the database efficiently.  
- The UI is **under active development** and will be improved further.

## Prediction Branch (Firebase Real-Time Database)
The Firebase branch stores prediction results in **JSON format**. Each entry uses a unique ID as a child. Example structure:

```json
{
  "id": "10d51801-bf90-4d1f-b529-2ab776f7f1d5",
  "filename": "Tr-no_1040.jpg",
  "url": "https://pixeldrain.com/api/file/JX2wWJ7n",
  "analysis2": "Top Prediction: Notumor (32.36%) | Second Prediction: Glioma (26.94%) | Best Round: 1 of 1 | Avg Confidence Per Class: [0.26935407519340515, 0.26501986384391785, 0.32359829545021057, 0.14202778041362762]",
  "analysis3": "Top-1 Class: Notumor with confidence 32.36%. | Top-2 Class: Glioma with confidence 26.94%. | Prediction confidence across classes: [0.26935407519340515, 0.26501986384391785, 0.32359829545021057, 0.14202778041362762]. | Best result obtained in round 1 of 1.",
  "details": "Probability Spread: 0.0542 | Uncertainty Index: 1.3476 | Confidence Level: ❓ Very Low Confidence (<40%) - The model is unsure. Strongly consider manual review and further diagnostics. | Second Most Likely: Glioma (26.94%) | Clinical Considerations: • No immediate intervention needed. • Recommend routine follow-up if clinically indicated. • Consider alternative diagnoses if symptoms persist. ⚠️ Additional Considerations: • Additional imaging (contrast-enhanced MRI). • Second opinion from neuroradiologist. • Clinical correlation with patient symptoms.",
  "extra": "class title: Notumor | class description: No tumor detected in the brain MRI scan. | confidence score: 0.3236 | best round: 1 of 1 | best avg confidence: [0.26935407519340515, 0.26501986384391785, 0.32359829545021057, 0.14202778041362762]"
}
