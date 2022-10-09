---
title: Home
---

# Welcome to the Sawin Lab!

We are interested in cell polarity and stress. We mainly use the yeast _Schizosaccharomyces pombe_ as a model organism and apply a variety of techinques including genetics, microscopy, and proteomics.

{%
  include link.html
  type="github"
  icon=""
  text="See the template on GitHub"
  link="greenelab/lab-website-template"
  style="button"
%}
{%
  include link.html
  type="docs"
  icon=""
  text="See the documentation"
  link="https://github.com/greenelab/lab-website-template/wiki"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/banner.jpg" %}

{% include section.html %}

# Our Research

{% capture text %}
Our laboratory is interested in two main areas related to cellular and cytoskeletal organisation: 1) the molecular mechanisms underlying microtubule nucleation; and 2) the regulation of cell polarity, in a systems context, under both normal and stress conditions. In both areas we use the fission yeast _Schizosaccharomyces pombe_ as a model eukaryotic organism. We combine classical and molecular genetic analysis with live-cell fluorescence microscopy, biochemistry, proteomics and computational modelling.


{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research1.png"
  link="research"
  text=text
%}

{% capture text %}
Microtubule nucleation in all eukaryotic cells depends on the γ-tubulin complex (γ-TuC), a multi-protein complex enriched at microtubule organizing centres such as the centrosome. The spatial and temporal regulation of the γ-TuC remains largely a mystery. We discovered the fission yeast proteins Mto1 and Mto2, which form an oligomeric complex (the Mto1/2 complex) that targets the γ-TuC to different sites in the cell and also activates γ-TuC during the cell cycle. Mutations in the human homolog of Mto1 lead to the brain disease microcephaly. Our current work involves understanding the mechanism of γ-TuC activation by the Mto1/2 complex, through genetic approaches in yeast, and through expression, purification and characterization of recombinant multi-protein complexes in insect cells, in vitro functional reconstitution, and structural biology analysis, including X-ray crystallography. We are also using new methods to investigate how the Mto1/2 complex is localized to different subcellular structures.


{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research2.png"
  link="resources"
  title="Our Resources"
  flip=true
  text=text
%}

{% capture text %}
An important component of our work involves developing new tools in genetics, microscopy, and proteomics. This includes a robust platform for differential proteomics in fission yeast, using Stable Isotope Labeling by Amino Acids in Culture (SILAC), which we are applying to global analysis of protein phosphorylation in cell polarity, and new methods for interrogating protein-protein interactions in complex “solid-phase” organelles.

{%
  include link.html
  link="research"
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
  title="Past projects"
  text=text
%}
