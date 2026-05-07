# n8n AI Automations

A collection of n8n workflow automations built for AI-powered business processes, CRM integrations, lead generation, and intelligent chatbots.

## Workflows

### CRM & Sales Automation
| Workflow | Description |
|----------|-------------|
| `iconic-mortgage-workflow.json` | AI Hot Lead Follow-Up system for Iconic Mortgage using Salesforce triggers |
| `Close CRM Automation Tory.json` | Close CRM automation workflow for contact and lead management |
| `close_crm_automation_workflow.json` | Automated Close CRM pipeline with deal tracking |
| `close_crm_workflow.json` | Close CRM integration workflow |
| `close_crm_workflow 1 .json` | Close CRM workflow variant |
| `fixed_close_workflow.json` | Fixed/improved Close CRM automation |
| `n8n_close_crm_workflow.json` | n8n-native Close CRM integration |

### AI Agents & Chatbots
| Workflow | Description |
|----------|-------------|
| `AI Agent for youtube Video automation.json` | AI agent that automates YouTube video content workflows |
| `Linkdinn AI agent automation.json` | LinkedIn post creator agent with form-based input |
| `Web Browsing AI agent Chatbot.json` | AI chatbot with web browsing capabilities |
| `RAG_Website_Chatbot.json` | RAG-based website chatbot using LangChain nodes |
| `n8n_chatmsg_openai_workflow.json` | Chat messaging workflow powered by OpenAI |

### Lead Generation & Outreach
| Workflow | Description |
|----------|-------------|
| `Business Lead Generation with Apify Web Scraping and Google Sheets Storage.json` | Web scraping leads with Apify and storing in Google Sheets |
| `AI hot_lead_follow_up_workflow.json` | AI-powered hot lead follow-up automation |
| `Email Sending Agent automation.json` | Automated email sending agent for outreach |

### Voice AI & Scheduling
| Workflow | Description |
|----------|-------------|
| `Automate Call Scheduling with Voice AI Receptionist using Vapi, Google Calendar & Airtable.json` | Voice AI receptionist for call scheduling with Vapi, Google Calendar, and Airtable integration |

### General Workflows
| Workflow | Description |
|----------|-------------|
| `My_workflow_2.json` | General-purpose n8n workflow |
| `n8n_workflow.json` | Base n8n workflow template |

## Project Structure

```
n8n-ai-automations/
├── README.md
├── workflows/          # All n8n workflow JSON files
│   ├── AI Agent for youtube Video automation.json
│   ├── AI hot_lead_follow_up_workflow.json
│   ├── Automate Call Scheduling with Voice AI Receptionist...json
│   ├── Business Lead Generation with Apify...json
│   ├── Close CRM Automation Tory.json
│   ├── Email Sending Agent automation.json
│   ├── iconic-mortgage-workflow.json
│   ├── Linkdinn AI agent automation.json
│   ├── RAG_Website_Chatbot.json
│   ├── Web Browsing AI agent Chatbot.json
│   └── ... (26 total workflows)
└── images/             # Screenshots and diagrams
```

## How to Use

1. **Import a workflow** into your n8n instance:
   - Open n8n dashboard
   - Go to **Workflows** > **Import from File**
   - Select any `.json` file from the `workflows/` folder

2. **Configure credentials**: Each workflow may require API credentials (Salesforce, Close CRM, OpenAI, Google Sheets, Vapi, etc.). Set them up in **Settings** > **Credentials**.

3. **Activate the workflow** once credentials are configured.

## Tech Stack & Integrations

- **n8n** - Workflow automation platform
- **OpenAI / LangChain** - AI/LLM capabilities
- **Salesforce** - CRM triggers and lead management
- **Close CRM** - Sales pipeline automation
- **Google Sheets** - Data storage
- **Google Calendar** - Scheduling
- **Airtable** - Database management
- **Vapi** - Voice AI
- **Apify** - Web scraping
- **LinkedIn** - Social media automation
- **YouTube** - Video content automation

## Author

**Awais Khan**  
AI/Automation Developer

## License

This project is open source and available for learning and reference purposes.
