# A Dataset of Laryngeal Endoscopic Images for Semantic Segmentation

Max-Heinrich Laves, Jens Bicker, Lüder A. Kahrs, Tobias Ortmaier

Automated segmentation of anatomical structures in medical image analysis is a prerequisite for autonomous diagnosis as well as various computer and robot aided interventions.
Recent methods based on deep convolutional neural networks (CNN) have outperformed former heuristic methods.
However, those methods were primarily evaluated on rigid, real-world environments.
Since there are no suitable datasets of soft tissue environments, we created
this dataset and made it available to the public.

## The dataset

<img src="https://raw.githubusercontent.com/imesluh/vocalfolds/master/dataset_description.png">

The dataset consists of 8 sequences from 2 patients (seq1-seq4 from patient 1
and seq5-seq8 from patient 2), containing 536 hand segmented in vivo colour
images of the larynx during two different resection interventions with a
resolution of 512x512 pixels.

The sequences have following characteristics:

* seq1: pre-op with clearly visible tumor on vocal fold, changes in translation,
  rotation, scale, no instruments visible, without intubation
* seq2: pre-op with clearly visible tumor, visible instruments, changes in
  translation and scale, with intubation
* seq3-4: post-op with removed tumor, damaged tissue, changes in translation and
  scale, with intubation
* seq5-7: pre-op with instruments manipulating and grasping the vocal folds,
  changes in translation and scale, with intubation
* seq8: post-op with blood on vocal folds, instruments and surgical dressing,
  with intubation

They are categorized in the 7 different classes *void*, *vocal folds*, *other tissue*, *glottal space*, *pathology*, *surgical tool* and *intubation* with indices `{0, 1, 2, 3, 4, 5, 6}, respectively, which is represented by the gray values of the label maps
Not all classes were present at both patients. We
would like to adress this in future work by enlarging the dataset.

## Publication

This work has been accepted for publication under the title "A Dataset of
Laryngeal Endoscopic Images with Comparative Study on Convolution Neural Network
Based Semantic Segmentation" in [International Journal of Computer Assisted
Radiology and Surgery](http://www.springer.com/medicine/radiology/journal/11548) ([arXiv:1807.06081](https://arxiv.org/abs/1807.06081)).

## Formal Consent

The endoscopic video images were acquired by Prof. Giorgio Peretti (Director of
Otorhinolaryngology at Ospedale Policlinico San Martino, University of Genova).
Patients gave their written consent for the procedure and the use of the data.
No further approval is necessary for such endoscopic recordings. The videos were
anonymized made available inside the μRALP consortium for further usage. All
procedures performed in studies involving human participants were in accordance
with the ethical standards of the institutional and/or national research
committee and with the 1964 Helsinki declaration and its later amendments or
comparable ethical standards.

## Contact

Max-Heinrich Laves, laves@imes.uni-hannover.de

Appelstr. 11A, 30167 Hannover, Germany
