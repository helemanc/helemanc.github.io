---
layout: page
title: Investigating the Effectiveness of Explainability Methods in Parkinson's Detection from Speech
permalink: /parkinsons-speech-xai/
description: Eleonora Mancini*, Francesco Paissan*, Paolo Torroni, Mirco Ravanelli, Cem Subakan <br> *Both authors contributed equally to this research. For these authors, the order is alphabetical. 
nav: false
#nav_order: 8
related_publications: false
---
<!-- pages/parkinsons-speech-xai.md -->


## Description
Project Webpage (Submitted to [SPADE Workshop - ICASSP'25](https://spadeworkshop.github.io/workshop.html)). 

## Abstract 
Speech impairments in Parkinson's disease (PD) provide significant early indicators for diagnosis. While models for speech-based PD detection have shown strong performance, their interpretability remains underexplored. This study systematically evaluates several explainability methods to identify PD-specific speech features, aiming to support the development of accurate, interpretable models for clinical decision-making in PD diagnosis and monitoring. Our methodology involves (i) obtaining attributions and saliency maps using mainstream interpretability techniques, (ii) quantitatively evaluating the faithfulness of these maps and their combinations obtained via union and intersection through a range of established metrics, and (iii) assessing the information conveyed by the saliency maps for PD detection from an auxiliary classifier. Our results reveal that, while explanations are aligned with the classifier, they often fail to provide valuable information for domain experts.

### Contribution in a nutshell: 
- Experimental results demonstrate that explanations align with the classifier's decisions.
- Explanations often fail to offer truly informative insights for domain experts.
- Existing methods may lack the interpretability required for practical applications.
- Results highlight the need for more effective explainability approaches.

### Explanations 
We provide explanations for samples generated from various speech tasks, including diadochokinetic (DDK) exercises, monologues, and reading exercises.


Click on any image to view a larger version in a new tab! 

`Diadochokinetic (DDK) Exercises Samples`

<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_1_1/original.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_1_1/original.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_1_1/saliency.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_1_1/saliency.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_1_1/gbp.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_1_1/gbp.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_1_1/ggc.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_1_1/ggc.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_1_1/shap.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_1_1/shap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    
</div>

<div class="caption">
    Explanations generated for a PD sample correctly classified by HuBERT.
</div>

<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_0_0/original.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_0_0/original.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_0_0/saliency.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_0_0/saliency.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_0_0/gbp.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_0_0/gbp.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_0_0/ggc.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_0_0/ggc.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_0_0/shap.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_0_0/shap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    
</div>

<div class="caption">
    Explanations generated for a HC sample correctly classified by HuBERT.
</div>

<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_1_0/original.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_1_0/original.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_1_0/saliency.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_1_0/saliency.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_1_0/gbp.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_1_0/gbp.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_1_0/ggc.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_1_0/ggc.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_1_0/shap.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_1_0/shap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    
</div>

<div class="caption">
    Explanations generated for a PD sample misclassified by HuBERT.
</div>

<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_0_1/original.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_0_1/original.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_0_1/saliency.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_0_1/saliency.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_0_1/gbp.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_0_1/gbp.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_0_1/ggc.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_0_1/ggc.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/ddk_0_1/shap.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/ddk_0_1/shap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    
</div>

<div class="caption">
    Explanations generated for a HC sample misclassified by HuBERT.
</div>

`Monologue Samples`


<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_1_1/original.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_1_1/original.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_1_1/saliency.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_1_1/saliency.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_1_1/gbp.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_1_1/gbp.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_1_1/ggc.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_1_1/ggc.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_1_1/shap.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_1_1/shap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    
</div>

<div class="caption">
    Explanations generated for a PD sample correctly classified by HuBERT.
</div>

<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_0_0/original.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_0_0/original.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_0_0/saliency.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_0_0/saliency.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_0_0/gbp.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_0_0/gbp.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_0_0/ggc.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_0_0/ggc.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_0_0/shap.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_0_0/shap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    
</div>

<div class="caption">
    Explanations generated for a HC sample correctly classified by HuBERT.
</div>

<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_1_0/original.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_1_0/original.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_1_0/saliency.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_1_0/saliency.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_1_0/gbp.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_1_0/gbp.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_1_0/ggc.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_1_0/ggc.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_1_0/shap.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_1_0/shap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    
</div>

<div class="caption">
    Explanations generated for a PD sample misclassified by HuBERT.
</div>

<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_0_1/original.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_0_1/original.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_0_1/saliency.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_0_1/saliency.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_0_1/gbp.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_0_1/gbp.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_0_1/ggc.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_0_1/ggc.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/monologue_0_1/shap.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/monologue_0_1/shap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    
</div>

<div class="caption">
    Explanations generated for a HC sample misclassified by HuBERT.
</div>


`Read Text`


<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_1_1/original.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_1_1/original.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_1_1/saliency.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_1_1/saliency.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_1_1/gbp.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_1_1/gbp.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_1_1/ggc.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_1_1/ggc.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_1_1/shap.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_1_1/shap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    
</div>

<div class="caption">
    Explanations generated for a PD sample correctly classified by HuBERT.
</div>

<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_0_0/original.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_0_0/original.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_0_0/saliency.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_0_0/saliency.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_0_0/gbp.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_0_0/gbp.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_0_0/ggc.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_0_0/ggc.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_0_0/shap.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_0_0/shap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    
</div>

<div class="caption">
    Explanations generated for a HC sample correctly classified by HuBERT.
</div>

<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_1_0/original.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_1_0/original.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_1_0/saliency.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_1_0/saliency.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_1_0/gbp.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_1_0/gbp.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_1_0/ggc.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_1_0/ggc.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_1_0/shap.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_1_0/shap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    
</div>

<div class="caption">
    Explanations generated for a PD sample misclassified by HuBERT.
</div>

<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_0_1/original.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_0_1/original.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_0_1/saliency.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_0_1/saliency.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_0_1/gbp.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_0_1/gbp.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_0_1/ggc.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_0_1/ggc.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <a href="{{ '/assets/img/parkinsons-speech-xai/read_text_0_1/shap.jpg' | relative_url }}" target="_blank">
            {% include figure.liquid loading="eager" path="assets/img/parkinsons-speech-xai/read_text_0_1/shap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </a>
    </div>
    
</div>

<div class="caption">
    Explanations generated for a HC sample misclassified by HuBERT.
</div>


