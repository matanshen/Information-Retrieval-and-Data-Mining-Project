# Data Mining Project and Information Retrieval

## Objective
This project applies a complete data mining and information retrieval workflow to analyze textual data. It focuses on generating vector representations, implementing information retrieval models, and evaluating their performance.

---

## Workflow Overview

### Part 1: Data Preparation and Feature Representation
1. **Data Loading and Preprocessing**:
   - **Files**:
     - `all_docs_14.jsonl`: A collection of 3,000 documents with metadata including document ID, title, and abstract.
     - `queries_14.jsonl`: A set of 5 queries with additional context and search needs.
     - `qrel_14.jsonl`: Relevance judgements linking queries to relevant document IDs.
   - **Tasks**:
     - Load and preprocess the document collection and queries.
     - Parse relevance judgements to create query-document pairs.

2. **Vector Representations**:
   - **Techniques**:
     - Binary vector representation captures presence/absence patterns.
     - CO vector representation highlights co-occurrence relationships in the text.
     - TF-IDF vector representation emphasizes term importance relative to the corpus.
   - **Tasks**:
     - Generate vectorized representations for both corpus and queries.
   - **Deliverables**:
     - Feature vectors prepared for retrieval tasks.

3. **Documentation**:
   - **File**:
     - `Specification Document (based on all parts).docx`
   - **Tasks**:
     - Define project objectives and preprocessing techniques.
     - Detail methodologies for feature representation.
     - Summarize insights into retrieval model utility and performance.

### Part 2: Information Retrieval Models
1. **Feature Analysis**:
   - **File**:
     - `Data_mining_&_IR_project_All_parts_Final_Updated_Version_Assigment_By_Matan_Shemesh_Nimetz.ipynb`
   - **Tasks**:
     - Explore vectorized data to identify patterns and trends.
     - Understand the distribution of features for retrieval tasks.

2. **Model Development**:
   - **File**:
     - `Data_mining_&_IR_project_All_parts_Final_Updated_Version_Assigment_By_Matan_Shemesh_Nimetz.ipynb`
   - **Tasks**:
     - Implement information retrieval models.
     - Rank and retrieve relevant documents based on query matching.
     - Evaluate model performance using precision, recall, and F1-score.

3. **Presentation**:
   - **File**:
     - `Data mining and information retrival project summary - Matan Shemesh Nimetz.pptx`
   - **Tasks**:
     - Summarize results and project insights.
     - Present findings in a concise and stakeholder-friendly format.

---

## Dataset
- **Source**: Textual data processed for information retrieval tasks.
- **Files**:
  - `all_docs_14.jsonl`: Document collection with metadata.
  - `queries_14.jsonl`: Query set with context and needs.
  - `qrel_14.jsonl`: Relevance judgements for evaluation.
  - Vectorized files derived using Binary, CO, and TF-IDF representations.

---

## Deliverables
1. Intermediate datasets with feature vectors:
   - Binary, CO, and TF-IDF representations.
2. Analytical insights and model performance metrics.
3. Final presentation summarizing findings.
4. Specification document detailing methodologies and results.

---

## Tools and Libraries
- **Languages**: Python
- **Libraries**: pandas, numpy, matplotlib, scikit-learn, nltk
- **Tools**: Jupyter Notebook, PowerPoint, Document Readers

---

## Acknowledgments
This is the final project from "Data Mining and Information Retrieval course.
