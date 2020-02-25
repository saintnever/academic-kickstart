---
title: "Tap-to-Pair: Associating Wireless Devices with Synchronous Tapping"
authors:
- __Tengxiang Zhang__
- Xin Yi
- Ruolin Wang
- Yuntao Wang
- Chun Yu
- Yiqin Lu
- Yuanchun Shi

date: "2018-12-03T00:00:00Z"
doi: "https://doi.org/10.1145/3287079"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Proc. ACM Interact. Mob. Wearable Ubiquitous Technol*, Vol 2, Issue 4, Article 201, Dec 2018."
publication_short: <i>IMWUT</i>.<br/><font color="grey">Tap-to-Pair pairs two wireless devices spontaneously through tapping without modifications on either device</font>

abstract: Ad-hoc wireless device pairing enables impromptu interactions in smart spaces, such as resource sharing and remote control. The pairing experience is mainly determined by the device association process, during which users express their pairing intentions between the advertising device and the scanning device. Currently, most wireless devices are associated by selecting the advertiser’s name from a list displayed on the scanner’s screen, which becomes less efficient and often misplaced as the number of wireless devices increases. In this paper, we propose Tap-to-Pair, a spontaneous device association mechanism that initiates pairing from advertising devices without hardware or firmware modifications. Tapping an area near the advertising device’s antenna can change its signal strength. Users can then associate two devices by synchronizing taps on the advertising device with the blinking pattern displayed by the scanning device. By leveraging the wireless transceiver for sensing, Tap-to-Pair does not require additional resources from advertising devices and needs only a binary display (e.g. LED) on scanning devices. We conducted a user study to test users’ synchronous tapping ability and demonstrated that Tap-to-Pair can reliably detect users’ taps. We ran simulations to optimize parameters for the synchronization recognition algorithm and provide pattern design guidelines. We used a second user study to evaluate the on-chip performance of Tap-to-Pair. The results show that Tap-to-Pair can achieve an overall successful pairing rate of 93.7% with three scanning devices at different distances.

# Summary. An optional shortened abstract.
summary: Tap-to-Pair pairs two wireless devices spontaneously with no modifications on either device. 

tags:
- interaction
- wireless
- sensing
- IoT
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: '/publication/taptopair18/Tap-to-Pair.pdf'
url_code: 'https://github.com/starsjf/Tap2pair'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/z_FhHYxLbT4'

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