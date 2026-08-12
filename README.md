## GridSense AI
**Role:** Team Lead

**Repository:** [github.com/IsraelTAIWO/gridsense-ai](https://github.com/IsraelTAIWO/gridsense-ai)

**Pull Request:** [#1 — Enhance GridSense AI with model refinements and dashboard improvements](https://github.com/IsraelTAIWO/gridsense-ai/pull/1)

**Commit:** [`a13274f`](https://github.com/IsraelTAIWO/gridsense-ai/pull/1/changes/a13274fa141119e170103516d2d972664b13f3dd)

**Status:** Pull request opened 7 August 2026

An AI-powered geospatial decision-support dashboard that detects anomalous power plant performance in Nigeria's electricity sector, built for the AI Now Data Science and Machine Learning Bootcamp, then substantially redeveloped post-bootcamp.

**Contribution:** Led the post-hackathon redevelopment of the project, covering the modeling pipeline, dashboard, documentation, and repository structure.

**Key changes:**
- Refined the anomaly detection pipeline by identifying and removing four highly correlated input features, then validated the impact on model explainability output (`top_driver` distribution) before and after
- Fixed a reproducibility bug where a computed variable had been hardcoded instead of referenced live, and derived a duplicated feature list from its single source of truth to prevent future drift
- Rebuilt the Streamlit dashboard with responsive layout, dynamic map sizing, an accurate multi-month aggregation view, and refreshed UI/typography
- Edited project documentation: README, methodology notes, known limitations, and a decision log for key modeling choices

**Skills demonstrated:** unsupervised anomaly detection (Isolation Forest, Local Outlier Factor), feature engineering and correlation analysis, Streamlit dashboard development, technical documentation, git/GitHub workflow (branching, pull requests)


<!---
SegT121/SegT121 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
