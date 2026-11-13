# Tales Andre Costa Valcacer

Platform Engineer with 13 years in infrastructure: from 24x7 banking operations to internal developer platforms and AI agents for operations on AWS and Google Cloud.

- **Platform engineering:** Kubernetes, Helm, Terraform and CI/CD with GitHub Actions, with least privilege and changes through pull requests.
- **AI agents with guardrails:** read-only by design, and a person approves every change.

AWS Certified Solutions Architect – Professional · Google Cloud Professional Cloud Architect · Certified Kubernetes Administrator (CKA)

LinkedIn: [linkedin.com/in/talesvalcacer](https://www.linkedin.com/in/talesvalcacer)

## Open-source labs and demos

The companies in the demos are fictional, and none of it is client or employer code. Each one runs on your own machine with no cloud account, and its README lists what was not tested.

**AI agents**

- [k8s-agent-readonly-lab](https://github.com/tales-andre/k8s-agent-readonly-lab): what actually stops an AI agent (MCP server) from changing a Kubernetes cluster, tested on a throwaway kind cluster, with the raw evidence in the repo.
- [reliable-ai-jobs-api](https://github.com/tales-andre/reliable-ai-jobs-api): background AI jobs that retry safely, survive a crashed worker and check a spending cap before every call.
- [pdf-rag-citations](https://github.com/tales-andre/pdf-rag-citations): a PDF chatbot that cites the document and page, and refuses to guess.

**Platform: CI/CD, Kubernetes and Terraform**

- [github-actions-safe-deploys](https://github.com/tales-andre/github-actions-safe-deploys): GitHub Actions that build an image once, scan it, wait for an approval, promote it by digest and roll back, tested on a throwaway kind cluster. The AWS and Google Cloud login steps never ran against a real account.
- [kubernetes-helm-release-tested](https://github.com/tales-andre/kubernetes-helm-release-tested): a Helm release installed, upgraded, rolled back and checked for drift on a throwaway cluster in GitHub Actions.
- [gcp-cloud-run-keyless-deploy](https://github.com/tales-andre/gcp-cloud-run-keyless-deploy): Terraform for Google Cloud Run, deployed through Workload Identity Federation instead of stored keys. Tested offline; never applied to a real project.
- [terraform-aws-review-before-after](https://github.com/tales-andre/terraform-aws-review-before-after): a deliberately flawed AWS Terraform setup, each risk fixed in its own commit with a policy check that fails before and passes after.
