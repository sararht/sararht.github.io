---
title: Reinforcement Learning Approach to Optimizing Profilometric Sensor Trajectories for Surface Inspection / Working paper"
authors:
- admin
- Mario Roos-Hoefgeest
- Ignacio Alvarez
- Rafael C. González
date: "2025-04-03"
doi: "https://doi.org/10.3390/s25072271"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-04-03"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: High-precision surface defect detection in manufacturing is essential for ensuring quality control. Laser triangulation profilometric sensors are key to this process, providing detailed and accurate surface measurements over a line. To achieve a complete and precise surface scan, accurate relative motion between the sensor and the workpiece is required. It is crucial to control the sensor pose to maintain optimal distance and relative orientation to the surface. It is also important to ensure uniform profile distribution throughout the scanning process. This paper presents a novel Reinforcement Learning (RL) based approach to optimize robot inspection trajectories for profilometric sensors. Building upon the Boustrophedon scanning method, our technique dynamically adjusts the sensor position and tilt to maintain optimal orientation and distance from the surface, while also ensuring a consistent profile distance for uniform and high-quality scanning. Utilizing a simulated environment based on the CAD model of the part, we replicate real-world scanning conditions, including sensor noise and surface irregularities. This simulation-based approach enables offline trajectory planning based on CAD models. Key contributions include the modeling of the state space, action space, and reward function, specifically designed for inspection applications using profilometric sensors. We use Proximal Policy Optimization (PPO) algorithm to efficiently train the RL agent, demonstrating its capability to optimize inspection trajectories with profilometric sensors. To validate our approach, we conducted several experiments where a model trained on a specific training piece was tested on various parts in simulation. Also, we conducted a real-world experiment by executing the optimized trajectory, generated offline from a CAD model, to inspect a part using a UR3e robotic arm model. 

# Summary. An optional shortened abstract.
summary: This paper presents a Reinforcement Learning-based approach to optimize robot inspection trajectories for profilometric sensors, dynamically adjusting sensor pose for precise scanning, validated through simulations and real-world experiments with a UR3e robotic arm.

tags:
- Reinforcement Learning
- Robot arms
- Surface Inspection
- Laser triangulation

featured: true
url_pdf: https://www.mdpi.com/1424-8220/25/7/2271
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

---