# Project-Veritas
Project Veritas is an experimental framework that studies when and why deepfake detectors fail.
Rather than proposing a new detection model, this project treats a standard deepfake detector as a probe and evaluates how its reliability changes under controlled temporal and distributional shifts using the FaceForensics++ dataset


Version (0.1) of Project Veritas on a single manipulation method and compression level to ensure interpretability. 

What Veritas is / is not:

What this project IS:
A controlled experimental study
A reproducible analysis framework
A failure-mode investigation
A research-style technical report

What this project is NOT:
A production-ready detector
A startup or product
A benchmark leaderboard entry
A claim of robustness or generalization


data/           # Dataset handling scripts (no raw data committed)
models/         # Baseline detector definitions
experiments/    # Frozen experiment configs
metrics/        # Evaluation and disagreement metrics
plots/          # Figures used in the report
report/         # Technical report source
