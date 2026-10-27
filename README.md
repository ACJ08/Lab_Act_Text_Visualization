# Words to Pictures

Analyze language in the UCI SMS Spam Collection using preprocessing, DTM, TF-IDF, message-length plots, group prevalence, and KWIC. Includes notebook, source-derived CSV, figures, report, and summary.

Dataset: UCI Machine Learning Repository, SMS Spam Collection, DOI [10.24432/C5CC84](https://doi.org/10.24432/C5CC84), CC BY 4.0; accessed 2026-10-27.

## Windows
From PowerShell in this folder:
1. py -3 -m venv .venv
2. .venv\Scripts\Activate.ps1
3. python -m pip install --upgrade pip
4. pip install -r requirements.txt
5. jupyter lab
Open the notebook and Run All. If activation is blocked, use .venv\Scripts\python.exe -m pip install -r requirements.txt and .venv\Scripts\jupyter.exe lab. macOS/Linux: python3 -m venv .venv; source .venv/bin/activate; pip install -r requirements.txt; jupyter lab.

Relative paths make the project movable. After dependencies install, no internet/model download is needed. The historical, heterogeneous corpus is not representative of current SMS. TF-IDF contrasts are descriptive, not classifier performance.
