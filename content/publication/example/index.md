---
title: "speaker identification using cepstral coefficients codebooks at Mel frequencies and hidden Markov models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Dennis Auccapuma

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2016"
doi: "20.500.12918/2466"

# Schedule page publish date (NOT publication's date).
publishDate: "2016"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Wowchemy Conference*
publication_short: In *ICW*

abstract: 

  Speech is a complicated type of product signal the outcome of a series of transforma-tions occurring at diﬀerent levels; semantic, linguistic and acoustics. Then these transfor-mations lead to diﬀerences in the characteristics of a speaker widely studied by Biometrics.The speaker identiﬁcation (indentify who is the person which claimed the voice) in sum-mary, is a detailed analysis of the unique characteristics speech of the speaker. In thiscontext, this project focuses on the speaker identiﬁcation with single words using HiddenMarkov Model (HMM) and the parameters in the feature extractions and the size of thecodebooks is restimated to increase eﬀectiveness of identiﬁcation of a speaker,those pro-cesses are described in three steps; cature extraction, data modeling and identiﬁcation,detailing in each step the theory and implementation in Java. Starting voice processing forthe most important features of an speaker Mel Frequency Cepstral Coﬃcients (MFCC) isused, because this tecnique give the best results in the Cepstral analysis by recent researchin this ﬁeld; Vector quantization (VQ) is made to clustering data by the classiﬁcation algo-rithm K-means, which substantially improves the processing time. For the modeling datathe HMM is assuming the statistical model as a Markov process,the HMMs are trained togenerate the sequence of observations (symbols observation), then the Viterbi algorithmﬁnd the sequence of states which has the most likelihood probability. In addition the pa-rameter modules of pre-processing,feature extraction and vector quantization with vectorcodebooks are restimated to suggest the size more suitable to the codebook and increasethe identiﬁcation. Finally, our experimental results show in details the parameters withwe get best results with a 90% of accuracy for a small closed group of 5 people in realconditions (background noise) with a decreasing trend as group the number of populationincreases and greater eﬀectiveness in ideal conditions (closed without background noiseenvironment).

# Summary. An optional shortened abstract.
summary: SR,MFCC,HMM-VQ,k-means.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.academia.edu/38921767/IDENTIFICACI%C3%93N_DE_LOCUTOR_USANDO_CODEBOOKS_DE_COEFICIENTES_CEPSTRALES_EN_LAS_FRECUENCIAS_DE_MEL_Y_MODELOS_OCULTOS_DE_MARKOV_a_dependent_speaker_identification_using_VQ_and_HMM_'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
