# Everything-as-Code Survey — Final Column Schema

| Column Name (existing)          | Display Name                      | Type                        | Required | Description |
|---------------------------------|-----------------------------------|------------------------------|----------|-------------|
| SurveyYear                      | Survey Year                       | Single line of text (or Number) | No | Year this survey response was provided. You can hide this and auto-fill if desired. |
| OrgUnit                         | Organizational Unit               | Choice (single)             | Yes | The top-level group the responder belongs to (e.g., I&E, EP, Security, Cloud Platform, AppDev). |
| TeamName                        | Team Name                         | Single line of text         | Yes | Name of the responding team. |
| PrimaryContact                  | Primary Contact                   | Single line of text         | Yes | Person responsible for answering follow-up questions. |
| WorkstreamType                  | Workstream Type                   | Choice (single)             | Yes | Primary domain of the team's work (Terraform/IaC, Network, IAM, CI/CD, App Runtime, Observability). |
| PercentWorkAsCode               | % of Work Treated as Code         | Number (0–100)              | Yes | Approximate percentage of the team's work represented in version-controlled code. |
| ConfigMgmt_Maturity             | Configuration Management Maturity | Choice (single)             | Yes | Level of maturity in managing configurations in Git and using automation. |
| ConfigDomains_Covered           | Configuration Domains Covered     | Choice (multi-select)       | Yes | Which areas the team manages as code (Network, IAM, IaC, CI/CD, App Config, Security Controls). |
| VersionControlUsage             | Version Control Tools Used        | Choice (multi-select)       | Yes | Systems where the team stores code and configuration (GitHub, Bitbucket, ADO). |
| Uses_Terraform                  | Uses Terraform                    | Choice (single)             | Yes | Does the team use Terraform today? |
| Terraform_Standardization       | Terraform Standardization Level   | Choice (single)             | Yes | How standardized the team’s Terraform code is. |
| Has_Documented_Standards        | Has Documented Standards          | Choice (single)             | Yes | Whether the team maintains internal documentation/standards for engineering. |
| Automation_Level                | Automation Level                  | Choice (single)             | Yes | How automated the team's workflows and deployments are. |
| Uses_AI_Today                   | Uses AI Today                     | Choice (single)             | Yes | Whether AI tools are actively in use by the team. |
| AI_Tools_In_Use                 | AI Tools in Use                   | Single line of text         | No | Names of AI tools currently used (e.g., Copilot, Wiz, custom scripts). |
| Biggest_Blocker_EverythingAsCode | Biggest Blocker to EAC Adoption  | Single line of text         | Yes | The top obstacle preventing the team from achieving Everything-as-Code. |
| Top_3_PainPoints                | Top 3 Pain Points                 | Single line of text (long text OK) | Yes | The top three problems slowing down the team's delivery or automation. |
| Top_3_Opportunities             | Top 3 Opportunities               | Single line of text (long text OK) | Yes | Top opportunities where automation or AI could improve delivery. |
| Current_Tooling                 | Current Tooling                   | Choice (multi-select)       | Yes | Tools used today (Terraform, Ansible, GitHub, Jenkins, Bitbucket, SaltStack, Octopus). |
| DeploymentPlatform              | Deployment Platform               | Choice (multi-select)       | Yes | Where the team deploys code (Azure, GCP, AWS, Salesforce, Pega, VMC). |
| Wants_TDX_Pilot                 | Interested in TDX Pilot Program   | Choice (single)             | Yes | Whether the team wants to participate in an early TDX pilot. |
| Notes_Internal                  | Internal Notes                    | Single line of text (long text OK) | No | Private internal notes for analysis. |
