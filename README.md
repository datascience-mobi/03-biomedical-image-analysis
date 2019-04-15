Biomedical Image analysis
=======================

#### *Project overview and guidelines*

-   [Introduction](#introduction)
-   [Objective](#objective)
-   [Description of datasets](#description-of-datasets)
-   [Literature](#literature)
-   [How to structure your project](#how-to-structure-your-project)
-   [Project proposal](#project-proposal)

Supervisor:

-   PD Dr. Karl Rohr
    ([k.rohr@dkfz-heidelberg.de](mailto:k.rohr@dkfz-heidelberg.de))
-   Christian Ritter
    ([christian.ritter@bioquant.uni-heidelberg.de](mailto:christian.ritter@bioquant.uni-heidelberg.de))
-   Leonid Kostrykin
    ([leonid.kostrykin@bioquant.uni-heidelberg.de](mailto:leonid.kostrykin@bioquant.uni-heidelberg.de))
-   Roman Spilger
    ([roman.spilger@bioquant.uni-heidelberg.de](mailto:roman.spilger@bioquant.uni-heidelberg.de))
-   Christian Kromm
    ([christian.kromm@bioquant.uni-heidelberg.de](mailto:christian.kromm@bioquant.uni-heidelberg.de))


Tutor:

- Nicolas Peschke ([peschke@stud.uni-heidelberg.de](mailto:peschke@stud.uni-heidelberg.de))

Introduction
------------

Image analysis methods are important to extract relevant information
from biomedical image data. Typically a large amount of data needs to be
analyzed to draw statistically significant conclusions. Manual analysis
of the image data is tedious, time-consuming, and subjective. Thus,
computer-based image analysis is needed, which enables fast,
reproducible, and accurate automated analysis of the data.

To extract information from the image data, methods for different image
analysis tasks are required. Typical tasks are image preprocessing,
feature extraction, segmentation, object recognition, tracking, and
image registration. The projects within the topic “Image Analysis” deal
with different image analysis tasks using different methods and
different image modalities.

Objective
---------

#### Digit Recognition:

The objective of projects 1 and 2 is to implement and evaluate
statistical methods for handwritten digit recognition (K-nearest
neighbors, linear discriminant analysis). For both projects, the first
step consists of computing statistical measures for data normalization.
Second, the normalized data should be computed and the handwritten
digits should be visualized. Third, data dimension reduction should be
performed by principal component analysis (PCA) and the results should
be visualized.

-   Project 1: Implementation and evaluation of K-nearest neighbors
    (KNN) algorithm.
-   Project 2: Implementation and evaluation of linear discriminant
    analysis (LDA).

#### Cell Nuclei Segmentation:

The objective of projects 3, 4, and 5 is to implement and evaluate
methods for segmentation of cell nuclei (Otsu thresholding, region
growing, clustering). First, a popular evaluation measure known as “Dice
score” should be implemented and tested using synthetically generated
images. Second, an image segmentation method should be implemented. The
methods should be applied to cell nuclei images and the average Dice
score should be computed. Third, pre-processing methods such as Gaussian
filtering should be investigated to improve the result.

-   Project 3: Implementation and evaluation of Otsu thresholding.
-   Project 4: Implementation and evaluation of region growing.
-   Project 5: Implementation and evaluation of clustering method.

Description of datasets
-----------------------

#### Digit Recognition:

The MNIST database (Modified National Institute of Standards and
Technology database) of handwritten digits consists of a training set
(60,000 images) and a test set (10,000 images). The images are
size-normalized (28×28 pixels) and centered, and stored as csv files.
Each line of these files represents an image. The first column
represents the label (the digit depicted in the image).
Link: http://yann.lecun.com/exdb/mnist/

#### Cell Nuclei Segmentation

The dataset for cell nuclei segmentation consists of 25 images of
bone-marrow derived macrophages from mice from the Broad Bioimage
Benchmark Collection. The cell nuclei were stained with DAPI. The images
have a size of 1388×1040 pixels and show 30–50 cell nuclei per image.
Link: https://data.broadinstitute.org/bbbc/BBBC020/

Literature
----------

#### Digit Recognition:

-   Gerbrands, Jan J. “On the relationships between SVD, KLT and PCA.”
    Pattern Recognition (1981), vol. 14, issues 1-6, pp 375-381
-   McDonnell, Tyler. “Principal Component Analysis of Handwritten
    Digits.”
-   Gareth, James and et al. “An introduction to statistical learning.”
    Springer New York (2013), Chapter: 4.4

#### Cell Nuclei Segmentation

-   Otsu, Nobuyuki. “A threshold selection method from gray-level
    histograms.” IEEE Transactions on Systems, Man, and Cybernetics 9.1
    (1979), pp 62-66.
-   Ljosa, Vebjorn, Katherine L., Sokolnicki and Anne E., Carpenter.
    “Annotated high-throughput microscopy image sets for validation.”
    Nature Methods 9.7 (2012), pp 637-637.
-   Shih F.Y., Cheng S. “Automatic seeded region growing for color image
    segmentation.” Image and Vision Computing (2005), vol. 23, issue 10,
    pp 877-886
-   Szénási S. “Distributed region growing algorithm for medical image
    segmentation.” International Journal of Circuits, Systems and Signal
    Processing (2014), vol. 8, pp 173-181
-   Lin, Z., Jin ,J.S. and Talbot, H. “Unseeded region growing for 3D
    image segmentation.” Proceedings of the Pan-Sydney Area Workshop on
    Visual Information Processing (2000), vol. 2, pp 31-37

How to structure your project
-----------------------------

### Project proposal

For all projects within the topic “Image Analysis” the first task is to
define a **project proposal**, which should include

-   List of planned analysis steps
-   Milestones (important achievements)
-   Deliverables (result for each milestone)
-   Approximate timetable

The project proposal will be presented three weeks after the beginning
of the semester (10 min presentation + 5 min discussion).
