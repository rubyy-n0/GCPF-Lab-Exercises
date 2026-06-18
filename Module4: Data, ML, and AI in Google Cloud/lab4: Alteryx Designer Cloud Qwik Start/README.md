# Alteryx Designer Cloud: Qwik Start (GSP105)

## Objective
To learn how to use Alteryx Designer Cloud (Dataprep) to import, clean, transform, join, and analyze datasets using a visual data preparation tool.

## Key Steps Performed
1. Created a Cloud Storage bucket for storing datasets.
2. Initialized Cloud Dataprep (Alteryx Designer Cloud).
3. Created a new flow named "FEC-2016".
4. Imported datasets:
   - Candidate Master 2016
   - Campaign Contributions 2016
5. Cleaned and transformed the Candidate Master dataset:
   - Filtered data by date range
   - Fixed mismatched column data types
   - Filtered presidential candidates (P)
6. Cleaned Contributions dataset using Wrangle transformation.
7. Joined Candidate and Contributions datasets using join keys.
8. Aggregated data using pivot:
   - Sum, average, and count of contributions
9. Renamed columns for clarity.
10. Rounded numeric values for readability.

## Tools / Services Used
- Alteryx Designer Cloud (Dataprep)
- Google Cloud Storage
- Cloud Shell
- Data Wrangling (Wrangle Language)
- Data Flow Builder

## Results
Successfully prepared, cleaned, and joined two datasets. Generated a structured summary of US presidential campaign contributions including total, average, and count metrics.
