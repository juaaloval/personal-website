---
title: "Test Oracle Generation for REST APIs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Juan C. Alonso
- Michael D. Ernst
- Sergio Segura
- Antonio Ruiz-Cortes

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2025-03-28T00:00:00Z"
doi: "10.1145/3726524"

# Schedule page publish date (NOT publication's date).
# publishDate: "2021-08-01T00:00:00Z" # TODO: Update

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Software Engineering and Methodoloy (TOSEM) 2025*
publication_short: In *ACM TOSEM 2025*

abstract: The number and complexity of test case generation tools for REST APIs have significantly increased in recent years. These tools excel in automating input generation but are limited by their test oracles, which can only detect crashes, regressions, and violations of API specifications or design best practices. This article introduces AGORA+, an approach for generating test oracles for REST APIs through the detection of invariants—output properties that should always hold. AGORA+ learns the expected behavior of an API by analyzing API requests and their corresponding responses. We enhanced the Daikon tool for dynamic detection of likely invariants, adding new invariant types and creating a front-end called Beet. Beet translates any OpenAPI specification and a set of API requests and responses into Daikon inputs. AGORA+ can detect 106 different types of invariants in REST APIs. We also developed PostmanAssertify, which converts the invariants identified by AGORA+ into executable JavaScript assertions. AGORA+ achieved a precision of 80% on 25 operations from 20 industrial APIs. It also identified 48% of errors systematically seeded in the outputs of the APIs under test. AGORA+ uncovered 32 bugs in popular APIs, including Amadeus, Deutschebahn, GitHub, Marvel, NYTimesBooks, and YouTube, leading to fixes and documentation updates.

# Summary. An optional shortened abstract.
summary: The number and complexity of test case generation tools for REST APIs have significantly increased in recent years. These tools excel in automating input generation but are limited by their test oracles, which can only detect crashes, regressions, and violations of API specifications or design best practices. This article introduces AGORA+, an approach for generating test oracles for REST APIs through the detection of invariants—output properties that should always hold. AGORA+ learns the expected behavior of an API by analyzing API requests and their corresponding responses. We enhanced the Daikon tool for dynamic detection of likely invariants, adding new invariant types and creating a front-end called Beet. Beet translates any OpenAPI specification and a set of API requests and responses into Daikon inputs. AGORA+ can detect 106 different types of invariants in REST APIs. We also developed PostmanAssertify, which converts the invariants identified by AGORA+ into executable JavaScript assertions. AGORA+ achieved a precision of 80% on 25 operations from 20 industrial APIs. It also identified 48% of errors systematically seeded in the outputs of the APIs under test. AGORA+ uncovered 32 bugs in popular APIs, including Amadeus, Deutschebahn, GitHub, Marvel, NYTimesBooks, and YouTube, leading to fixes and documentation updates.

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
- agoraPlusTOSEM

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: arteSrc
---
