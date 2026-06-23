# Gemma 4 on ML exam questions: text vs image

Checking if Gemma 4 does worse on 02450 ML exam multiple choice questions when a
figure or table is shown as an image instead of being written out as text.

- exam PDFs and their solutions are in `ML-examsets/` and `ML-solutions/`
- Gemma's answers are in `data/results.csv`
- the code is in `code/`: `build_questions_csv.py` builds the question list,
  `crop_figures.py` cuts the figures out of the exam PDFs, and `collect.py` sends
  everything to Gemma and saves the answers
- `statcalculations.ipynb` does the stats (McNemar, binomial, z-test, power)

Run the scripts from the repo root, like `python code/collect.py`.
