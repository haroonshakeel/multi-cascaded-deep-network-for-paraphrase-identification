# A multi-cascaded model with data augmentation for enhanced paraphrase detection in short texts
The repository contains the code and trained model for the research paper titled ``A multi-cascaded model with data augmentation for enhanced paraphrase detection in short text``. Kindly cite the paper as:

``@article{SHAKEEL2020102204,
title = "A multi-cascaded model with data augmentation for enhanced paraphrase detection in short texts",
journal = "Information Processing & Management",
volume = "57",
number = "3",
pages = "102204",
year = "2020",
issn = "0306-4573",
doi = "https://doi.org/10.1016/j.ipm.2020.102204",
url = "http://www.sciencedirect.com/science/article/pii/S0306457319307502",
author = "Muhammad Haroon Shakeel and Asim Karim and Imdadullah Khan",
keywords = "Paraphrase detection, Deep learning, Data augmentation, Sentence similarity",
abstract = "Paraphrase detection is an important task in text analytics with numerous applications such as plagiarism detection, duplicate question identification, and enhanced customer support helpdesks. Deep models have been proposed for representing and classifying paraphrases. These models, however, require large quantities of human-labeled data, which is expensive to obtain. In this work, we present a data augmentation strategy and a multi-cascaded model for improved paraphrase detection in short texts. Our data augmentation strategy considers the notions of paraphrases and non-paraphrases as binary relations over the set of texts. Subsequently, it uses graph theoretic concepts to efficiently generate additional paraphrase and non-paraphrase pairs in a sound manner. Our multi-cascaded model employs three supervised feature learners (cascades) based on CNN and LSTM networks with and without soft-attention. The learned features, together with hand-crafted linguistic features, are then forwarded to a discriminator network for final classification. Our model is both wide and deep and provides greater robustness across clean and noisy short texts. We evaluate our approach on three benchmark datasets and show that it produces a comparable or state-of-the-art performance on all three."
}
``

Due to size limitations, the trained model and all the data files cannot be uploaded here. Kindly email the authors at: ``15030040@lums.edu.pk`` or ``akarim@lums.edu.pk``.

The prefix ``_`` represents original dataset without any augmentation.
