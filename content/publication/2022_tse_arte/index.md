---
title: "ARTE: Automated Generation of Realistic Test Inputs for Web APIs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Juan C. Alonso
- Alberto Martin-Lopez
- Sergio Segura
- Jose Maria Garcia
- Antonio Ruiz-Cortes

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2022-02-14T00:00:00Z"
doi: "10.1109/TSE.2022.3150618"

# Schedule page publish date (NOT publication's date).
# publishDate: "2021-08-01T00:00:00Z" # TODO: Update

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Software Engineering*
publication_short: In *IEEE TSE 2022*

abstract: Automated test case generation for web APIs is a thriving research topic, where test cases are frequently derived from the API specification. However, this process is only partially automated since testers are usually obliged to manually set meaningful valid test inputs for each input parameter. In this article, we present ARTE, an approach for the automated extraction of realistic test data for web APIs from knowledge bases like DBpedia. Specifically, ARTE leverages the specification of the API parameters to automatically search for realistic test inputs using natural language processing, search-based, and knowledge extraction techniques. ARTE has been integrated into RESTest, an open-source testing framework for RESTful APIs, fully automating the test case generation process. Evaluation results on 140 operations from 48 real-world web APIs show that ARTE can efficiently generate realistic test inputs for 64.9% of the target parameters, outperforming the state-of-the-art approach SAIGEN (31.8%). More importantly, ARTE supported the generation of over twice as many valid API calls (57.3%) as random generation (20%) and SAIGEN (26%), leading to a higher failure detection capability and uncovering several real-world bugs. These results show the potential of ARTE for enhancing existing web API testing tools, achieving an unprecedented level of automation.

# Summary. An optional shortened abstract.
summary: Automated test case generation for web APIs is a thriving research topic, where test cases are frequently derived from the API specification. However, this process is only partially automated since testers are usually obliged to manually set meaningful valid test inputs for each input parameter. In this article, we present ARTE, an approach for the automated extraction of realistic test data for web APIs from knowledge bases like DBpedia. Specifically, ARTE leverages the specification of the API parameters to automatically search for realistic test inputs using natural language processing, search-based, and knowledge extraction techniques. ARTE has been integrated into RESTest, an open-source testing framework for RESTful APIs, fully automating the test case generation process. Evaluation results on 140 operations from 48 real-world web APIs show that ARTE can efficiently generate realistic test inputs for 64.9% of the target parameters, outperforming the state-of-the-art approach SAIGEN (31.8%). More importantly, ARTE supported the generation of over twice as many valid API calls (57.3%) as random generation (20%) and SAIGEN (26%), leading to a higher failure detection capability and uncovering several real-world bugs. These results show the potential of ARTE for enhancing existing web API testing tools, achieving an unprecedented level of automation.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/9712422'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- arteTSE

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: arteSrc
---
