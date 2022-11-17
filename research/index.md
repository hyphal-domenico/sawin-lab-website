---
title: Research
nav:
  order: 1
  tooltip: About our research
---

# <i class="fas fa-microscope"></i>Our Research

{% capture text %}
We are interested in two general areas related to cellular organisation. Our current main interest is the regulation of cell polarity, under both normal and stress conditions; we also continue to study the molecular mechanisms underlying nucleation of the microtubule cytoskeleton. In both areas we use fission yeast _Schizosaccharomyces pombe_ as a model single-celled eukaryote. We combine classical and molecular genetic analysis with live-cell fluorescence microscopy, biochemistry, proteomics/phosphoproteomics, and structural biology methods.


{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research1.png"
  link="research"
  text=text
%}

{% capture text %}
Cell polarity in fission yeast is regulated by multiple internal cues that cooperate and compete with each other. The Rho-family GTPase Cdc42 and its associated regulators and effectors control the actin cytoskeleton and exocytosis. Microtubules provide an additional level of control, through the microtubule-associated protein Tea1 and its interactors. We have shown how the Tea1/microtubule system coordinates polarity regulation by a conventional Cdc42 guanine-nucleotide exchange factor, Scd1, with regulation by an unconventional exchange factor, Gef1. Our work has also led to the discovery of new cell-polarity regulators outside of the Cdc42- and Tea1/microtubule-based systems, and a new understanding of how the conserved NDR kinase Orb6 regulates cell polarity. A major current focus is on how the stress-activated kinase Sty1 (homolog of human p38 MAP kinase) regulates cell polarity; we are addressing this through large-scale phosphoproteomics and genetics/biochemistry/microscopy approaches.


{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research2.png"
  flip=true
  text=text
%}

{% capture text %}
Microtubule nucleation in all eukaryotic cells depends on the γ-tubulin complex (γ-TuC), a large multi-protein complex enriched at microtubule organising centres such as the centrosome. Many aspects of γ-TuC regulation remain a mystery. We discovered the fission yeast proteins Mto1 and Mto2, which form an oligomeric complex (the Mto1/2 complex). Mutations in the human homolog of Mto1 lead to the brain disease microcephaly. We have shown how Mto1/2 targets the γ-TuC to different sites in the cell and we have also shown that also Mto1/2 activates the γ-TuC in vivo. We have reconstituted microtubule nucleation in vitro using purified γ-TuC and Mto1/2 proteins, and we have characterised Mto1/2 through cross-linking mass spectrometry and X-ray crystallography. Our current work is focused on understanding how Mto1/2 complex activates the γ-TuC.

As part of our work, we develop new tools in genetics, microscopy, and proteomics as needed. These have included a robust platform for differential proteomics in fission yeast, engineering of signalling pathways in vivo, and new methods for interrogating protein-protein interactions in complex “solid-phase” organelles.

{%
  include link.html
  link="Publications"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research3.png"
  link="research"
  text=text
%}

{% include section.html %}

## <i class="fas fa-coins"></i>Funding

Current funders of our work.
{:.center}

{% capture col1content %}

{% include figure.html image="images/darwin_trust.png" width= "240px" link="https://darwintrust.bio.ed.ac.uk" %}




{:.center}

{% endcapture %}

{% capture col2content %}

{% include figure.html image="images/wellcome.svg" width= "135px" link="https://wellcome.org/" %}


{:.center}

{% endcapture %}

{% capture col3content %}

{% include figure.html image="images/eastbio.jpeg" width= "60000px" link="http://www.eastscotbiodtp.ac.uk" %}

{:.center}

{% endcapture %}

{% include three-col.html col1=col1content col2=col2content col3=col3content%}
