# AI Business Research Agent
### Chettinad CodeFest 2026 — Grand Final Submission

## Objective
An AI-powered research agent that finds, verifies, organizes, and summarizes 
business information from publicly available internet sources.

## How It Works
The agent follows a multi-step pipeline:
1. Query Agent — understands business type and location
2. Search Agent — searches DuckDuckGo across 7 query variations
3. Source Classification Agent — categorizes each source
4. Business Discovery Agent — extracts businesses from Official and Directory sources
5. Deduplication Agent — removes duplicate records using RapidFuzz
6. Verification Agent — assigns confidence scores
7. Contact Information Agent — extracts phone, email, address
8. Research Summary Agent — generates professional report using Gemini AI

## Technologies Used
- Python (Google Colab)
- Google Gemini AI (google-genai)
- DuckDuckGo Search (ddgs)
- BeautifulSoup4
- RapidFuzz
- Pandas

## Example Queries
- Neurologists in Minnesota
- Cardiologists in Birmingham


## How to Run
1. Open the notebook in Google Colab
2. Add your GEMINI_API_KEY to Colab Secrets
3. Run all cells
4. Call run_agent("your query here")
