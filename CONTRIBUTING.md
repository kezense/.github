# Contributing to Kezense

First off, thank you for considering contributing to Kezense! We are building enterprise-grade MLOps infrastructure, and we welcome contributions from the community and our partners.

## Code of Conduct

By participating in this project, you agree to maintain a professional, respectful, and inclusive environment.

## Pull Request Process

1. **Fork & Branch:** Ensure you fork the repository and create your branch from `main`. Use descriptive branch names (e.g., `feature/add-waf-rules` or `fix/sagemaker-latency`).
2. **Code Standards:** 
   - Python code must be formatted with `black` and linted with `ruff`.
   - Terraform code must be formatted using `terraform fmt` and pass `tflint`.
3. **Testing:** Ensure all existing unit tests pass, and write new tests for your features.
4. **Documentation:** Update the `README.md` and any relevant design documents in the `/docs` folder if you are changing architecture.
5. **Template:** Fill out the required Pull Request template completely.

## Commit Messages

We follow conventional commits. Please prefix your commits with:
- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documentation changes
- `chore:` for pipeline/dependency updates

## Security 

If your contribution impacts security (IAM, VPC, WAF), it will require a secondary review from the MLSecOps lead. Do not commit hardcoded secrets or credentials under any circumstances.
