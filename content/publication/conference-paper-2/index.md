---
title: 'Mobile robot localization in industrial environments using a ring of cameras and ArUco markers'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Ignacio Alvarez Garcia
  - Rafael C. Gonzalez


date: '2021-11-10'
doi: 10.1109/IECON48115.2021.9589442

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-10'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2021 – 47th Annual Conference of the IEEE Industrial Electronics Society*
publication_short: In *IECON*

abstract: Localization of mobile robots in industrial environments is key in an increasingly automated industry. Nowadays, the inspection and repair of heavy steel plates is performed by human workers. Repair work often requires long hours in uncomfortable postures that can cause problems for the worker. We propose a mobile robot placed on top of a steel plate that must move along the plate to inspect and repair it, without leaving the sheet. Robot localization on the plate is key to generate the inspection and repair trajectories.There are different methods of localization, the most widely used require the use of expensive laser sensors to create a map using information from the environment and localize from it. This paper proposes a less expensive localization system for a mobile robot based on the installation of ArUco markers in the environment and the use of a ring of 8 calibrated cameras mounted on the robot that allow a 360° vision. This ensures a correct localization regardless of the working area. It is necessary to map the markers with respect to a common coordinate system.We propose a method to create the map using the ring. We validate the proposal through experiments comparing the localization obtained with the proposed system and a localization using a state-of-the-art SLAM method employing laser sensors.

# Summary. An optional shortened abstract.
summary: This paper proposes a cost-effective localization system for mobile robots inspecting and repairing steel plates, using ArUco markers and a ring of 8 calibrated cameras to ensure accurate positioning, validated against a laser-based SLAM method.

tags:
  - Mobile Robot
  - Computer Vision
  - Robot Localization
  - ArUco Markers
  - Ring of Cameras
  - ROS


# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/9589442'
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
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.


---

