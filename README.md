# Vision–Language Models for Sustainability Claim Verification

## Overview
Sustainability benchmarking in the energy sector is largely based on self-reported
textual disclosures, which often lack objective validation. This pilot study explores
the feasibility of using Vision–Language Models (VLMs) to analyze alignment between
satellite imagery and corporate sustainability claims.

The project serves as a proof-of-concept for multimodal sustainability assessment
and forms the foundation for proposed doctoral research in AI-driven sustainability
analytics.

---

## Research Objective
To evaluate whether pretrained Vision–Language Models can identify alignment or
mismatch between:
- Visual environmental indicators from satellite imagery
- Textual sustainability claims from publicly available reports

---

## Methodology

### Visual Data
- Publicly available satellite images of industrial facilities
- Focus on visible indicators such as gas flaring and industrial activity

### Text Data
- Short sustainability claim excerpts related to environmental impact and emissions

### Models Used
- CLIP (Contrastive Language–Image Pretraining) for image–text similarity analysis
- BLIP-2 for generative reasoning and qualitative explanation

---

## Experimental Setup
1. Satellite images are encoded using CLIP’s image encoder
2. Sustainability claims are encoded using CLIP’s text encoder
3. Image–text similarity scores are computed via cosine similarity
4. BLIP-2 is used to generate cautious, natural-language explanations based on visual evidence

---

## Preliminary Findings
Initial results indicate that Vision–Language Models can distinguish between
general sustainability commitments and visual indicators of ongoing industrial
activity. This suggests the potential of multimodal AI methods to complement
traditional text-based sustainability assessments.

---

## Relevance and Future Work
This pilot demonstrates the feasibility of:
- Multimodal sustainability benchmarking
- AI-assisted verification of sustainability disclosures
- Scalable integration of satellite imagery into ESG analytics

Future work will involve expanding datasets, refining evaluation metrics, and
aligning assessments with SDGs and national sustainability priorities.

---

## Project Structure
vlm-sustainability-pilot/
├── data/
├── notebooks/
├── analysis/
├── README.md
└── requirements.txt


---

## References
- Radford et al., Learning Transferable Visual Models From Natural Language Supervision
- OpenAI CLIP: https://github.com/openai/CLIP
- BLIP-2: https://github.com/salesforce/LAVIS

---

## Author
Shifa Ussudoor  
Master’s in Data Science  
Research Interest: Vision–Language Models, Multimodal AI, Sustainability Analytics
