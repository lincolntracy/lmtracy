+++
title = "Development of a Viral Vector Library to Target Retinal Cell Types"
subtitle = ""

date = 2019-07-24T00:00:00
lastmod = 2019-07-24T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

tags = ["writing"]
summary = "Research summary for **BrainPost**"

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["writing"]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
# [image]
#   # Caption (optional)
#   caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

  # Show image only in page previews?
  preview_only = false

# Set captions for image gallery.

# [[gallery_item]]
# album = "gallery"
# image = "01_lincolntracy.jpg"
# caption = "Lincoln Tracy"

# [[gallery_item]]
# album = "gallery"
# image = "02_anneburke.jpg"
# caption = "Anne Burke"

+++

**What's the science?**

Being able to **target genes that are specific to neuronal or glial cell types** is critical for the understanding and repairing of brain circuits. Most of the currently available technologies for cell-type targeting requires the use of [transgenic animals](https://www.whatisbiotechnology.org/index.php/science/summary/transgenic/transgenic-animals-have-genes-from-other-species-inserted), which have several limitations. For example, using a transgenic component **prevents such therapies being used in humans**. These limitations may be overcome using [Adeno-associated viruses](https://www.sciencedirect.com/topics/neuroscience/adeno-associated-virus) (AAVs) - viruses that are able to deliver genes to particular cell types. AAVs are **commonly used in both basic research and gene therapy as they are safe for use in a variety of species**—including non-human primates (NHPs) and humans—**and are simple, cheap, and easy to make**. This week in [Nature Neuroscience](https://www.nature.com/articles/s41593-019-0431-2), Jüttner and colleagues **created a library of 230 AAVs**—each containing a different synthetic promoter designed from one of four unique strategies—**to allow transgene expression in retinal cells in mice, NHPs, and humans**.

<br/>
**How did they do it?**

First, the authors created a library of **230 AAV [plasmids](https://www.nature.com/scitable/definition/plasmid-plasmids-28), each containing a different synthetic DNA sequence** ranging between 113 and 2501 base pairs in length. They used **four different strategies to construct the [5` sequences](http://www.informatics.jax.org/glossary/_5_prime)** (synthetic promoters). The four groups of promoters created by each strategy were named group ProA, ProB, ProC, and ProD. Two-hundred and twenty-six of the AAVs were also **designed to drive a channelrhodopsin variant fused to [green fluorescent protein](https://www.sciencedirect.com/topics/neuroscience/green-fluorescent-protein) (CatCh-GFP)** as an [optogenetic tool](https://www.sciencedirect.com/topics/neuroscience/optogenetics). The four remaining AAVs were designed to express only GFP. Second, they injected the collection of 230 AAVs **underneath the retina in the eyes of mice**. **Four mouse eyes were used for each AAV**. Transgene expression of the AAVs throughout the retina was evaluated three to four weeks later using [confocal microscopy](https://www.sciencedirect.com/topics/medicine-and-dentistry/confocal-microscopy). Third, they injected a subset of the AAVs into the eyes of the **NHP [Macaca fascicularis](http://pin.primate.wisc.edu/factsheets/entry/long-tailed_macaque/behav)**. Like the mice, four viruses with different synthetic promoters were injected into each distinct quadrant of the eye. Transgene-expressing cells were analyzed **three months post-injection**. Fourth, the same subset of AAVs injected into the NHPs were **injected into retinas taken from deceased individuals with no history of eye disease**. [Immunofluorescence analysis](https://www.sciencedirect.com/topics/neuroscience/immunofluorescence) was performed at seven weeks post-injection to identify if and which AAVs had reproducibly resulted in gene expression. Finally, they partitioned retinal cell types into one of eight different groups to **quantify the translatability of the AAV targeting across the three different species**.

<br/>
**What did they find?**

First, the authors found that **113 of the 230 synthetic promoters were active in the mouse retina**. **Thirty-two promoters resulted in successful targeting**, defined as (i) cell-type-specific labelling with 90% specificity or greater, (ii) cell-type-specific labelling with 50% specificity or greater where the only contamination was Müller glia, or (iii) cell class-specific labelling with a 70% or greater specificity. **The ProD promoters had the highest targeting success rate in the mouse retina**. While several promoters were successful in their targeting, less than 1% of the promoters replicated the expression specificity of their source genes. Several promoters drove CatCh-GFP expression in specific photoreceptors, such as **the ProA1 and ProA4 promoters driving CatCh-GFP expression in cone photoreceptors**. Second, they identified **94 AAVs that produced either reproducible or no gene expression in the NHP retina three months after injection**. Sixty-two AAVs were active, and 23 led to successful targeting. The ProA1 and ProA4 promoters were again found to drive gene expression in cone photoreceptors in the NHP retina. Third, they found that **84 of the 113 AAVs injected into human retinas reproducibly resulted in expression or no expression**, 52 of which were active. Nineteen of these AAVs led to successful targeting. Fewer promoters preferentially targeted specific cell types compared to what was observed in mice and NHP’s. Finally, they found that the **ability of an AAV to target a cell group in NHPs was a better predictor of targeting the same cell group in humans** versus the ability of an AAV to target a specific cell group in mice predicting targeting ability in humans.

![Figure 1](/img/Leigh_image.jpg)


<br/>
**What's the impact?**

These findings are the first report of a broad spectrum of AAVs targeting neuronal or glial cell types, especially in NHPs and humans. The results of this study suggest that **the absence of the expression of a specific cell type or class in mice can be used as a useful proxy for the absence of expression in humans (i.e. the AAV vector does not need to be tested in humans)**. The resources provided by the authors have different levels of potential for basic and translational research in mice, NHPs, and humans. **The authors have also created an [online database of three-dimensional confocal scans](https://data.fmi.ch/promoterDB/) for the AAVs that yielded reproducible labelling, which can be used by other researchers to search for cell types activated by active AAVs**. Overall, the resources and approaches described by the authors allow for economic and efficient cell-type targeting across a range of species for basic science and gene therapy. 

![author quote](/img/Roska_quote_Jul23.jpg)


<br/>
Jüttner et al. Targeting neuronal and glial cell types with synthetic promoter AAVs in mice, non-human primates and humans. Nature Neuroscience (2019). [Access the original scientific publication here](https://www.nature.com/articles/s41593-019-0431-2). 

---

*This article was first published via [BrainPost](https://www.brainpost.co/weekly-brainpost/2019/7/23/development-of-a-viral-vector-library-to-target-retinal-cell-types) and is reproduced with permission.*
