# 🚀 DSV-Developer-Hub

> Your personal developer operating system.

DSV-Developer-Hub is a self-hosted productivity portal designed to centralize the daily tools, systems, environments, and workflows used by DSV developers, DevOps engineers, and IT professionals.

Instead of managing dozens of browser tabs across Jira, Azure, AKS, Bitbucket, Clarity, Flex, Artifactory, Swagger, Confluence, and internal systems, DSV-Developer-Hub provides a single entry point for everything.

---

## 🎯 Vision

Reduce context switching and improve developer productivity by providing:

- One place for all work-related systems
- Personalized dashboards
- Environment management
- Azure and Kubernetes tooling
- Time reporting reminders
- Documentation access
- AI-powered assistant capabilities

---

## ✨ Features

### Dashboard

- Personalized home page
- Daily overview
- Important notifications
- Quick access to frequently used tools

### Quick Links

- Jira
- Bitbucket
- Azure Portal
- Artifactory
- Clarity
- Flex HRM
- Swagger UIs
- Documentation
- Internal Platforms

### Jira Integration

- My assigned tickets
- Active sprint overview
- Blocked issues
- Recently updated issues
- Search tickets

### Azure Integration

- Subscription overview
- Resource groups
- Application Insights
- Service Bus
- Storage Accounts
- Key Vault

### AKS Tools

- Cluster overview
- Namespaces
- Pods
- Logs
- Deployments
- Services
- Secret references

### Time Reporting

#### Clarity

- Weekly hours
- Missing hours
- Submission status

#### Flex HRM

- Current balance
- Worked hours
- Leave information

### Documentation Hub

- Confluence
- Internal documentation
- Swagger endpoints
- Architecture diagrams
- Team wiki

### AI Assistant (Planned)

Examples:

```text
Show my Jira tickets

Show AKS pods in TEST

Open DTMS Swagger

Find authentication service logs

Show Key Vault secrets for QA

How many hours are missing in Clarity?
```

---

## 🏗️ Solution Architecture

```text
DsvDevOS

src
│
├── DsvDevOS.Web
│
├── DsvDevOS.Application
│
├── DsvDevOS.Domain
│
├── DsvDevOS.Infrastructure
│
├── DsvDevOS.AI
│
└── DsvDevOS.Shared
```

---

## 📂 Project Structure

### DsvDevOS.Web

Presentation layer.

Responsibilities:

- Blazor UI
- Pages
- Components
- Navigation
- User interactions

---

### DsvDevOS.Application

Application services and contracts.

Responsibilities:

- Interfaces
- Use cases
- Business workflows

Examples:

```csharp
IJiraService
IAzureService
IAksService
IFlexService
IClarityService
```

---

### DsvDevOS.Domain

Core business models.

Examples:

```csharp
JiraTicket
QuickLink
AksCluster
PodInfo
DashboardStats
```

---

### DsvDevOS.Infrastructure

External integrations.

Examples:

```text
Azure SDK
Jira API
Bitbucket API
Kubernetes
Key Vault
```

---

### DsvDevOS.AI

AI features and integrations.

Examples:

- Azure OpenAI
- Semantic Kernel
- Ollama
- Custom tools

---

### DsvDevOS.Shared

Common DTOs and contracts.

---

## 🛠️ Technology Stack

### Backend

```text
.NET 8
ASP.NET Core
Blazor Server
```

### UI

```text
MudBlazor
Bootstrap
```

### Cloud

```text
Azure
Azure Key Vault
Azure AD
Azure App Service
```

### DevOps

```text
Kubernetes
AKS
Docker
```

### AI

```text
Azure OpenAI
Semantic Kernel
Ollama
```

### APIs

```text
REST APIs
Microsoft Graph
Jira API
Bitbucket API
```

---

## 🚀 Getting Started

### Prerequisites

Install:

```bash
.NET 8 SDK
```

Verify:

```bash
dotnet --version
```

---

### Clone Repository

```bash
git clone https://github.com/your-user/DsvDevOS.git

cd DsvDevOS
```

---

### Create Solution

```bash
dotnet restore

dotnet build
```

---

### Run Application

```bash
dotnet run --project src/DsvDevOS.Web
```

Open:

```text
https://localhost:5001
```

---

## ⚙️ Configuration

Example:

```json
{
  "Portal": {
    "Links": [
      {
        "Name": "Jira",
        "Url": "https://jira.dsv.com",
        "Category": "Development"
      },
      {
        "Name": "Azure",
        "Url": "https://portal.azure.com",
        "Category": "Cloud"
      }
    ]
  }
}
```

---

## 🔒 Authentication Roadmap

### Phase 1

```text
Anonymous local usage
```

### Phase 2

```text
Azure AD Login
```

### Phase 3

```text
Role-based access
```

### Phase 4

```text
Team dashboards
```

---

## 🗺️ Roadmap

### v1.0

- [ ] Dashboard
- [ ] Quick Links
- [ ] Navigation
- [ ] Configuration Management

### v1.1

- [ ] Jira Integration
- [ ] Bitbucket Integration

### v1.2

- [ ] Azure Integration
- [ ] Key Vault Explorer
- [ ] Service Bus Explorer

### v1.3

- [ ] AKS Dashboard
- [ ] Pod Explorer
- [ ] Log Viewer

### v1.4

- [ ] Clarity Integration
- [ ] Flex HRM Integration

### v2.0

- [ ] AI Assistant
- [ ] Documentation Search
- [ ] Intelligent Recommendations

---

## 🌟 Future Ideas

### Developer Productivity

- Git shortcuts
- Release tracking
- Environment overview
- Swagger launcher
- API testing

### Monitoring

- Grafana
- Kibana
- Application Insights
- Splunk

### Collaboration

- Team dashboards
- Knowledge base
- Shared bookmarks

### AI Features

- Sprint summaries
- Ticket analysis
- Log investigation
- Documentation assistant
- Deployment insights

---

## 🤝 Contributing

This project is currently maintained as a personal productivity platform and experimentation space for improving development workflows.

Ideas, feedback, and improvements are always welcome.

---

## 📜 License

Private Internal Project

© DSV-Developer-Hub

---

## 💡 Motto

> Less tab switching. More development.
>
> One portal. One workflow. One DevOS.
