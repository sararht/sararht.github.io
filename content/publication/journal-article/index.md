---
title: "Simulation of Laser Profilometer Measurements in the Presence of Speckle Using Perlin Noise"
authors:
- admin
- Mario Roos-Hoefgeest
- Ignacio Álvarez
- Rafael C González

date: "2023-09-02"
#doi: "https://doi.org/10.3390/s23177624"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-02"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "MDPI Sensors"
publication_short: ""

abstract: In the manufacturing industry, inspection systems play a crucial role in ensuring product quality. High-resolution profilometric sensors have become increasingly popular for inspection due to their ability to provide detailed surface information. However, the development and testing of inspection systems can be costly and time-consuming. This paper presents the development of a simulation of an inspection system using a high-resolution profilometric sensor. A geometrical and noise model is proposed to simulate the readings of any actual profilometric sensor. The model replicates the sensor’s movement on the CAD model of the inspected part. The model incorporates the physical properties of the sensor and combines noise sources from sensor uncertainty and speckle noise induced by the roughness of the material. Our contribution lies in noise modeling. This work proposes a combination of Perlin noise to simulate the speckle noise and Gaussian noise for the uncertainty-related noise. Perlin noise is generated based on the surface roughness parameters of the inspected part. The accuracy of the simulation system is evaluated by comparing the simulated scans with real scans. The results highlight the ability to simulate real scans of different parts, using commercial sensor specifications and the CAD model of the inspected part.

# Summary. An optional shortened abstract.
summary: This paper presents a simulation model for high-resolution profilometric sensor inspection, incorporating geometrical and noise modeling (Perlin and Gaussian noise) to replicate real sensor readings and validate accuracy against real scans.

tags:
- Laser triangulation profilometry
- Perlin noise; speckle
- Surface roughness
- Simulation
- Computer vision
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.mdpi.com/1424-8220/23/17/7624
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

