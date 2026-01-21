# Eye-tracking-Fake-News---Study

# Replication Data: Elements of Credibility or Credulity About Fake News Exposure

This repository contains the dataset and analysis scripts for the empirical study: **"Elements of Credibility or Credulity About Fake News Exposure: An Empirical Study"**.

## 📂 Repository Structure

Pour chaque participant (P01 à P30)
* `Fixeye.csv`: The raw eye-tracking data associated with the timestamp.
* `FixRep.csv`: The claims, the participant responses, associated with the timestamp.
* `reponses_XX.csv`: The user_id, the claims, the participant responses, and the real responses (false/true) associated with the timestamp.
* `README.md`: This file.

## 📊 Data Dictionary (Variables)

The dataset includes the following metrics for N=30 participants and 30 claims:

* **Participant_ID**: Unique identifier for each participant.
* **Response**: Participant classification (false, true or not\sure).
* **vrairep**: Real classification (false or true)
* **FPOG-X**: Horizontal Gaze Position (mean X-coordinate relative to screen center).
* **FPOG-Y**: Vertical Gaze Position (mean X-coordinate relative to screen center).
* **FPOG-S**: First Fixation Duration (in milliseconds).
* **LPD / RPD**: Left/Right Pupil Diameter (dilation metric).

## 🚀 How to use

1.  Clone the repository.
2.  Merged files witht the timestamp.
3.  Create new columns to add topics and proper nouns.
4.  Ensure you have Python installed with `pandas` and `scipy`.
5.  Run the script to reproduce the T-tests and Chi-square results mentioned in the paper.

##  citation

If you use this dataset, please cite the original paper:
[Insert your citation here once published]
