# Data Science Portfolio — Ilan Goldfarb

Selected projects from the Post-Graduate Diploma in Artificial Intelligence & Data Science at Loyalist College (2023–2024).

| Project | What it shows | Tools |
|---|---|---|
| [Audience segmentation for a live-events organization](capstone-audience-segmentation/) — **capstone, 97%** | Joined survey and ticketing data, then used hypothesis testing to decide whether two venues need separate marketing. The audiences match on income and spending but differ in age and preferred day/time (χ² = 54.3, p ≈ 2×10⁻⁹). | pandas, SciPy (Welch t-test, chi-square, regression), matplotlib, seaborn |
| [Face verification for secure access](face-verification/) | Built SIFT + FLANN keypoint matching for face verification and evaluated it properly: threshold chosen on 25 people and tested on 25 unseen people. ROC AUC 0.93, compared with deep face embeddings (dlib). | OpenCV, scikit-learn, dlib / face_recognition |

Both notebooks were revised in 2026. Each one ends with a *Changes from the original submission* section listing what was corrected and why.

## Running the notebooks
```bash
pip install -r requirements.txt
jupyter notebook
```
- **Capstone:** the client's data is confidential (non-disclosure agreement) and isn't included. The chi-square section runs without it.
- **Face verification:** download the [Georgia Tech Face Database](http://www.anefian.com/research/face_reco.htm) and unzip it to `face-verification/data/gt_db/`.

## Contact
ilangoldfarb15@gmail.com · [LinkedIn](https://www.linkedin.com/in/ilan-goldfarb/)
