# COENG-20203: Supplemental materials

Supplemental materials for **Mapping Methods and Applications in Construction Project Management Analytics**.

**Authors:** Filippo Maria Ottaviani, Gabriel Castelblanco, Timur Narbaev, and Alberto De Marco.

**Associated manuscript:** COENG-20203, Journal of Construction Engineering and Management.

This package contains the supplemental materials prepared for the first revision, dated November 18, 2026.

## Files

| Material | File | Contents |
| --- | --- | --- |
| S1 | [Coding prompt](Supplemental_Material_S1_Coding_Prompt.txt) | The fixed contextual-coding prompt, taxonomy labels, method-to-family crosswalk, evidence rules, and output schema. |
| S2 | [Pathway map](Supplemental_Material_S2_Pathway_Map.xlsx) | A filterable workbook containing all 1,387 retained paper-specific links, source identifiers and passages, a worked example, and annual family counts and share formulas. |
| S3 | [Annual family-share figures](Supplemental_Material_S3_Annual_Family_Shares.pdf) | Annual shares for all ten analytical families in the complete years 2015-2025, using two denominators. |

## Using the pathway map

The manuscript's heatmaps give a quick overview of concentrated and less-explored family-domain and family-purpose relationships. The S2 workbook identifies the actual family-domain-purpose combinations reported together in individual studies and provides the passages supporting them.

1. Download S2 and open the **Pathways** worksheet in a spreadsheet application.
2. Use the column filters to select a family or practice, performance domain, managerial purpose, year, or textual evidence tier. Use Find to search titles, method names, and passages.
3. Read the reported study action and supporting abstract passages. Use the DOI or source URL to locate the paper and assess its data requirements, project setting, and validation.
4. Consult the **Guide** worksheet for field definitions and a worked example. Filtering for ML/DL, cost and budget, and estimation and forecasting returns 44 papers.

The map contains 1,387 retained links in 578 of the 780 included abstracts, representing 424 distinct family/practice-domain-purpose combinations. Each paper contributes at most once to a given combination.

## Reading the annual shares

S3 shows two sets of annual plots:

- **Figure S1:** papers applying a family divided by all distinct paper-family assignments in that year.
- **Figure S2:** papers applying a family divided by all included abstracts in that year.

Each paper counts once per analytical family. Management practice systems are excluded from these plots. The **Annual shares** worksheet in S2 supplies the numerators, denominators, and spreadsheet formulas for 2015-2026. The partial year 2026 is labeled separately and omitted from the complete-year plots in S3. Small annual counts can produce substantial year-to-year fluctuations.

## Interpretation

These materials describe applications reported in the retrieved titles and abstracts. The contextual links are language-model judgments inspected qualitatively by the authors, without a systematic human-coded accuracy estimate. Supporting passages make the judgments inspectable; they do not establish semantic accuracy, method effectiveness, or a confirmed field-wide research gap.

S2 is a fixed export of the primary analysis (dataset B). Its share formulas respond to the annual count cells; editing individual Pathways rows does not rebuild those counts.

## Citation

Please cite the associated manuscript and identify the repository version or commit used. Citation metadata for these supplemental materials is provided in [CITATION.cff](CITATION.cff).
