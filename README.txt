# Polling clients via Telergam bot for n8n

## Overview
This repository provides an open-source n8n automation workflow for polling clients of any service company based on CRM in Google Sheet aiming to manage services reservation with less time spending for Client Administrator.  
Free for public use with author attribution (see License section).

**Key features:**
- Plug-and-play n8n workflow (`TG-bot-clients-poll.json`)
- Step-by-step import instructions
- Secure credential placeholders
- Readable code comments and documentation
- MIT License (for code/workflow) and CC BY 4.0 License (for documentation/screenshots)

## Quick Start

1. **Import workflow into n8n:**  
   - Download `TG-bot-clients-poll.json`.
   - Go to n8n, click "Import workflow" and upload the file.

2. **Setup environment variables and credentials:**  
   - Create required credentials in n8n, using placeholders from `TG-bot-clients-poll.json`.
   - Set environment variables if needed (see `.env.example`).

3. **Run and test:**  
   - Activate the workflow.
   - Test processing with sample data (see `/examples` folder if provided).

## Requirements

- n8n (self-hosted or cloud)
- Accounts/credentials for [your integrations Telegram & Google Sheets]

## Author & License

- **Author:** [Denis Panasenko, https://github.com/dpanasenko-tech/]
- **Copyright:** (c) 2025 [Denis Panasenko]
- **License:**  
  - Code and workflow JSON — [MIT License](./LICENSE)
  - Documentation and screenshots — [Creative Commons BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Please attribute original author in public forks and projects.

## Feedback & Contributions

- Issues, bugs or feature requests: use [GitHub Issues](../../issues)
- Ask questions and discuss: [n8n Community thread](впишите ссылку)
- Pull Requests welcome!

## Folder structure
your Google Cloud folder
