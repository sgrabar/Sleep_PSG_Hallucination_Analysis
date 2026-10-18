# Sleep_PSG_Hallucination_Analysis

This repository contains the paper for my individual capstone project for my M.S. in Artificial Intelligence at City University of Seattle.

**Paper:** *Evaluating Hallucination Risk in AI-Generated Polysomnography Reports Under Controlled Artifact Contamination*

## Project Overview
This research investigates whether signal artifacts in polysomnography (PSG) data increase the likelihood of hallucinations in AI-generated sleep study reports.

Using real-world sleep study recordings, I introduced controlled EEG contamination from EOG, EMG, and ECG signals at different severity levels. I used SleepLM to generate clinical interpretations across 1,750 signal versions and an independent LLM-based evaluation framework to assess hallucinations. I performed statistical comparisons against clean baseline recordings to determine whether artifact type or severity significantly affected hallucination rates.

## Methods & Skills
- **Programming & Data Analysis:** Python, NumPy, Pandas, MNE-Python
- **Signal Processing:** EEG/PSG processing, artifact simulation, signal-to-noise ratio (SNR)
- **Machine Learning & AI:** SleepLM, LLM-based evaluation, hallucination detection
- **Statistical Analysis:** McNemar's test, Holm correction, paired experimental comparisons
- **Research:** Experimental design, data preprocessing, quantitative analysis, scientific writing
