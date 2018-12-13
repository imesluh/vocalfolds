# A Dataset of Laryngeal Endoscopic Images for Semantic Segmentation

Max-Heinrich Laves, Jens Bicker, Lüder A. Kahrs, Tobias Ortmaier

Automated segmentation of anatomical structures in medical image analysis is a prerequisite for autonomous diagnosis as well as various computer and robot aided interventions.
Recent methods based on deep convolutional neural networks (CNN) have outperformed former heuristic methods.
However, those methods were primarily evaluated on rigid, real-world environments.
Since there are no suitable datasets of soft tissue environments, we created
this dataset and made it available to the public.

## The dataset

<img src="https://raw.githubusercontent.com/imesluh/vocalfolds/master/img/patient1/seq1/0006.png" width="128"> <img src="https://raw.githubusercontent.com/imesluh/vocalfolds/master/img/patient1/seq2/0160.png" width="128"> <img src="https://raw.githubusercontent.com/imesluh/vocalfolds/master/img/patient1/seq3/0202.png" width="128"> <img src="https://raw.githubusercontent.com/imesluh/vocalfolds/master/img/patient2/seq7/0466.png" width="128"> <img src="https://raw.githubusercontent.com/imesluh/vocalfolds/master/img/patient2/seq8/1124.png" width="128">

The dataset consists of 5 sequences from 2 patients (seq1-seq4 from patient 1
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

Not all classes were present at both patients. We
would like to adress this in future work by enlarging the dataset.

## Publication

This work has been submitted for publication under the title "A Dataset of
Laryngeal Endoscopic Images with Comparative Study on Convolution Neural Network
Based Semantic Segmentation" in the [International Journal of Computer Assisted
Radiology and Surgery](http://www.springer.com/medicine/radiology/journal/11548)
. The review is still in progress.

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
