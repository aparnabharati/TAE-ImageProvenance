# TAE-ImageProvenance
Code for learning "Transformation Aware Embeddings for Image Provenance" analysis

## Abstract
A dramatic rise in the flow of manipulated image content on the Internet has led to a prompt response from the media forensics research community.
New mitigation efforts leverage cutting-edge data-driven strategies and increasingly incorporate usage of techniques from computer vision and machine learning to detect and profile the space of image manipulations. This paper addresses Image Provenance Analysis, which aims at discovering relationships among different manipulated image versions that share content. One important task in provenance analysis, like most visual understanding problems, is establishing a visual description and dissimilarity computation method that connects images that share full or partial content. But the existing handcrafted or learned descriptors --- generally appropriate for tasks such as object recognition --- may not sufficiently encode the subtle differences between near-duplicate image variants, which significantly characterize the provenance of any image. This paper introduces a novel data-driven learning-based approach that provides the context for ordering images that have been generated from a single image source through various transformations. Our approach learns transformation-aware embeddings using weak supervision via composited transformations and a rank-based Edit Sequence Loss. To establish the effectiveness of the proposed approach, comparisons are made with state-of-the-art handcrafted and deep-learning-based descriptors, as well as image-matching approaches. Further experimentation validates the proposed approach in the context of image provenance analysis and improves upon existing approaches.

## Contact
Aparna Bharati (aparna.bharati@lehigh.edu), Daniel Moreira (dhenriq1@nd.edu)

