# Project and application materials

Start with [the case study](PROJECT_CASE_STUDY.md) or the [two-page brief](../output/pdf/Calorie_Lab_Project_Brief.pdf). Both explain the question, findings, implementation and limitations.

- [Research source](https://github.com/Moobakr/calorie-lab-research)
- [Live demo](https://huggingface.co/spaces/Moobakr/calorie-lab-fewer-sensors)
- [Original notebook project](https://github.com/Moobakr/calories-burnt-prediction)
- [CV and motivation drafts](APPLICATION_TEXT.md)
- [Interview preparation](INTERVIEW_GUIDE.md)
- [Contributions and AI assistance](CONTRIBUTIONS_AND_CLAIMS.md)

The usability study was skipped; no participant findings or measured user benefit are claimed. The study kit is retained for optional future use. Application drafts must reflect your actual understanding and the selected programme's instructions; no eligibility, deadline or application submission is asserted here.

## Rebuild the brief

Install portfolio/requirements-pdf.txt in a separate document environment, then run `python portfolio/build_brief.py` from the repository root. The generator reads aggregate JSON reports only and does not load data/models or repeat evaluation. PDF generation is separate from the pinned ML environment.
