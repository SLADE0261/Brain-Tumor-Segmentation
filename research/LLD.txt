### Low-Level Document (LLD)

**Data Pipeline:**

- Dataset: BraTS 2018 for MRI images.
- Database: Cassandra.
- Preprocessing:
  - DICOM to NIfTI conversion.
  - Skull stripping and normalization.

**Model Details:**

1. Segmentation:
   - Model: U-Net architecture.
   - Loss Function: Dice coefficient loss.
   - Metrics: Intersection over Union (IoU).
2. Prediction:
   - Model: Random Forest and Neural Networks.
   - Features: Radiomic and clinical.

**Code Specifications:**

- Programming Language: Python.
- Standards: PEP 8.
- Modular structure.

**Deployment:**

- Platform: AWS.
- Tools: MLFlow for model tracking.
- API: FastAPI.

**Logging:**

- Library: Python logging module.
- Level: INFO, DEBUG, ERROR.

**Testing:**

- Unit tests using pytest.
- Integration testing for end-to-end pipelines.

---
