---
title: "Facilitating Temporal Synchronous Target Selection through User Behavior Modeling"
authors:
- __Tengxiang Zhang__
- Xin Yi
- Ruolin Wang
- Jiayuan Gao
- Yuntao Wang
- Chun Yu
- Simin Li
- Yuanchun Shi

date: "2019-12-01T00:00:00Z"
doi: "https://doi.org/10.1145/3369839"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Proc. ACM Interact. Mob. Wearable Ubiquitous Technol*, Vol 3, Issue 4, Article 159, Dec 2019."
publication_short: <i>IMWUT</i>.<br/><font color="grey">This paper improves the target selection performance by optimizing blinking pattern sets with Bayesian-based human modeling</font>

abstract: Temporal synchronous target selection is an association-free selection technique:users select a target by generating signals (e.g., finger taps and hand claps) in sync with its unique temporal pattern. However, classical pattern set design and input recognition algorithm of such techniques did not leverage users’ behavioral information, which limits their robustness to imprecise inputs. In this paper, we improve these two key components by modeling users’ interaction behavior. In the first user study, we asked users to tap a finger in sync with blinking patterns with various period and delay, and modeled their finger tapping ability using Gaussian distribution. Based on the results, we generated pattern sets for up to 22 targets that minimized the possibility of confusion due to imprecise inputs. In the second user study, we validated that the optimized pattern sets could reduce error rate from 23% to 7% for the classical Correlation recognizer. We also tested a novel Bayesian, which achieved higher selection accuracy than the Correlation recognizer when the input sequence is short. The informal evaluation results show that the selection technique can be effectively scaled to different modalities and sensing techniques.

# Summary. An optional shortened abstract.
summary: <font color="#953100"><b>IMWUT 2019</b></font></br> This paper improves the target selection performance by optimizing blinking pattern sets with Bayesian-based human modeling. 

tags:
- interaction
- IoT
- Bayesian
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: '/publication/flysync19/flysync.pdf'
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
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['links']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
<!-- 
{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}} -->

<!-- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->