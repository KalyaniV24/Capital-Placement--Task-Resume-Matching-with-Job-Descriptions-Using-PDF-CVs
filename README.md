Approach:

Data Preprocessing:
Extracted text from PDF-based resumes using PyMuPDF.
Tokenized and converted resumes and job descriptions into embeddings using DistilBERT.
Embedding Extraction:
Utilized DistilBERT to obtain embeddings for resumes and job descriptions.
Employed mean pooling to aggregate token embeddings into a single vector.
Similarity Calculation:
Computed cosine similarity between job description embeddings and resume embeddings.
Ranked resumes based on similarity scores for each job.


Challenges and Solutions:
PDF Text Extraction:
Extracting text from PDFs can be challenging due to various formats and encodings.
Solution: Overcame this by using PyMuPDF, which effectively extracted text from PDFs.
Efficient Processing:
Processing a large number of resumes and job descriptions efficiently.
Solution: Optimized processing by utilizing batching and parallelization.

Top 5 Candidates for Each Job:
For each job description, the top 5 candidates based on similarity scores were identified. Specific candidate names or detailed information cannot be provided due to privacy concerns.

Recommendations and Insights:
Personalized Candidate Shortlisting:
The approach facilitates personalized candidate shortlisting, aligning resumes with specific job descriptions.
Refining Matching Algorithms:
Fine-tuning similarity calculation methods based on domain knowledge can enhance the accuracy of candidate recommendations.
Integration with HR Systems:
Integrating this matching process into HR systems can automate and streamline candidate selection, improving recruitment efficiency.
