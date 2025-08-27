---
title: "SATORI: Static Test Oracle Generation for REST APIs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Juan C. Alonso
- Alberto Martin-Lopez
- Sergio Segura
- Gabriele Bavota
- Antonio Ruiz-Cortes

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2025-08-22T00:00:00Z"
doi: "10.48550/arXiv.2508.16318"

# Schedule page publish date (NOT publication's date).
# publishDate: "2021-08-01T00:00:00Z" # TODO: Update

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/ACM International Conference on Automated Software Engineering (ASE) 2025*
publication_short: In *IEEE/ACM ASE 2025*

abstract: "REST API test case generation tools are evolving rapidly, with growing capabilities for the automated generation of complex tests. However, despite their strengths in test data generation, these tools are constrained by the types of test oracles they support, often limited to crashes, regressions, and noncompliance with API specifications or design standards. This paper introduces SATORI (Static API Test ORacle Inference), a black-box approach for generating test oracles for REST APIs by analyzing their OpenAPI Specification. SATORI uses large language models to infer the expected behavior of an API by analyzing the properties of the response fields of its operations, such as their name and descriptions. To foster its adoption, we extended the PostmanAssertify tool to automatically convert the test oracles reported by SATORI into executable assertions. Evaluation results on 17 operations from 12 industrial APIs show that SATORI can automatically generate up to hundreds of valid test oracles per operation. SATORI achieved an F1-score of 74.3%, outperforming the state-of-the-art dynamic approach AGORA+ (69.3%)—which requires executing the API—when generating comparable oracle types. Moreover, our findings show that static and dynamic oracle inference methods are complementary: together, SATORI and AGORA+ found 90% of the oracles in our annotated ground-truth dataset. Notably, SATORI uncovered 18 bugs in popular APIs (Amadeus Hotel, Deutschebahn, FDIC, GitLab, Marvel, OMDb and Vimeo) leading to documentation updates by the API maintainers."

# Summary. An optional shortened abstract.
summary: "REST API test case generation tools are evolving rapidly, with growing capabilities for the automated generation of complex tests. However, despite their strengths in test data generation, these tools are constrained by the types of test oracles they support, often limited to crashes, regressions, and noncompliance with API specifications or design standards. This paper introduces SATORI (Static API Test ORacle Inference), a black-box approach for generating test oracles for REST APIs by analyzing their OpenAPI Specification. SATORI uses large language models to infer the expected behavior of an API by analyzing the properties of the response fields of its operations, such as their name and descriptions. To foster its adoption, we extended the PostmanAssertify tool to automatically convert the test oracles reported by SATORI into executable assertions. Evaluation results on 17 operations from 12 industrial APIs show that SATORI can automatically generate up to hundreds of valid test oracles per operation. SATORI achieved an F1-score of 74.3%, outperforming the state-of-the-art dynamic approach AGORA+ (69.3%)—which requires executing the API—when generating comparable oracle types. Moreover, our findings show that static and dynamic oracle inference methods are complementary: together, SATORI and AGORA+ found 90% of the oracles in our annotated ground-truth dataset. Notably, SATORI uncovered 18 bugs in popular APIs (Amadeus Hotel, Deutschebahn, FDIC, GitLab, Marvel, OMDb and Vimeo) leading to documentation updates by the API maintainers."

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'https://doi.org/10.1145/3597926.3598114'
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
- satoriASE

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: arteSrc
---
