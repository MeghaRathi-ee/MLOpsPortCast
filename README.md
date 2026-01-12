# MLOpsPortCast

MLOpsPortCast is a **local MLOps learning project** focused on understanding
end-to-end MLOps concepts **without using cloud services initially**.

This project follows best practices inspired by real-world MLOps systems:
- Dataset registration and versioning
- Reproducible machine learning experiments
- Clean project structure
- Git-based tracking

---

## Project Structure

Dataset/
├── raw/ # Original raw data (never modified)
├── processed/ # Versioned processed datasets (v1, v2, ...)
├── metadata/ # Dataset registration metadata (YAML)
notebooks/ # Data exploration and preprocessing
requirements.txt # Python dependencies
.gitignore # Ignored files and folders


---

## Current Progress

- Dataset v1 created and registered locally using metadata
- Data preprocessing completed
- Git and GitHub versioning set up correctly

---

## Next Steps

- Train first machine learning model
- Track experiments using MLflow
- Evaluate and package the model
- Serve the model locally using an API

“All experiments are run locally using a Python virtual environment as a replacement for cloud compute.”