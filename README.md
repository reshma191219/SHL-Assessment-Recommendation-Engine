# SHL-Assessment-Recommendation-Engine
This project implements a semantic recommendation engine for SHL assessments using a Retrieval-Augmented Generation (RAG) pipeline with Gemini embeddings. The system processes a catalog of assessments and enables users to retrieve the most relevant assessments based on a query or requirement.

Data Collection

The assessment data was scraped from the SHL Product Catalog using requests and BeautifulSoup and scrape all 366 assements data:

Source: https://www.shl.com/solutions/products/product-catalog/

Fields Extracted:
data-entity-id
Assessment Name
Relative URL
Remote Testing
Adaptive/IRT
Test Type
Assessment Length (seperate logic)
