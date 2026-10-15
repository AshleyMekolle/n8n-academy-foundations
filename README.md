# n8n Academy: Foundations Program

All three courses of the official [n8n Academy](https://learn.n8n.io) Foundations program completed, with every hands-on project, its workflow file and documentation.

**12 workflows** across data transformation, API integrations, webhooks, sub-workflows, AI chains, AI agents and production error handling.

## Certificates

| Course | Certificate | Badge |
|---|---|---|
| **N8N101** Essentials: Your First Workflows | [View](certificates/N8N101-certificate.pdf) | [Verify](https://badges.n8n.io/e1b2e425-ee90-45e3-bb6c-2fd7b8bf7776#acc.dlxP0Koz) |
| **N8N102** Integrations: APIs & Connected Workflows | [View](certificates/N8N102-certificate.pdf) | [Verify](https://badges.n8n.io/19174a82-6324-44ae-b102-740ba6887095#acc.uQalkpRc) |
| **N8N103** In Practice: AI, Testing & Best Practices | [View](certificates/N8N103-certificate.pdf) | [Verify](https://badges.n8n.io/1bd00129-c0ac-498b-969f-d699da1b3f58#acc.4sWJjRUY) |

Certificates can be verified at [learn.n8n.io](https://learn.n8n.io).

## Projects

### [N8N101 Essentials](N8N101-essentials/)

| Project | What it shows |
|---|---|
| [Academy Registration](N8N101-essentials/README.md#1-academy-registration) | Authenticated HTTP requests with query parameters |
| [Sales Data Pipeline](N8N101-essentials/README.md#2-sales-data-pipeline) | Extract, transform and load across three branches: order totals, regional summary and a CSV report sent as binary data |

### [N8N102 Integrations](N8N102-integrations/)

| Project | What it shows |
|---|---|
| [API Integration Pipeline](N8N102-integrations/README.md#1-api-integration-pipeline) | Paginated API calls, joining two data sources, fallback data on error, batching, and routing with Switch |
| [Order Processing System](N8N102-integrations/README.md#2-order-processing-system-webhook-sub-workflow-and-report) | An authenticated webhook API with validation and 200/400 responses, a reusable sub-workflow with duplicate prevention, Data Table storage and status reporting |

### [N8N103 In Practice](N8N103-in-practice/)

| Project | What it shows |
|---|---|
| [AI Feedback Pipeline](N8N103-in-practice/README.md#1-ai-feedback-pipeline) | Two LLM chains with structured output: one classifies feedback, the other writes a reply matched to that classification |
| [Customer Service AI Agent](N8N103-in-practice/README.md#2-customer-service-ai-agent) | A chat agent that chooses between three API tools and fills their parameters from the conversation |
| [Error Handling and Monitoring System](N8N103-in-practice/README.md#3-error-handling-and-monitoring-system) | Retries for unreliable APIs, deliberate failure testing and a central error workflow that reports failures |
| [Fixed Broken Workflow](N8N103-in-practice/README.md#4-fixed-broken-workflow) | Diagnosing and fixing three bugs: missing authentication, a wrong join key and a reference to a deleted node |

## Repo structure

```
n8n-academy-foundations/
├── certificates/
├── N8N101-essentials/
│   ├── README.md
│   ├── workflows/       # exported workflow JSON
│   └── screenshots/
├── N8N102-integrations/
│   └── ...
└── N8N103-in-practice/
    └── ...
```

Each course folder has its own README that explains how each workflow works, which nodes it uses and what I learned.

## Importing a workflow

1. In n8n, create a new workflow.
2. Open the **...** menu, choose **Import from File**, and select a JSON file from any `workflows/` folder.
3. Connect your own credentials. No credentials, API keys or personal IDs are stored in this repo. Placeholders such as `YOUR_ASSESSMENT_ID` mark where your own values go.

The endpoints belong to the n8n Academy practice API, so most workflows need an Academy account to run as they are. The patterns themselves apply to any API.

## Where I apply this

I build workflow automations, API integrations and back-end services for businesses. This includes [Dispatch](https://github.com/AshleyMekolle/Dispatch-AI), a platform that automates business processes from a single prompt, as well as client workflows in n8n, Make and Zapier.

## Contact

**Mekolle Ashley** | Automation & Back-End Developer
[GitHub](https://github.com/AshleyMekolle) | Mekolleashleyam@gmail.com
