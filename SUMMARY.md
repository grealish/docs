# Table of contents

* [Introduction](README.md)

## Getting started

* [📐 Architecture](getting-started/design-and-architecture.md)
* [🔐 Security](getting-started/security.md)
* [📥 Deployment](getting-started/deployment/README.md)
  * [Kubernetes](getting-started/deployment/kubernetes/README.md)
    * [Azure Kubernetes Service (AKS)](getting-started/deployment/kubernetes/azure-kubernetes-service.md)
    * [Google Kubernetes Engine (GKE)](getting-started/deployment/kubernetes/google-kubernetes-engine-gke.md)
    * [Amazon Kubernetes Service (AKS)](getting-started/deployment/kubernetes/amazon-kubernetes-service-aks.md)
  * [Docker Compose](getting-started/deployment/docker-compose/README.md)
    * [Docker Compose](getting-started/deployment/docker-compose/docker-compose.md)
    * [Docker Compose + Azure Storage](getting-started/deployment/docker-compose/docker-compose-1.md)
* [🌟 Getting started](getting-started/getting-started.md)
* [🏢 Organizations](getting-started/organizations.md)
* [🕹 Workspaces](getting-started/workspaces.md)
* [🛡 VCS Providers](getting-started/vcs-providers/README.md)
  * [Github](getting-started/vcs-providers/github.md)
  * [Azure Devops](getting-started/vcs-providers/azure-devops.md)
  * [BitBucket](getting-started/vcs-providers/bitbucket.md)
  * [Gitlab](getting-started/vcs-providers/gitlab.md)
* [🗃 Templates](getting-started/templates.md)

## 💻 CLI

* [🌟 Getting started](cli/getting-started/README.md)
  * [variable create](cli/getting-started/variable-create.md)
  * [variable update](cli/getting-started/variable-update.md)
  * [variable delete](cli/getting-started/variable-delete.md)
  * [terrakube job](cli/getting-started/terrakube-job/README.md)
    * [job list](cli/getting-started/terrakube-job/job-list.md)
    * [job create](cli/getting-started/terrakube-job/job-create.md)
  * [terrakube module](cli/getting-started/azb-module/README.md)
    * [module list](cli/getting-started/azb-module/list.md)
    * [module create](cli/getting-started/azb-module/create.md)
    * [module update](cli/getting-started/azb-module/module-update.md)
    * [module delete](cli/getting-started/azb-module/module-delete.md)
* [💿 Installation](cli/install.md)
* [ℹ Commands](cli/commands/README.md)
  * [terrakube login](cli/commands/azb-login.md)
  * [terrakube logout](cli/commands/terrakube-logout.md)
  * [terrakube organization](cli/commands/azb-organization/README.md)
    * [organization list](cli/commands/azb-organization/list.md)
    * [organization create](cli/commands/azb-organization/create.md)
    * [organization update](cli/commands/azb-organization/update.md)
    * [organization delete](cli/commands/azb-organization/delete.md)
  * [terrakube team](cli/commands/terrakube-team/README.md)
    * [team list](cli/commands/terrakube-team/team-list.md)
    * [team create](cli/commands/terrakube-team/team-create.md)
    * [team update](cli/commands/terrakube-team/team-update.md)
    * [team delete](cli/commands/terrakube-team/team-delete.md)
  * [terrakube workspace](cli/commands/terrakube-workspace/README.md)
    * [workspace list](cli/commands/terrakube-workspace/workspace-list.md)
    * [workspace create](cli/commands/terrakube-workspace/workspace-create.md)
    * [workspace update](cli/commands/terrakube-workspace/workspace-update.md)
    * [workspace delete](cli/commands/terrakube-workspace/workspace-delete.md)
    * [workspace variable](cli/commands/terrakube-workspace/workspace-variable/README.md)
      * [variable list](cli/commands/terrakube-workspace/workspace-variable/variable-list.md)

## 📖 API

* [🌟 Getting started](api/getting-started.md)
* [⚙ Methods](api/methods/README.md)
  * [Organization](api/methods/organization.md)
  * [Teams](api/methods/teams.md)
  * [Workspace](api/methods/workspace.md)
  * [Variables](api/methods/variables.md)
  * [History](api/methods/history.md)
  * [Jobs](api/methods/jobs.md)
  * [Template](api/methods/template.md)
  * [Schedule](api/methods/schedule.md)
  * [Step](api/methods/step.md)
  * [Module](api/methods/module.md)
  * [Vcs](api/methods/vcs.md)
  * [Provider](api/methods/provider.md)

## 🛡 VCS Connection

* [Azure DevOps](vcs-connection/azure-devops.md)
* [Bitbucket](vcs-connection/bitbucket.com.md)
* [Github](vcs-connection/github.com.md)
* [GitLab](vcs-connection/gitlab.com.md)

## 🏗 CI/CD Integration

* [Bitbucket](ci-cd-integration/bitbucket.md)
