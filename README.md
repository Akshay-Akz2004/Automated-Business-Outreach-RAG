This project focuses on building an automated business outreach tool to assist software services companies in streamlining their client outreach. 
The system uses advanced techniques in Natural Language Processing (NLP), Deep Learning (DL), and Machine Learning (ML) to generate personalized outreach emails based on job descriptions extracted from client career portals.

The process begins by scraping job descriptions from client portals using the LangChain framework. Once extracted, the job descriptions are embedded into a vector space. Each job description, D, and associated skills, S, are represented as k-dimensional vectors in ℝ^k stored in chromaDB. 
These vector representations allow the system to understand the semantics of the job posting.
