### AI-Powered Resume Screening Tool

This tool processes PDF resumes to extract text and calculates similarity scores against predefined categories like Project Management, Data Analytics, and Healthcare. It uses the BERT model for semantic analysis, tokenizes the text, and computes embeddings for both the resume text and category keywords. Similarity scores are calculated using cosine similarity. The results are visualized using pie charts and shortlisted based on aggregate scores. The solution is implemented using PyPDF2 for PDF extraction, BERT from Hugging Face for semantic analysis, and Tkinter for the GUI. The tool helps in automatically shortlisting candidates based on their alignment with job categories.

*Tech Stack:  Python, transformers, torch, pandas, numpy, matplotlib BERT.*
