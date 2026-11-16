# Driver Drowsiness Detection System

A multi-model deep learning pipeline built with TensorFlow/Keras to detect driver fatigue using eye state (`Open`/`Closed`), mouth state (`yawn`/`no_yawn`), and 3-stage fatigue fusion.

## Key Results
* **Dataset:** 3,496 images across 4 balanced classes (Train: 2,304 | Val: 596 | Test: 596)
* **4-Class Models:** Custom CNN (93.46% test accuracy) vs. MobileNetV2 (89.93% test accuracy)
* **Eye-State Classifier (MobileNetV2):** 99.15% test accuracy
* **Mouth-State Classifier (MobileNetV2):** 85.34% test accuracy
* **3-Level Fatigue Fusion Accuracy:** 89.93%