
# CircularCheck: A Tool for Detecting Circular Reporting

## Institution

**University of Tartu**  
Faculty of Science and Technology  
Institute of Computer Science  

## Author

**Kasper Kaljuste**  
Software Engineering, BSc

## Abstract

In the modern information landscape, the speed with which news is spread has reached unprecedented levels. This poses significant challenges in ensuring the accuracy and independence of information. Circular reporting is a situation where a piece of information appears to come from multiple independent sources, but in reality comes from only one source. Such practices can be intentional or accidental and contribute to the spread of false information by creating an illusion of corroboration. While circular reporting has been studied in intelligence and scientific literature, its detection in journalism, particularly in a small media ecosystem like Estonia, has received little attention. This thesis addresses the problem of detecting circular reporting in Estonian online news media. We present a system that detects circular reporting by building reference hierarchies and comparing article content across ERR, Delfi, and Postimees. Here we show that using a combination of link-based and text-based methods, it is possible to flag suspicious reference patterns for manual validation. The results show that 47 positive cases were detected by link analysis and 4 by text similarity. Self-referencing structures were the most reliable. These results reveal that although circular reporting is not widespread, it does occur and can be identified with relatively simple heuristics. The system does not attempt to verify the truthfulness of the information but instead focuses on tracing the propagation of references. This allows researchers and journalists to better assess the credibility and independence of sources. In a broader context, the results offer a framework that can be adapted to other media ecosystems and help improve media transparency.

---

## Results

The system flagged 51 potential cases of circular reporting in a dataset of 283,880 articles across ERR, Postimees, and Delfi. Manual validation confirmed that most circular links involved self-references or repeated sourcing patterns.

The final system is intended as a semi-automated tool to help journalists, researchers, or media watchdogs track reference chains and assess source independence.

---

## Contact

For questions, please contact **Kasper Kaljuste** at [kasper.kaljuste@ut.ee].
