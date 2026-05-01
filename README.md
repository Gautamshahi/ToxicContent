# ToxicContent
A repository for literature review on toxic content

# 📚 Literature Review Process for Hate Speech Datasets

This repository documents a structured methodology for collecting, analyzing, and organizing datasets used in hate speech and toxic content research.

The aim is to standardize dataset comparison across research papers.

---

## 🔍 Overview

Each dataset is analyzed using a consistent schema that captures:

- Dataset metadata  
- Language and geographic context  
- Data collection process  
- Annotation methodology  
- Classification models and performance  

---

## 📊 Dataset Schema

| Element | Description | Example | Comments |
|--------|------------|--------|---------|
| Dataset Number | Unique dataset ID | HS1 | Alphanumeric |
| Year | Publication year | 2010 |  |
| Dataset Name | Dataset name (if available) | Online Harassment Dataset |  |
| Platform | Source platform | Twitter |  |
| Language | Language of dataset| English |  |
| Dataset Available | Availability | Yes |  |
| Dataset Available At | Dataset link | URL |  |
| Multimodal | Data type | Text / Text+Image | Yes/No |
| Evaluated In | Papers using dataset | Paper link |  |
| Count of Evaluated Papers | Number of papers | 3 | Derived |
| Hatebase.org Used | Hatebase usage | Yes |  |
| Time Period | Data collection time | 23-04-2020 to 23-06-2020 |  |
| Hashtags/Keywords Used | Data queries | #MeToo |  |
| Name of Positive Class | Label names | Hate / Offensive |  |
| Hate Speech Definition | Definition in paper | "We define..." |  |
| Definition of Other Classes | Multi-class definitions | Offensive language |  |
| Data Crawling Process | Collection method | Tweepy API |  |
| Topics Focused 1 | Main topic of hate  | Racism |  |
|General Info | Additional notes | - |  |
| Full Dataset Size | Total data collected | 20,000 |  |
| Annotated Dataset Size | Labeled data size | 1,000 | Important |
| Amount of Hate Words | Hate lexicon size | 345 (German) |  |
| Data Sparsity | Sparse data issue | - | Optional |
| Annotation Guidelines Available | Guidelines shared? | Yes |  |
| Annotation Guidelines | Link/text | URL |  |
| Annotation Type | In-house / Crowdsourcing | AMT |  |
| Number of Annotators | Annotator count | 2 |  |
| Annotation Quality Mentioned | Agreement reported | Yes |  |
| Annotation Measure | Metric used | Cohen’s Kappa (0.86) |  |
| Classification Model Used | Model type | SVM / BERT |  |
| Performance | Best accuracy | 89% |  |
| Comments on Results | Observations | - |  |

---

## 🧠 Methodology

### 1. Paper Collection
- Use sources such as:
  - Google Scholar  
  - Springer  
  - AIS eLibrary  
- Apply keyword search (e.g., *hate speech detection*, *toxic content*)

### 2. Screening
- Remove duplicates  
- Filter irrelevant papers  
- Focus on dataset-related studies  

### 3. Data Extraction
- Extract dataset details using the schema above  
- Verify dataset availability via paper or external search  

### 4. Annotation Analysis
- Identify annotation type:
  - Crowdsourcing (e.g., AMT)
  - In-house annotation  
- Record agreement metrics (e.g., Cohen’s Kappa)

### 5. Model & Performance Review
- Document classification models:
  - SVM  
  - Deep Learning models (e.g., BERT)  
- Record best reported performance  

---

## 📁 Repository Structure
### Papers
- Provides the list of papers used in the study

