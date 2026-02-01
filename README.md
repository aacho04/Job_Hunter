An AI-powered MCP (Model Context Protocol) server that automates:

 LinkedIn job searching

 Saving jobs to Excel

 Filtering by location

 Generating personalized cold emails

 Resume optimization (ATS-friendly)

 TXT → PDF resume conversion

 Gmail compose automation

Built using Python, async scraping, and FastMCP.

 Features
Job Automation

Search LinkedIn jobs programmatically

Persist results across sessions

Export results to Excel

Smart Resume Tools

Optimize resume for specific roles

Inject keywords + metrics

Auto-generate ATS-optimized resume files

Convert TXT resumes to PDF
 Cold Email Generator

Personalized role-based emails

Resume-skill-aware Gmail drafts

One-click email composing

 Tech Stack & Libraries Used
Purpose	Library
Environment variables	python-dotenv
Async HTTP requests	httpx
Web scraping	beautifulsoup4
Data handling	pandas
PDF generation	fpdf
MCP server	mcp.server.fastmcp
Async runtime	asyncio
📦 Installation
1️⃣ Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate     # Windows

2️⃣ Install dependencies
pip install python-dotenv httpx beautifulsoup4 pandas fpdf mcp lxml

3️⃣ Create .env file
# (Optional for future API keys)


(Already loaded using dotenv)

▶️ Run the MCP Server
python server.py


You should see:

JobAgent MCP Server starting...
Tools loaded:
1. search_jobs_on_linkedin
2. save_results_to_excel
3. filter_by_location
4. generate_role_based_email
5. improve_resume
6. open_gmail_compose
7. list_jobs
