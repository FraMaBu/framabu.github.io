---
title: "Enhancing Priority Setting with LLMs and RAG"
date: 2024-06-04
excerpt: "LLM-powered desk reviews for evidence-based priority setting in World Bank health lending design."
tags: [case study]
header:
  overlay_image: "/assets/images/health_hero.png"
  overlay_filter: 0.5
  caption: "Presentation to the SteerCo"
  teaser: "/assets/images/health_hero.png"
classes: custom-page
---

This project was done in partnership with the [Bill and Melinda Gates Foundation](http://gatesfoundation.org/). As the technical lead on this project, I designed and implemented a mixed document analysis approach blending advanced LLM methods with human expertise. This initiative was aimed at analyzing and strengthening how countries set priorities for World Bank health investments, ensuring that decision makers have clear, evidence-based insights drawn from complex financial and project documents.

## The challenge

World Bank health projects involve a vast array of documents—from Project Appraisal Documents (PADs) and investment proposals (PIDs) to financing agreements—each reflecting the diverse inputs of multiple country stakeholders. The inherent variability in these sources, combined with the evolving nature of project priorities from initial concepts to final appraisals, created significant obstacles for extracting consistent and actionable insights. The complexity of these processes demanded an innovative solution capable of processing large volumes of heterogeneous text while maintaining high accuracy and contextual relevance.

## The innovative solution

To overcome these challenges, I led the development of a document analysis system ("desk review") that combines the efficiency of a large language model (LLM) with the guardrails of human oversight. This approach standardizes the extraction of key information from complex documents, ensuring that the analysis remains both replicable and reliable. By automating the initial extraction process and then incorporating human verification, we were able to quickly and accurately uncover patterns and trends. This, in turn, strengthened evidence-based decision making in the design of World Bank health investments.

Here is a high-level overview of the approach: Our process begins with clearly defined focus topics, which guide and standardize the analysis of relevant documents. After preprocessing, the documents are ingested into a vector database to support semantic search. This enables retrieval augmented generation (RAG), where the LLM generates targeted summaries grounded in extracts and references from specific texts—be it from PIDs, PADs, or financing agreements. Human analysts then review and refine the outputs before final postprocessing and storage for further comparative analysis.

This structured approach not only standardizes data extraction but also ensures that references to the most relevant textual evidence are maintained throughout the process.

## Impact & benefits

The implementation of this mixed approach yielded tangible benefits, including:

- **Reduction in processing time:** Manual and tedious desk review was slashed from days to minutes, significantly accelerating hypothesis formulation and insight generation.
- **Consistency in data extraction:** The combination of automation and human oversight ensured highly reliable extraction across diverse document types with an accuracy of over 95%—virtually eliminating inconsistencies in the generated summaries.
- **Direct impact on strategic funding decisions:** The insights derived from our hybrid analysis directly informed adjustments to strategic funding in 12 low- and middle-income countries, ensuring that investment priorities are closely aligned with critical health needs.

By blending advanced LLM capabilities with rigorous human review, this project has informed new standards for evidence-based priority setting in World Bank health investments. The approach not only streamlines the review process but also empowers decision makers with clear, actionable insights—paving the way for more informed, efficient, and impactful project design. If you’re interested in learning more about this methodology fostering co-creation between AI and humans or discussing potential collaborations, please do not hesitate to [get in touch](/contact/).