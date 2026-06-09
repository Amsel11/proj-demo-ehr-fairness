# Auditing Algorithmic Fairness in EHR Mortality Models

A systematic audit of subgroup calibration and error-rate disparities in widely
deployed EHR mortality risk scores, plus a reweighting-based mitigation that
closes the largest disparities while preserving overall discrimination.

This repo is wired into the [lab dashboard](https://github.com/Amsel11/lab-dashboard):
editing [`project.yaml`](./project.yaml) and pushing updates the project card
automatically. To re-point it at your own dashboard, edit the `repository:` line
in `.github/workflows/sync-dashboard.yml` and add a `DASHBOARD_TOKEN` secret.
