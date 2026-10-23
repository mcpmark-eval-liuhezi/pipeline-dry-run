# Smoke readiness checklist

Short checklist to confirm the automated change flow is ready for the Thursday demo dry run.

- [ ] Default branch exists and is not protected
- [ ] Smoke workflow file present at `.github/workflows/smoke.yml`
- [ ] Feature branch created and checklist file committed
- [ ] Pull request opened from the feature branch into the default branch
- [ ] Teammate-style review completed with inline comment (token: SMOKE-REVIEW-V1)
- [ ] Pull request merged (squash) into the default branch
- [ ] `smoke` workflow run completed successfully on the default branch

Marker line for pipeline verification:

SMOKE-CHECK-V1: pipeline dry run
