# 🌐 Module 3 – Data Acquisition & Persistence Layer

This repo is part of the **MedEd-AI Builder Phase 1 Plan**, focused on acquiring structured NEET content from websites and storing it efficiently in a local database. It acts as the **data ingestion layer** for NEETPrepGPT — feeding raw study material into the system.

---

## 🚀 What You'll Learn

### 🕸️ Web Scraping Mastery
- Sending requests with `requests` + headers/user-agents
- Parsing HTML with `BeautifulSoup4`
- Navigating DOM using tags, classes, and CSS selectors
- Handling challenges like:
  - IP blocks
  - robots.txt
  - dynamic content
- Intro to `Selenium` (if needed for JS-heavy pages)

### 🗃️ Database Integration with SQLAlchemy
- SQL fundamentals: `SELECT`, `INSERT`, `UPDATE`, `DELETE`
- Designing schema for NEET data:
  - chapters, sections, topics, difficulty levels
- SQLAlchemy Core & ORM:
  - Declarative base models
  - Sessions
  - CRUD operations
- Connecting with FastAPI using `Depends()`

---



