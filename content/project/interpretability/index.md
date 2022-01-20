+++
# Project title.
title = "Summarize with Caution: Comparing Global Feature Attributions"

# Date this page was created.
date = 2020-11-10

# Project summary to display on homepage.
summary = "Local interpretability methods are widely used because of their ability to generate explanations tailored to individual data points even for complex black-box models. Although these methods are not designed to provide a global view of a model's behavior, many common interpretability tools offer makeshift global feature attributions obtained by taking the mean absolute value of each feature's (local) attribution scores across all training data points and then ranking the features by their average scores. We argue that averaging feature attribution scores may not always be appropriate and explore the ramifications of doing so. We present an artifact-based interview study intended to investigate whether ML developers would benefit from being able to compare and contrast different global feature attributions obtained by ranking features by other summary statistics of their attribution scores. We find that participants are able to use these global feature attributions to achieve different tasks and objectives. Viewing multiple global feature attributions increased participants' uncertainty in their understanding of the underlying model as they became more aware of the intricacies of the model's behavior. However, participants expressed concerns about the time it would take to compare and contrast different global feature attributions, echoing observations from prior work about the need to balance the benefits of thinking fast and thinking slow when designing interpretability tools. This project was started during an internship with with [Jenn Wortman Vaughan](http://www.jennwv.com/) and [Hanna Wallach](http://dirichlet.net/) in the [FATE group](https://www.microsoft.com/en-us/research/theme/fate/) at Microsoft Research."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "files/global_feature_attributions.pdf"
url_slides = ""
url_video = ""
url_code = "https://github.com/aokeson/Aggregated-Explainability-Ranking-Alternatives"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = ""
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"

  preview_only = true
+++
Local interpretability methods are widely used because of their ability to generate explanations tailored to individual data points even for complex black-box models. Although these methods are not designed to provide a global view of a model's behavior, many common interpretability tools offer makeshift global feature attributions obtained by taking the mean absolute value of each feature's (local) attribution scores across all training data points and then ranking the features by their average scores. We argue that averaging feature attribution scores may not always be appropriate and explore the ramifications of doing so. We present an artifact-based interview study intended to investigate whether ML developers would benefit from being able to compare and contrast different global feature attributions obtained by ranking features by other summary statistics of their attribution scores. We find that participants are able to use these global feature attributions to achieve different tasks and objectives. Viewing multiple global feature attributions increased participants' uncertainty in their understanding of the underlying model as they became more aware of the intricacies of the model's behavior. However, participants expressed concerns about the time it would take to compare and contrast different global feature attributions, echoing observations from prior work about the need to balance the benefits of thinking fast and thinking slow when designing interpretability tools. This project was started during an internship with with [Jenn Wortman Vaughan](http://www.jennwv.com/) and [Hanna Wallach](http://dirichlet.net/) in the [FATE group](https://www.microsoft.com/en-us/research/theme/fate/) at Microsoft Research.
![](featured.png)