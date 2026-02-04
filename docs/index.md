# BioDataManifest

Tools for generating Biomedical Data Manifest HTML pages from survey results or the web.

## Overview

Biomedical machine learning (ML) models raise critical concerns about embedded assumptions influencing clinical decision-making, necessitating robust documentation frameworks for datasets that are shared via external repositories. Fairness-aware algorithm effectiveness hinges on users' prior awareness of specific issues in the data -- information such as data collection methodology, provenance and quality. Current ML-focused documentation approaches impose impractical burdens on data generators and conflate data/model accountability. This is problematic for resource datasets not explicitly created for ML applications. This study addresses these gaps through a two-step process: First, we derived consensus documentation fields by mapping elements across four key templates. Second, we surveyed biomedical stakeholders across four roles (clinicians, bench scientists, data manager and computationalists) to assess field importance and relevance. This revealed important role-dependent prioritization differences, motivating the development of the Biomedical Data Manifest -- a modular template employing persona-specific field presentation reducing generator burden while ensuring end-users receive role-relevant information. The Biomedical Data Manifest improves transparency for datasets deposited in public or controlled-access repositories and bias mitigation across ML applications.

**Citation:** Bottomly, D., Suciu C.G., Cordier, B., Evans N., Poire, A., Zheng, C., The ARTNet Consortium, Tyner, J.W., Hutson, A., and McWeeney S.K. Biomedical Data Manifest: A lightweight data documentation mapping to increase transparency for AI/ML. Scientific Data, In Press.

## Examples

-   [Synthetic Data](https://github.com/biodev/BioDataManifest/blob/main/inst/extdata/template_example.html)
-   [TARGET-AML](https://github.com/biodev/BioDataManifest/blob/main/inst/extdata/TARGET-AML-biomedical_data_manifest.html)
-   [TCGA-LAML](https://github.com/biodev/BioDataManifest/blob/main/inst/extdata/TCGA-LAML-biomedical_data_manifest.html)
-   [BeatAML](https://github.com/biodev/BioDataManifest/blob/main/inst/extdata/BEATAML1.0-COHORT-biomedical_data_manifest.html)

See our Github [site](https://github.com/biodev/BioDataManifest) for more information.
