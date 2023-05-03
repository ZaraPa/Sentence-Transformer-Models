# Sentence Transformer Models
###### Analyzing CVS using all-MiniLM models

<p align="justify">
This project efficiently processes multiple resumes in docx format and extracts crucial information, such as name, email, education, experience, additional skills, awards, licenses and certificates, and languages. The process is executed through a for loop, which iterates over each line in each document and applies various heuristics to determine the relevant category, such as checking for specific keywords or using cosine similarity between the line and category keywords.

The extracted information is then saved in a CSV file, and the relevant lines are highlighted with color-coded tags in the original document for better visualization, implemented with Python's python-docx library. The code also handles some minor formatting and parsing issues, such as removing underscores and hyphens from the name field, splitting and highlighting the email field, and writes the resulting modified document to a new file.
Finally, the code saves the extracted information in a CSV file, which is then downloaded to the local machine for further processing.
</p>
