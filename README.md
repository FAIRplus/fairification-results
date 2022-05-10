# fairification-results

A webside showing all FAIR assessment results.
Please view the FAIRification results here: [https://fairplus.github.io/fairification-results/](https://fairplus.github.io/fairification-results/)

## How to release FAIR assessment results from Google sheets
> :bulb: The FAIRification result page is a static website for publishing FAIR assessment results. 
> If you'd like to add more features to this website, please send a pull request.

****Step 1:** Clean up the FAIR assessment results**

    A complete FAIR assessment result should include:
    - link to pre/post FAIRification datasets
    - dates for the assessment 
    - members of the assessment team
    - version of the indicators
Please copy the summarised version to [this summary spreadsheet](https://docs.google.com/spreadsheets/d/1mMsYygU0d0SWbxeVXKDNou1T-cvJHhfo_JqnowkoQjI/edit#gid=455218470)
(Please access using your FAIRplus account)

**Step 2: Format the Google sheets**

Metadata on top of each sheet should be updated.

**Step 3: Convert to HTML**

In the Google sheet, select `File`->`Download` -> `Web page(HTML)`

**Step 4: Publish the HTML page**

1. Rename the HTML file, following the `yyyy-mm-dd-name.html` pattern, e.g. `2019-12-17-ND4BB-post-assessment.html`
2. Move the files under the `_posts` folder

**Step 5: Update the indexing homepage**

Update the table in `index.html`



