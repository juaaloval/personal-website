---
title: "Automated generation of test oracles for RESTful APIs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Juan C. Alonso

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2022-11-09T00:00:00Z"
doi: "10.1145/3540250.3559080"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-11-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 30th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering* November, 2022, Singapore
publication_short: In *ESEC/FSE 2022 Student Research Competition* **(First prize winner)**

abstract: 'Test case generation tools for RESTful APIs have proliferated in recent years. However, despite their promising results, they all share the same limitation: they can only detect crashes (i.e., server errors) and disconformities with the API specification. In this paper, we present a technique for the automated generation of test oracles for RESTful APIs through the detection of invariants. In practice, our approach aims to learn the expected properties of the output by analysing previous API requests and their corresponding responses. For this, we extended the popular tool Daikon for dynamic detection of likely invariants. A preliminary evaluation conducted on a set of 8 operations from 6 industrial APIs reveals a total precision of 66.5% (reaching 100% in 2 operations). Moreover, our approach revealed 6 reproducible bugs in APIs with millions of users: Amadeus, GitHub and OMDb.'

# Summary. An optional shortened abstract.
summary: 'Test case generation tools for RESTful APIs have proliferated in recent years. However, despite their promising results, they all share the same limitation: they can only detect crashes (i.e., server errors) and disconformities with the API specification. In this paper, we present a technique for the automated generation of test oracles for RESTful APIs through the detection of invariants. In practice, our approach aims to learn the expected properties of the output by analysing previous API requests and their corresponding responses. For this, we extended the popular tool Daikon for dynamic detection of likely invariants. A preliminary evaluation conducted on a set of 8 operations from 6 industrial APIs reveals a total precision of 66.5% (reaching 100% in 2 operations). Moreover, our approach revealed 6 reproducible bugs in APIs with millions of users: Amadeus, GitHub and OMDb.'

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
- testOraclesSRC

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: arteSrc
---
