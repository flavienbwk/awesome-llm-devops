# Awesome LLM for DevOps [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A list of DevOps features enabled by LLM software.

This repo is intended to be powered by the community. Feel free to pick up ideas and start a profitable business 🤑.

## Foreword

LLMs represent a major step forward for all digital professions. Software engineering can (and must) take advantage of it to speed up its development cycles, make software more secure, and succeed in maintaining it more easily and for longer.

## Features

Features are listed by category and sub-categories, along with the name of tools that meet them.

Checked titles are those where products are considered addressing the issue (at least 3 projects, including 1 product, should exist). Cited tools must be specifically trained for the category they are stated in.

- 🔓 Open source / 🔐 Closed source
- 🆓 Free (or including free tier) / 💸 Paid 3rd party (i.e. OpenAI API) / 💶 Paid
- 📄 Project / 📦 Product (early stage) / 🗄 Product (production-ready)
- #️⃣ CLI interface / 🖥️ browser interface / 👨‍💻 IDE interface

### Software productivity

- [x] Code & configuration writing, suggestion or explanation (chat-based / cli-based / auto-complete)
    - 🔐💶🗄🖥️ [ChatGPT](https://chat.openai.com/)
    - 🔐💶🗄👨‍💻 [GitHub Copilot](https://github.com/features/copilot)
    - 🔓🆓📦👨‍💻 [fauxpilot/fauxpilot](https://github.com/fauxpilot/fauxpilot)
    - 🔓🆓📦👨‍💻 [TabbyML/tabby](https://github.com/TabbyML/tabby)
    - 🔐💶🗄🖥️ [Harness AIDA](https://www.harness.io/products/aida)
    - 🔐💶🗄👨‍💻 [Replit Ghostwriter](https://replit.com/site/ghostwriter)
    - 🔐💶🗄👨‍💻 [AWS CodeWhisperer](https://aws.amazon.com/codewhisperer)
    - 🔐🆓🗄🖥️ [Claude](https://claude.ai/)
    - 🔐💶🗄🖥️ [dev.meta.ai](https://dev.meta.ai/)
    - 🔐🆓🗄👨‍💻 [Ampcode](https://ampcode.com/)
    - 🔐🆓🗄#️⃣ [Claude Code](https://claude.com/product/claude-code)
    - 🔐🆓🗄#️⃣ [Gemini CLI](https://github.com/google-gemini/gemini-cli)
    - 🔐🆓📦👨‍💻 [Google Project IDX](https://idx.google.com/)
    - 🔐🆓📦👨‍💻 [Google Duet AI](https://cloud.google.com/duet-ai)
    - 🔐💶🗄🖥️ [GitLab Duo](https://about.gitlab.com/gitlab-duo/)
    - 🔐💶📄🖥️ [SafeCoder](https://huggingface.co/blog/safecoder)
    - 🔐💸🗄👨‍💻 [Cody](https://sourcegraph.com/cody) (VSCode Extension)
    - 🔐🆓🗄👨‍💻 [Cursor](https://www.cursor.com/)
    - 🔐🆓📦👨‍💻🖥️ [Amazon Q](https://aws.amazon.com/fr/q/)
    - 🔓💸📄#️⃣ [Repochat Action](https://github.com/flavienbwk/repochat-action) (GitHub Action)
- [x] Code, tests & configuration writing, refactoring or suggestion (automated integration with software lifecycle)
    - 🔓💸📦🖥️ [sweepai/sweep](https://github.com/sweepai/sweep)
    - 🔐💶🗄🖥️ [GitLab Duo](https://about.gitlab.com/gitlab-duo/)
    - 🔓🆓📦👨‍💻 [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT)
- [ ] Software documentation exploration (Q&A)
    - 🔐💶🗄🖥️ [GitLab Duo](https://about.gitlab.com/gitlab-duo/)
    - 🔐💸📄🖥️ [GitLab Chat Community](https://github.com/flavienbwk/gitlab-chat-community)
- [ ] Automated MR/PR or issues descriptions, summarization or completion
    - 🔐💶🗄🖥️ [GitLab Duo](https://about.gitlab.com/gitlab-duo/)

### Software maintainability

- [ ] Check code readability and typos
- [ ] Check for valid commit messages (format and relevance)
- [ ] Check for valid issues (format and relevance)
- [ ] Check for code best practices
    - 🔓💸📄🖥️ [truskovskiyk/pr-reviewer](https://github.com/truskovskiyk/pr-reviewer)
    - 🔐💶🗄🖥️ [GitLab Duo](https://about.gitlab.com/gitlab-duo/)
- [ ] Check for abnormal/dangerous contributions
- [ ] Recognize code license
    - 🔐💶🗄👨‍💻 [AWS CodeWhisperer](https://aws.amazon.com/codewhisperer/)
- [ ] Code optimization
    - 🔓💸📄#️⃣ [sshh12/llm_optimize](https://github.com/sshh12/llm_optimize)
- [x] Code vulnerabilities explanation and refactoring suggestions
    - 🔐💶🗄🖥️ [Harness AIDA](https://www.harness.io/products/aida)
    - 🔐💶🗄👨‍💻 [AWS CodeWhisperer](https://aws.amazon.com/codewhisperer/)
    - 🔐💶🗄🖥️ [GitLab Duo](https://about.gitlab.com/gitlab-duo/)

### Infrastructure productivity and maintainability

- [ ] Infrastructure alerts (automated)
- [ ] Infrastructure optimization
    - 🔐🆓📦👨‍💻🖥️ [Amazon Q](https://aws.amazon.com/fr/q/)
    - 🔓🆓📦🖥️ [KubeStellar Console](https://github.com/kubestellar/console) - Multi-cluster Kubernetes dashboard with LLM-powered operations and intelligent workload optimization
- [ ] Infrastructure exploration (i.e: cost analysis, network description etc...)
    - 🔐🆓📦👨‍💻🖥️ [Amazon Q](https://aws.amazon.com/fr/q/)
    - 🔓💸📦#️⃣ [OpsTower.ai](https://github.com/opstower-ai/llm-opstower)
- [ ] Infrastructure troubleshooting
    - 🔓💸📦#️⃣ [OpsTower.ai](https://github.com/opstower-ai/llm-opstower)
- [ ] Detect vulnerabilities and misconfiguration in running machines
    - 🔓💸📦#️⃣ [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt)
- [ ] Detect vulnerabilities and misconfiguration in running webservers/APIs
- [ ] Detect viruses on volumes/disks
- [x] LLM gateway / unified AI routing (EU data residency, GDPR-compliant)
    - 🔐💶🗄#️⃣🖥️ [EURouter](https://eurouter.ai/) - Unified API gateway for 100+ AI models with EU data residency, GDPR compliance, intelligent routing and OpenAI compatibility
