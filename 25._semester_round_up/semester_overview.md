# Semester Overview

## 01. Introduction
**Topics covered**: [SSH](../07._Azure_vm_portal_az/07._ssh.md), SCP, [legacy codebase](../01._introduction/02._the_legacy_project.md), [OpenAPI/Swagger](../02._decide_framework_convert_code/03._openapi.md), Postman, [Claude Code](../01._introduction/ai_cli_assistant.md), DevOps Handbook, exam format overview.  
**Produced**: Exam groups formed, first look at the legacy project.

## 02. Decide Framework & Convert Code
**Topics covered**: [Framework selection](../02._decide_framework_convert_code/decide_on_a_framework.md), [code migration](../02._decide_framework_convert_code/commence_the_rewrite.md), [OpenAPI specification](../02._decide_framework_convert_code/03._openapi.md), [Kanban board](../02._decide_framework_convert_code/kanban_github_project.md), [monolith vs. mono-repo vs. multi-repo](../02._decide_framework_convert_code/04._monolith_monorepo_multirepo.md), DevOps principle of flow (visible work, WIP, batch size).  
**Produced**: Group GitHub organisation, initial exam project repository, Kanban board, OpenAPI spec started.

## 03. Linux Crash Course
**Topics covered**: [Linux terminal basics](../03._linux/unix_commands.md), [file system navigation](../03._linux/unix_commands.md), [file permissions](../03._linux/unix_commands.md), [bash scripting](../03._linux/unix_commands_exercises.md).  
**Produced**: Basic shell scripts and familiarity with the Linux terminal.  
**Cookbook**: [openapi branch](https://github.com/cookbookio/awsome_recipe_cookbook/tree/openapi)

## 04. Linux, Windows & Mac
**Topics covered**: [Package managers (apt, brew, Chocolatey)](../04._linux_win_mac/package_managers.md), [environment variables](../04._linux_win_mac/env.md), [shell commands](../04._linux_win_mac/shell_cheatsheet.md), [pipes](../04._linux_win_mac/shell_cheatsheet.md), [output redirection](../04._linux_win_mac/shell_cheatsheet.md), [bash scripts](../04._linux_win_mac/shell_cheatsheet.md).  
**Produced**: Package manager installed and configured, basic bash scripts.

## 05. Git Branching Strategies
**Topics covered**: [Git Flow](../05._git_branching_strategies/git_branching_demo.md), [GitHub Flow](../05._git_branching_strategies/git_branching_demo.md), [Trunk-Based Development](../05._git_branching_strategies/git_branching_demo.md), [merge conflicts](../05._git_branching_strategies/create_a_merge_conflict.md), [branching best practices](../05._git_branching_strategies/research_git_branching_strategies.md), DevOps principle of reducing WIP.  
**Produced**: Chosen and documented branching strategy for the exam project.

## 06. CI - GitHub Actions
**Topics covered**: [YAML syntax](../06._CI_github_actions/refresh_yaml_syntax.md), [GitHub Actions workflows](../06._CI_github_actions/02._github_actions.md), [runners, jobs, steps](../06._CI_github_actions/02._github_actions.md), [GitHub Secrets](../06._CI_github_actions/04._github_secrets.md), PR templates, [issue templates](../06._CI_github_actions/03._github_issues_workflow.md), branch protection rules.  
**Produced**: GitHub Actions workflow, PR template, issue template, secrets configured.

## 07. Azure - Cloud
**Topics covered**: [Cloud concepts](../07._Azure_vm_portal_az/05._azure.md), [Azure VM setup (portal & CLI)](../07._Azure_vm_portal_az/Azure_Cheatsheet.md), [SSH key pairs](../07._Azure_vm_portal_az/07._ssh.md), [static IP](../07._Azure_vm_portal_az/05._azure.md), [open ports](../07._Azure_vm_portal_az/05._azure.md), [deployment to Azure](../07._Azure_vm_portal_az/Azure_Cheatsheet.md).  
**Produced**: Running application deployed on an Azure VM.

## 09. Continuous Delivery
**Topics covered**: [Continuous Delivery vs. Continuous Deployment](../09._Continous_delivery/09._deployment_considerations.md), GitHub Actions CI/CD pipeline, [GHCR.io](../09._Continous_delivery/cheatseet_ghcr.io.md), [Docker image build & push](../09._Continous_delivery/cheatseet_ghcr.io.md), [running apps in production (PM2, Gunicorn)](../09._Continous_delivery/08._running_in_production.md).  
**Produced**: Full CI/CD pipeline that builds, pushes, and deploys the application automatically.  
**Cookbook**: [cd branch](https://github.com/cookbookio/awsome_recipe_cookbook/tree/cd)

## 12. CI - Code Quality, Linting & Static Code Analysis
**Topics covered**: [Software quality](../12._CI_code_quality_linting_static_code_analysis/02._software_quality.md), [technical debt](../12._CI_code_quality_linting_static_code_analysis/02._software_quality.md), [code smells](../12._CI_code_quality_linting_static_code_analysis/02._software_quality.md), [linting](../12._CI_code_quality_linting_static_code_analysis/04._linting.md), [popular linters per language](../12._CI_code_quality_linting_static_code_analysis/04._linting.md), [linting in GitHub Actions](../12._CI_code_quality_linting_static_code_analysis/04._linting.md), [code reviews](../12._CI_code_quality_linting_static_code_analysis/02._software_quality.md), [pull requests](../12._CI_code_quality_linting_static_code_analysis/02._software_quality.md), [SonarQube/Code Climate](../12._CI_code_quality_linting_static_code_analysis/02._software_quality.md).  
**Produced**: Linter added to the project and integrated into the GitHub Actions workflow. README badges.  
**Cookbook**: [linting branch](https://github.com/cookbookio/awsome_recipe_cookbook/tree/linting)

## 13. CI - Code Quality, Git Hooks, Linting & Testing
**Topics covered**: [Git hooks](../13._CI-Code_Quality-Git_Hooks_Linting_Testing/01._githooks.md), [pre-commit framework](../13._CI-Code_Quality-Git_Hooks_Linting_Testing/tutorial_precommit.md), [running linters and tests before committing](../13._CI-Code_Quality-Git_Hooks_Linting_Testing/tutorial_precommit.md), [Husky & lint-staged for JavaScript](../13._CI-Code_Quality-Git_Hooks_Linting_Testing/husky_lint_staged.md), [pytest with pre-commit](../13._CI-Code_Quality-Git_Hooks_Linting_Testing/tutorial_pytest_precommit.md).  
**Produced**: Pre-commit hooks configured in the project, tests running automatically before each commit.  
**Cookbook**: [precommit branch](https://github.com/cookbookio/awsome_recipe_cookbook/tree/precommit)

## 19. How DevOps Are You?
**Topics covered**: [DevOps maturity assessment](../19._how_devops_are_you/how_are_you_devops.md), The DevOps Handbook, [the three ways (Flow, Feedback, Continual Learning)](../19._how_devops_are_you/devops_slides.md), [reflection on the hackathon project](../19._how_devops_are_you/how_are_you_devops.md).  
**Produced**: Group analysis and presentation of DevOps maturity level.

## 20. Nginx - Reverse Proxy & Load Balancing
**Topics covered**: [Reverse proxies](../20._nginx_proxy_load_balancer/06._reverse_proxies.md), [nginx configuration](../20._nginx_proxy_load_balancer/06._reverse_proxies.md), [load balancing strategies](../20._nginx_proxy_load_balancer/06._reverse_proxies.md), [running multiple servers](../20._nginx_proxy_load_balancer/06._reverse_proxies.md), [Docker Compose with proxy setup](../20._nginx_proxy_load_balancer/02._docker-compose.md).  
**Produced**: Nginx reverse proxy configured in front of the application.  
**Cookbook**: [nginx branch](https://github.com/cookbookio/awsome_recipe_cookbook/tree/nginx) / [proxy branch](https://github.com/cookbookio/awsome_recipe_cookbook/tree/proxy)

## 21. IaC - Infrastructure as Code
**Topics covered**: [Why IaC](../21._iac/02._why_infrastructure_as_code.md), [ClickOps vs. CLI vs. SDK vs. IaC](../21._iac/02._why_infrastructure_as_code.md), [reproducibility](../21._iac/02._why_infrastructure_as_code.md), [idempotency](../21._iac/02._why_infrastructure_as_code.md), [recoverability](../21._iac/02._why_infrastructure_as_code.md), [Azure setup and teardown scripts](../21._iac/03._cookbook_iac.md).  
**Produced**: Infrastructure scripts (setup & teardown) added to the project repository.  
**Cookbook**: [IaC branch](https://github.com/cookbookio/awsome_recipe_cookbook/tree/IaC/infrastructure)

## 22. IaC - Infrastructure as Code II
**Topics covered**: Continued IaC work, [infrastructure checklist](../22._iac_II/01._infrastructure_check_list.md), full team able to run setup and teardown scripts, [developing new features with IaC in mind](../22._iac_II/02._developing_a_new_feature.md).  
**Produced**: Complete, version-controlled infrastructure folder in the project repository.  
**Cookbook**: [IaC branch](https://github.com/cookbookio/awsome_recipe_cookbook/tree/IaC/infrastructure)

## 23. Monitoring & Logging
**Topics covered**: [Monitoring vs. logging](../23._monitor_logging/03._monitoring.md), [Prometheus](../23._monitor_logging/01._prometheus_grafana_setup.md), [Grafana](../23._monitor_logging/01._prometheus_grafana_setup.md), [metrics and dashboards](../23._monitor_logging/01._prometheus_grafana_setup.md), [DevOps feedback principle](../23._monitor_logging/03._monitoring.md), [setting up monitoring on Azure](../23._monitor_logging/03._azure_multivm_monitoring.md).  
**Produced**: Prometheus and Grafana running alongside the application with a working dashboard.  
**Cookbook**: [monitoring branch](https://github.com/cookbookio/awsome_recipe_cookbook/tree/monitoring)

## 24. Deployment Strategies, Orchestration & Maintenance
**Topics covered**: [Mutable vs. immutable infrastructure](../24._deployment_strategies/02._deploying_infrastructure_configuration_managment.md), [blue-green deployment](../24._deployment_strategies/03._deployment_strategies.md), [canary deployment](../24._deployment_strategies/03._deployment_strategies.md), [rolling updates](../24._deployment_strategies/03._deployment_strategies.md), [fault tolerance](../24._deployment_strategies/04._orchestration.md), [redundancy](../24._deployment_strategies/04._orchestration.md), [scalability](../24._deployment_strategies/04._orchestration.md), [load balancing](../24._deployment_strategies/04._orchestration.md), [orchestration platforms](../24._deployment_strategies/04._orchestration.md), [maintainability](../24._deployment_strategies/08._maintenance.md), service level agreements, [definition of done](../24._deployment_strategies/definition_of_done.md).  
**Produced**: Chosen and documented deployment strategy, SLA written and published.
