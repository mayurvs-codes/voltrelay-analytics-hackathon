# VoltRelay Energy: what drives service failures, rider churn and margin erosion?

Submission for the **Gradient Learnings Data Analytics Hackathon** (November 2026).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mayurvs-codes/voltrelay-analytics-hackathon/blob/main/1_VoltRelay_Analysis_Notebook.ipynb)

## Files

| File | What it is |
|---|---|
| [`1_VoltRelay_Analysis_Notebook.ipynb`](1_VoltRelay_Analysis_Notebook.ipynb) | Colab notebook: data understanding, cleaning, analysis of the six core questions, the expansion and budget question, and recommendations. Runs top to bottom. |
| [`2_VoltRelay_Analysis_Report.pdf`](2_VoltRelay_Analysis_Report.pdf) | 6-page analysis report (an editable `.docx` copy is included). |
| [`3_VoltRelay_Video_transcript.md`](3_VoltRelay_Video_transcript.md) | Transcript of the 3-minute video. |

## How to run

Click **Open in Colab** above, then choose **Runtime → Run all**. The first cells install any missing packages and download the organizer's dataset (8 CSVs, about 840 MB) from the shared Google Drive folder. No login is needed. A standard Colab runtime is enough (peak RAM is about 6 GB).

## Key findings

1. **Heat-stressed Gen1 cabinets.** At 45°C a Gen1 cabinet takes 209 minutes to charge a pack instead of 88. The 36 Gen1 stations in Jaipur, Delhi NCR and Hyderabad cause 58% of all summer failures.
2. **A defective battery batch.** 1,385 Kyron 2W packs added in Sep 2024 lose health 3.2× faster than other packs. Wear costs ₹103 per Kyron swap against ₹32, which is the main reason contribution per swap turned negative.
3. **The ZipDrop re-contract.** The largest fleet partner's discount went from 12% to 28% with no peak surcharge, making it the most loss-making 2W account (about −₹20 to −₹22 per swap).
4. **New-rider churn** is driven by first-month failure rate and delivered range, not by price or competitors.

**Recommendation:** spend the next budget on upgrading the 36 hotspot cabinets and replacing the Kyron cohort, not on new stations or more batteries. Re-price ZipDrop before any exclusive deal, and roll out peak pricing as a margin measure.

## AI use disclosure

Claude (Anthropic) was used as an assistant for the code, analysis and writing. The disclosure is also stated in the notebook and the report.
