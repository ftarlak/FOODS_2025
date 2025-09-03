*Overview*
This modelling platform (Tarlak et al., 2025) lets you build, compare, and evaluate microbial growth and inactivation models.
It supports both one-step and two-step modelling approaches, and you can benchmark traditional/statistical methods against machine-learning (ML) methods within the same interface.
The sample datasets provided were synthetically generated based on data from the ComBase database.
These datasets are intended for demonstration and learning purposes only, and should not be used as a substitute for experimental validation.

*Key Features*:
Compare one-step vs. two-step modelling workflows
Model growth and inactivation behaviours.
Evaluate traditional vs. machine-learning approaches on the same datasets.
Automatic data augmentation when small datasets are provided (see notes below).

*Units & Conventions*
Microorganism concentration: log CFU/g
Time: hour or second (choose based on your dataset)
You can change units depending on your data. Ensure consistency within each dataset.
Units may vary depending on the input provided.

*Sample Data & Video Guide*
Sample dataset: Synthesized using ComBase Browser
https://combase.errc.ars.usda.gov/
How-to video:https://www.youtube.com/channel/UC9FQD0NAhpUKKlM_I5mabjQ

*Preparing Your Data*
Start in Excel (recommended).
Create a clean worksheet containing only the columns required by your chosen model (e.g., time, concentration, temperature, etc.).
Clean & format.
Use consistent units (see above).
It is recommended to average replicate (parallel) measurements before uploading the data.
While the platform can still generate fitted results without averaging, the plots may display overlapping lines that reduce clarity.
Remove headers/rows you don’t intend to paste.
Avoid merged cells, empty rows, and stray notes.
For two-step modelling, format your dataset with two columns (time, response).
For one-step and ML modelling, format your dataset with three columns (time, response, environmental variable).
For accurate fitting, it is recommended to provide at least 5–7 data points for two-step modelling.
For one-step and ML modelling, accuracy improves as more data are provided. Using fewer points may lead to unreliable or unstable results.
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
ML model fittings may take up to 3–5 minutes, depending on the size of the input dataset.

*Typical Workflow*
Paste data into the platform.
Select approach: one-step or two-step; traditional or ML.
Configure model settings as needed.
Run model and review diagnostics (fit quality, uncertainty, residuals).
Compare approaches and export results/figures if needed.
Download your modelled data together with the statistical indicators (fit metrics, confidence intervals, etc.).

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

**Thank you very much.**

