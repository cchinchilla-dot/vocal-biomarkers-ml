# Vocal Biomarkers for Respiratory Disease Detection using Machine Learning

This repository contains the implementation of the machine learning pipeline described in our IEEE Access paper focused on early and cost-effective diagnosis of COVID-19 through voice analysis.

The code is currently being published and will be available shortly.

## Paper Reference

This code is part of the research presented in:

> A. J. L. Rivero, C. C. Corbacho, T. R. Arias, M. Martín-Merino and P. Vaz, "Application of Machine Learning Techniques for the Characterization and Early Diagnosis of Respiratory Diseases Such as COVID-19," in IEEE Access, vol. 12, pp. 160516-160528, 2024, doi: 10.1109/ACCESS.2024.3487773

## Abstract

This paper presents a robust methodology for the early and cost-effective diagnosis of COVID-19 based on vocal features and machine learning techniques. The proposed methodology addresses all challenges inherent to the prediction of COVID-19, including those related to feature extraction and selection, the imbalance problem, and predictor training. In contrast to existing methodologies that rely solely on acoustic attributes of the voice, such as intensity or frequency, our approach represents a pioneering investigation that incorporates biomechanical aspects of vocal production. These include muscle tension, the coordination of articulatory movements, and respiration. The relationship between these characteristics and the presence of the virus is investigated rigorously using robust feature selection techniques. To this end, we have constructed an original dataset comprising patients with confirmed cases of COVID-19 infection and a control group, incorporating both acoustic and biomechanical features using Voice Clinical Software. The robustness and reproducibility of the experimental results have been enhanced through the rigorous comparison of several classifiers and feature selection algorithms, as well as the employment of resampling strategies. The application of random forests for feature selection has revealed that a limited set of biomechanical markers are significantly associated with the presence of COVID-19 infection. Moreover, a random forest classifier based on a subset of biomechanical and acoustic features demonstrates high efficacy in predicting cases of COVID-19 infection, achieving a sensitivity of S = (0.9212 ± 0.0775) while maintaining a specificity of Sp = ($0.9150 ± 0.0649). Considering these findings, the proposed methodology can be regarded as a non-invasive and cost-effective alternative for the diagnosis of COVID-19 infection. Furthermore, it can be extended to the diagnosis of other respiratory diseases, provided that the vocal cords are affected.

## Experimental Setup

The development and testing of this project were conducted in the following environment:

* Hardware: Apple MacBook Pro with M1 chip
* Operating System: macOS 14
* Environment: Conda (Python virtual environment)
* Python Version: 3.10.14
* Dependencies: Refer to requirements.txt for detailed library versions and dependencies.

## Additional Experimental Code

This repository includes supplementary experimental code and analyses developed during the research process but not included in the final published article or its supplementary materials, as they were considered exploratory or not central to the main findings.

These additional experiments reflect intermediate iterations, alternative approaches, and exploratory analyses conducted during model development. As a result, some scripts may be experimental in nature and could contain minor inconsistencies, incomplete configurations, or implementation details that were not part of the final validated pipeline.

Minor discrepancies between the published article and this codebase may therefore exist due to the natural evolution of the code during the research process, including experimentation, refactoring, and optimization. These discrepancies do not affect the core methodology or the main conclusions reported in the paper, which should be considered the authoritative reference.

## Data Availability and Reproducibility

Due to data privacy and ethical constraints, the dataset used in this research cannot be made publicly available. The data may be provided by the authors upon reasonable request.

To ensure methodological transparency and reproducibility, all preprocessing, feature selection, and modeling code used in the experiments is fully provided in this repository. Full reproduction of the results requires access to the original dataset.

## Authors

* Alfonso José López Rivero - Computer Science Faculty, Universidad Pontificia de Salamanca, Salamanca, Spain
* Carlos Chinchilla Corbacho - Computer Science Faculty, Universidad Pontificia de Salamanca, Salamanca, Spain
* Tatiana Romero Arias - Facultad de Ciencias de la Salud, Dpto. de Psicología, Universidad Europea de Canarias
* Manuel Martín-Merino - Computer Science Faculty, Universidad Pontificia de Salamanca, Salamanca, Spain
* Paulo Vaz - CISeD - Research Centre in Digital Services, Polytechnic of Viseu, Portugal Polytechnic Institute of Viseu, Viseu, Portugal

## Funding

This work is funded by National Funds through the FCT - Foundation for Science and Technology, I.P., within the scope of the project Ref. UIDB/05583/2020. We thank the Research Centre in Digital Services (CISeD) and the Instituto Politécnico de Viseu for their support.

## Citation

If you use this code in your research, please cite our paper:

```bibtex
@ARTICLE{10737357,
  author={Rivero, Alfonso José López and Corbacho, Carlos Chinchilla and Arias, Tatiana Romero and Martín-Merino, Manuel and Vaz, Paulo},
  journal={IEEE Access}, 
  title={Application of Machine Learning Techniques for the Characterization and Early Diagnosis of Respiratory Diseases Such as COVID-19}, 
  year={2024},
  volume={12},
  number={},
  pages={160516-160528},
  doi={10.1109/ACCESS.2024.3487773}}
```

## Acknowledgments

Special thanks to all participants who contributed data to this research and to the institutions that supported this work.

## License

This code is released under the MIT License.
