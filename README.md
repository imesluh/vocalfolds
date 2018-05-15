# A Dataset of Laryngeal Endoscopic Images for Semantic Segmentation

Max-Heinrich Laves, Jens Bicker, Lüder A. Kahrs, Tobias Ortmaier

Automated segmentation of anatomical structures in medical
image analysis is a key step in image and situs understanding for enabling
assisting or autonomous intervention robots. Recent methods based on deep
convolutional neural networks (CNN) have outperformed former heuristic methods.
However, those methods were mostly evaluated on rigid, real-world environments.
Since there are no suitable datasets of soft tissue environments, we created
this dataset and made it available to the public.

## The dataset

![0006.png](https://raw.githubusercontent.com/imesluh/vocalfolds/master/img/patient1/seq1/0006.png =128x)
![0160.png](https://raw.githubusercontent.com/imesluh/vocalfolds/master/img/patient1/seq1/0006.png =128x)
![0202.png](https://github.com/imesluh/vocalfolds/raw/master/img/patient1/seq3/0202.png =128x)
![0466.png](https://github.com/imesluh/vocalfolds/raw/master/img/patient2/seq7/0466.png =128x)
![1124.png](https://github.com/imesluh/vocalfolds/raw/master/img/patient2/seq8/1124.png =128x)

The dataset consists of 5 sequences from 2 patients (seq1-seq3 from patient 1
and seq7-seq8 from patient 2), containing 400 hand segmented in vivo colour
images of the larynx during two different resection interventions with a
resolution of 512x512 pixels. For training a CNN for semantic segmentation, we
split the dataset as follows:

training set: Seq1 and Seq8 (218 images)
validation set: Seq3 and first half of Seq7 (87 images)
test set: Seq2 and second half of Seq7 (95 images)

The sequences have following characteristics:

* seq1: pre-op with clearly visible tumor on vocal fold, changes in translation,
  rotation, scale, no instruments visible, without intubation
* seq2: pre-op with clearly visible tumor, visible instruments, changes in
  translation and scale, with intubation
* seq3: post-op with removed tumor, damaged tissue, changes in translation and
  scale, with intubation
* seq7: pre-op with instruments manipulating and grasping the vocal folds,
  changes in translation and scale, with intubation
* seq8: post-op with blood on vocal folds, instruments and surgical dressing,
  with intubation

Ideally, we would like to use one patient for training and the other patient for
validation/testing. However, not all classes were present at both patients. We
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
