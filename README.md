# Hi, I'm Yigit

I build AI agents and automated workflows: voice agents that answer calls and book appointments, document agents that read and file paperwork, and the automations around them. Before that, 15 years of delivering software as a technical project manager (PMP, PSM I, PSPO I).

Most client code is private. Here is what it does.

## Selected builds

**Accounting office voice and messaging agent**  
Reads incoming PDFs (tax returns, trial balances, invoices, payroll documents, including scanned copies), identifies the document type, client and period, and files each one to the right client. Anything it is not sure about goes to a review queue with the reason written next to it. Also sends scheduled reminders for missing documents.  
Python, FastAPI, Vapi, ElevenLabs, Telegram, SQLite, OCR. Deployed on Railway. 948 automated tests.

**Car service booking voice agent**  
Answers the call, collects the customer's details and the reason for the visit, checks open slots and books the appointment into the calendar. Speaks Turkish.  
Vapi, ElevenLabs, Make webhooks, Cal.com.

**E-commerce operations and finance panel**  
Inventory, purchase invoices, sales and alerts for a marketplace store, with scheduled jobs pulling data in the background.  
TypeScript, Cloudflare Pages, Hono, Cron Workers, D1, R2. About 245 automated tests.

**[PathMate V3](https://github.com/yigitaydemirr/pathmatev3): a Claude Code subagent team**  
Six specialised agents (project manager, business analyst, UI designer, React Native developer, Supabase developer, QA engineer) that take a module from task to tested code, with progress tracked in Notion.

**AI workflows**  
Meeting notes to tasks: Fireflies transcript, Claude extracts decisions and action items, tasks written to ClickUp through MCP.  
Email to spreadsheet: Zapier and ChatGPT extract fields from incoming emails into Excel.

## Currently

Fine-tuning a Turkish text-to-speech model on Hugging Face.

## Tools I work with

Vapi, ElevenLabs, Deepgram, Claude, OpenAI, Claude Code, MCP, Make, Zapier, Python, FastAPI, TypeScript, Cloudflare, Railway, Supabase, Notion, ClickUp, Jira
