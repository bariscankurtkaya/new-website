---
title: "Deep Learning Based Driver Assistance System"
authors:
  - admin
  - Arda Tezcan
  - Murat Taskiran

date: "2023-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Electrica Journal"
publication_short: ""

abstract: Cars have become an essential mode of transportation for people all around the world, but unfortunately, traffic accidents remain a persistent problem. This paper proposes a solution to this issue using "deep learning" models and "image processing" algorithms, without the need for any additional sensors. The proposed system is designed to categorize images with 99.92% accuracy into two classes, "Night" and "Day", using a specially designed filter. Based on the results, the system employs a deep learning model that achieves 87.66% accuracy for vehicle detection, 80.47% accuracy for pedestrian detection, and 88.80% accuracy for lane detection. The system provides feedback to the driver based on these results, thereby enhancing driver awareness and improving overall road safety.

# Summary. An optional shortened abstract.
summary: The Deep Learning Based Driver Assistance System was developed with the aim of reducing car accidents caused by driver error, using a deep learning-based object detection algorithm. During our investigation, we discovered that the YoloV3 and YoloV4 algorithms, along with their pretrained Darknet53 and CSP-Darknet53 models, were susceptible to low-light images when detecting objects. To address this issue, we fine-tuned the pre-trained networks using the "Oxford RobotCar Dataset" to minimize the network's bias towards daytime images in the object detection task. With this issue resolved, we created a pipeline that detects road lanes, calculates the probability of collisions, and provides feedback to the driver.

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "https://electricajournal.org/en/deep-learning-based-driver-assistance-system-161988"
url_code: "https://github.com/bariscankurtkaya/DL-DAS"
url_dataset: "https://robotcar-dataset.robots.ox.ac.uk/"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ""
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
