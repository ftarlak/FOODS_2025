*Overview*
This modelling platform (Tarlak et al., 2025) lets you build, compare, and evaluate microbial growth and inactivation models. It supports both one-step and two-step modelling approaches, and you can benchmark traditional/statistical methods against machine-learning (ML) methods within the same interface.

*Key Features*:
Compare one-step vs. two-step modelling workflows
Model growth and inactivation behaviours.
Evaluate traditional vs. machine-learning approaches on the same datasets.
Automatic data augmentation when small datasets are provided (see notes below).

*Units & Conventions*
Microorganism concentration: log CFU/g
Time: hour or second (choose based on your dataset)
You can change units depending on your data. Ensure consistency within each dataset.

*Sample Data & Video Guide*
Sample dataset: Synthesized using ComBase Browser
https://combase.errc.ars.usda.gov/
How-to video:https://www.youtube.com/channel/UC9FQD0NAhpUKKlM_I5mabjQ

*Preparing Your Data*
Start in Excel (recommended).
Create a clean worksheet containing only the columns required by your chosen model (e.g., time, concentration, temperature, etc.).
Clean & format.
Use consistent units (see above).
Remove headers/rows you don’t intend to paste.
Avoid merged cells, empty rows, and stray notes.
Copy just the data area.
Select the block of data (no extra blank rows/columns) and paste it into the platform’s data input area.
Check size & coverage.
More data generally improves model stability and confidence intervals.

*Important Notes on Machine Learning*
Dataset size matters. Accuracy and robustness improve with more diverse and abundant data.
Automatic augmentation:
If you provide fewer than 750 data points, the platform will generate augmented data to help models train.
This can inflate perceived robustness and interval coverage.
Whenever possible, prefer real, larger datasets over augmented ones.

*Typical Workflow*
Paste data into the platform.
Select approach: one-step or two-step; traditional or ML.
Configure model settings as needed.
Run model and review diagnostics (fit quality, uncertainty, residuals).
Compare approaches and export results/figures if needed.
Download their modelled data together with the statistical indicators (fit metrics, confidence intervals, etc.).

*Troubleshooting*
Verify units are correct and consistent.
Ensure no missing/invalid values in pasted data.
Increase data size/coverage if fits are unstable.
Be cautious interpreting results when augmentation is used.

*Contact & Collaboration*
Questions, issues, or collaboration offers:
📧 ai.microbiology@gmail.com
📧 ftarlak@gtu.edu.tr

*Citation*
If you use this platform in your work, please cite:
Tarlak, F., Şimşek, B.B., Şahin, M., & Pérez-Rodríguez, F., (2025). Next-Generation Predictive Microbiology: A Software Platform Combining Two-Step, One-Step and Machine Learning Modelling. Foods, ..(..), .... https://doi.org/.........
Thank you very much.