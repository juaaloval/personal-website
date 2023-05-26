---
title: "Automated Generation of Realistic Test Inputs for Web APIs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Juan C. Alonso

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-08-01T00:00:00Z"
doi: "10.1145/3468264.3473491"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 29th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering* August 23–28, 2021, Athens, Greece
publication_short: In *ESEC/FSE 2021 Student Research Competition*

abstract: Testing web APIs automatically requires generating input data values such as addressess, coordinates or country codes. Generating meaningful values for these types of parameters randomly is rarely feasible, which means a major obstacle for current test case generation approaches. In this paper, we present ARTE, the first semantic-based approach for the Automated generation of Realistic TEst inputs for web APIs. Specifically, ARTE leverages the specification of the API under test to search for meaningful test inputs for the API parameters in knowledge bases like DBpedia. Our approach has been integrated into RESTest, a state-of-the-art tool for API testing, achieving an unprecedented level of automation which allows to generate up to 100% more valid API calls than existing fuzzing techniques, 30% on average. Evaluation results on a set of 26 real-world APIs show that ARTE can generate realistic inputs for 7 out of every 10 parameters, outperforming related approaches.

# Summary. An optional shortened abstract.
summary: Testing web APIs automatically requires generating input data values such as addressess, coordinates or country codes. Generating meaningful values for these types of parameters randomly is rarely feasible, which means a major obstacle for current test case generation approaches. In this paper, we present ARTE, the first semantic-based approach for the Automated generation of Realistic TEst inputs for web APIs. Specifically, ARTE leverages the specification of the API under test to search for meaningful test inputs for the API parameters in knowledge bases like DBpedia. Our approach has been integrated into RESTest, a state-of-the-art tool for API testing, achieving an unprecedented level of automation which allows to generate up to 100% more valid API calls than existing fuzzing techniques, 30% on average. Evaluation results on a set of 26 real-world APIs show that ARTE can generate realistic inputs for 7 out of every 10 parameters, outperforming related approaches.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
- arteSrc

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: arteSrc
---
