# Market Share Explorer 2.0 — historical extension (partial coverage)

The prior simplified edition is Market Share Explorer 1.0. This is a separate GitHub package; GPT sites were not changed.

## Verified extension
2019–20, 2020–21, and 2021–22 county homeschool enrollment, registered home school counts, and private enrollment were added from NC DOA annual reports for all 18 member counties. Together with existing data these series span 2019–20 through 2024–25. Source PDFs are in sources/.

## Remaining gaps
Earlier district final ADM, county public and charter/laboratory/regional totals, scholarship payments and recipients by county of residence, and compatible school-age population are NOT verified in this package. Earlier market shares are not calculated without all four components. These measures display “Not verified” before their available coverage; missing does not mean zero. The official interactive DPI portal was blocked by security verification during retrieval. Public availability does not establish that matching historical values have been recovered.

The 20 existing six-page district PDFs remain from 1.0 and cover the November 2026 registration profile plus 2022–23 through 2024–25 historical comparisons. They are explicitly labeled on the download button. Do not describe them as six-year reports.

## Navigation
Your county: current aggregate registration snapshot, map, historical summary. Trends & comparisons → 2019–20 onward: choose measure, start/end years, and inspect the six-year chart and county table. Existing sector, county, scholarship, population, and connection views retain their verified three-year coverage. Sources & methods describes coverage and links to original reports.

## GitHub Pages
Extract the ZIP and upload its contents to the repository root. Settings → Pages → Deploy from a branch → main → / (root). No build required. All assets use relative paths. No homeschool address records or registration CSVs are included. Existing repository files and history are not removed by uploading this package.

## Reproducibility
The embedded dataset in index.html and data.json match. Historical annual PDFs substantiate added values; historical-enrollment.csv exports all district views with blanks for unverified measures. Shared counties repeat across district views and must not be summed. Zero private enrollment is retained as published and is not proof of no private schooling.
