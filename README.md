# face-detection-mlproject
AI-based system to detect face-swap deepfake videos using CNNs, temporal analysis, and artifact detection. Includes dataset preprocessing, model training, explainability.
- Dataset: 50 real, 50 fake (FaceForensics++ subset)
- Pipeline: frames -> face crops -> CNN embeddings -> PCA -> classifier
- Steps: see /scripts for preprocessing & training

