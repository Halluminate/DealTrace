# Mock deal packages (illustrative only)

> [!IMPORTANT]
> **These files are a mock, provided only as an illustrative example.**
>
> They are **not** the dataset used in the DealTrace paper, and they are **not**
> a sample, subset, extension, or de-identified version of it. They were not used
> to produce any result reported in the paper. Results obtained on these files
> are not comparable to the paper's results and should not be reported as
> results on the DealTrace benchmark.
>
> The paper's deal packages are confidential and are not distributed.

## Purpose

These three invented deal packages show the kind of input DealTrace works with:
a financial model in Excel accompanied by the documents an analyst would receive
with it. They let you inspect the file formats and run the pipeline end to end.
Every company, person, place, product and figure in them is fictional.

## Contents

| Folder | Files | Deal type |
|---|---|---|
| `Project Kestrel/` | Confidential information memorandum (69 pages), LBO model (22 tabs), model printout (8 pages) | Sponsor buyout of a manufacturer |
| `Orivane Clinical Laboratories/` | Confidential information memorandum, slide format (40 pages), sell-side diligence model (8 tabs) | Sale of a clinical laboratory |
| `Project Dunecrest/` | Transaction teaser (48 pages), two management presentations, macroeconomic note, fund quarterly report, transaction model (15 tabs) | GP-led continuation fund holding two companies |

Each PDF has a `.txt` file beside it containing the page text and a description
of each chart, generated with Claude Opus 4.7.

## How the files were made

- The files were generated from written specifications. The documents follow
  the general layout of real deal documents of each type (section order, page
  layouts, exhibit types); all content is invented.
- Figures in each package's documents are taken from its model, so each package
  is internally consistent.
- Names were checked against real companies, funds and people and replaced
  wherever they coincided. Images are placeholder boxes, email addresses use the
  `.example` domain, telephone numbers use the 555 range, and locations are
  generic ("Country A", "State A").
- The generated documents and models were checked against the confidential
  source materials for shared names and figures; none were found.
- The workbooks contain live formulas. Their stored values were computed with
  LibreOffice so the files can be read programmatically without Excel.
