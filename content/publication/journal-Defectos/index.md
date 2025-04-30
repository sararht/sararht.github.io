---
title: "" #"Realistic Three-Dimensional Defect Simulation for Deep Learning-Based Industrial Inspection Systems / Working paper"
authors:
#- admin
#- Mario Roos-Hoefgeest
#- Daniel García
#- Ignacio Álvarez
#- Rafael C González

date: "2025-02-13"
#doi: "https://doi.org/10.3390/s23177624"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-02-13"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "Preprint"
publication_short: ""

#abstract: Quality requirements for manufactured products have increased dramatically in recent years. A challenging example is the detection of small surface deformations that may fall below manufacturing #tolerances. It requires analysis of high-precision, high-resolution three-dimensional information obtained with contactless methods, such as Laser profilometric sensors. Deep learning techniques may be #useful to locate such defects within the captured data. These new technologies demand large, annotated and balanced datasets to train the algorithms. Unfortunately, acquiring and labeling real defect #datasets in an industrial environment is challenging because of the random and infrequent nature of defects, and labor costs associated with manual detection and classification.We present a method to create #synthetic, labeled datasets that can be tailored to the inspection of new parts or manufacturing processes. Defects are modeled by an elevation defining their size and shape. The triangular mesh describing #the object is modified using Free-Form Deformation techniques, adapting the defect to the object’s local geometry. Random noise is added to ensure variety in the dataset. Moreover, we propose mathematical #models to characterize three common types of superficial defects. To validate our proposal, synthetic depth images are obtained by simulating the sensor acquisition process. Real and synthetic depth maps #are compared. Two deep-learning networks, trained with a synthetic and with a real dataset, are compared. Results achieved with a fresh set of real samples showed that synthetic data can replace the scarce #real data during the training phase. The method makes easier the development of inspection applications for new products.

# Summary. An optional shortened abstract.
#summary: This work presents a method to generate synthetic, labeled 3D surface defect datasets, enabling deep learning-based industrial inspection without relying on scarce and costly real data.

tags:
#- Surface defect simulation
#- Three-dimensional inspection
#- Laser Profilometric Sensor
#- Synthetic Defect Data Set Generation
#- You only look once network
#- Smart Quality Inspection in Industry
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5136909
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Graphical Abstract'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

