
# CircularCheck: A Tool for Detecting Circular Reporting

## Institution

**University of Tartu**  
Faculty of Science and Technology  
Institute of Computer Science  

## Author

**Kasper Kaljuste**  
Software Engineering, MSc

## Abstract

This thesis addresses the problem of detecting circular reporting in Estonian online news media. Circular reporting occurs when information appears to come from multiple independent sources but originates from a single one, often creating an illusion of corroboration. This phenomenon contributes to misinformation and undermines media transparency. 

The project introduces **CircularCheck**, a system for identifying circular reporting patterns by analyzing reference chains and content similarity across three major Estonian news outlets: **ERR**, **Delfi**, and **Postimees**. The system builds reference hierarchies from scraped articles and uses a combination of link-based analysis and TF-IDF cosine similarity to detect potentially circular patterns.

A total of 55 circular reporting cases were identified (47 by link analysis, 4 by text similarity). The most robust signals were found in self-referencing loops. While circular reporting is not widespread, the findings show that it does occur and can be detected with relatively simple heuristics. The system does not aim to assess the truthfulness of information but rather the **independence** of sources by tracing reference propagation.

This work demonstrates that structured reference tracking can enhance source credibility analysis and offers a foundation for adapting similar methods in other media ecosystems.

---

## Results

The system flagged 51 potential cases of circular reporting in a dataset of over 250,000 articles across ERR, Postimees, and Delfi. Manual validation confirmed that most circular links involved self-references or repeated sourcing patterns. Precision was evaluated based on manually labeled results using the following formula:

\[
\text{precision} = \frac{\text{TP}}{\text{TP} + \text{FP}}
\]

The final system is intended as a semi-automated tool to help journalists, researchers, or media watchdogs track reference chains and assess source independence.

---

## Contact

For questions, please contact **Kasper Kaljuste** at [kasper.kaljuste@ut.ee].
