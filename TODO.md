# TODO for Final IJRR Website Materials (Anonymous)

This file lists items that should be prepared next to complete a publication-ready project website.

## 1) Core links and reproducibility assets (highest priority)

- [ ] **Anonymous code repository URL** for review period (read-only mirror if needed).
- [ ] **Camera-ready public repository URL** (post-acceptance switch).
- [ ] **Paper link** (arXiv or publisher page) once allowed by review policy.
- [ ] **Devkit release tag** (e.g., `v1.0.0`) matching the dataset version.
- [ ] **Checksums** (`SHA256SUMS`) for each downloadable archive.
- [ ] **Data license text** (short summary on webpage + full LICENSE in repository).

## 2) Visual materials for homepage

- [ ] **Hero image** representing bimanual gearbox assembly.
- [ ] **Modalities figure** (RGB/proprioception/actions/annotations pipeline).
- [ ] **Real vs simulation comparison figure** with aligned task setup.
- [ ] **Benchmark overview diagram** (T1/T2/T3 + weighted score formula).

## 3) Dataset documentation details to add

- [ ] Episode count and duration statistics (real and simulation splits).
- [ ] Split definition (`train/val/test`) and official evaluation split policy.
- [ ] Annotation schema table (field names, units, frequency, frame conventions).
- [ ] Sensor calibration and synchronization details.
- [ ] Known failure modes and caveats section.

## 4) Devkit completeness checklist

- [ ] Minimal data loader script (`load_one_episode.py`) with expected output.
- [ ] End-to-end benchmark script (`run_benchmark.py`) with reproducible seed.
- [ ] Baseline training config files and default hyperparameters.
- [ ] Evaluation script with exact metric implementation and unit tests.
- [ ] Visualization utility (trajectory + keyframe playback).

## 5) Benchmark/challenge operation items

- [ ] Submission format template (Docker/image + config + logs).
- [ ] Leaderboard update policy and schedule.
- [ ] Tie-break and disqualification rules (safety/reproducibility).
- [ ] FAQ page for common setup and evaluation issues.

## 6) Utility statement refinement (for reviewer concern #2)

Prepare a concise paragraph for the homepage and manuscript rebuttal that states **future utility of real data**:

- [ ] Learning robust assembly policies under partial observability.
- [ ] Studying human-aware recovery strategies from physically plausible mistakes.
- [ ] Benchmarking sim-to-real transfer and domain adaptation methods.
- [ ] Building multimodal foundation models for industrial collaborative manipulation.

## 7) Anonymous-review compliance

- [ ] Remove non-anonymous organization/team references from screenshots and metadata.
- [ ] Replace personal links with anonymous placeholders until review ends.
- [ ] Verify repository commit history visibility policy for double-blind compliance.

## 2026-04-29 Website update progress

- [x] Added dataset visual materials to homepage (`assert/objects.png`, `assert/real_data_frame.png`, `assert/sim_data_frame.png`).
- [x] Added robot configuration PDF entry (`assert/real_robot_config.pdf`) with direct open link.
- [x] Added task videos (`video/task1.mp4`, `video/task3.mp4`) and clarified that Task 2 is a subset of Task 1 (starts from an intermediate state).
- [x] Replaced direct Markdown links with HTML-rendered documentation links through `docs/viewer.html`.
- [x] Confirmed dataset download link points to: https://huggingface.co/datasets/rocochallenge2025/rocochallenge2025
