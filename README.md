# SimplifyUR

This repository contains code, dataset and models for Urdu text simplification as described in paper [SimplifyUR: Unsupervised Lexical Text Simplification for Urdu](http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.428.pdf).

# Requirement(s)

The source is available as a [Jupyter](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) notebook for a Python 3 kernel. Please see [requirements.txt](requirements.txt) for details.

# Model(s)

Pre-trained models including Word2Vec, Parts of Speech (PoS) tagger and Language Model (LM) are [available for download](https://drive.google.com/file/d/1RVW7C-d6hOqIPOiYVHWqiicaYaFloLeo/view). Download and extract them to root directory, SimplifyUR.

# Dataset

A parallel corpus of [complex](Data/Complex.txt)-[simplified](Data/Simplified.txt) Urdu sentence-pairs is the [Data](Data) folder.


# Reference(s)

If you use this tool in any of your work, please cite below paper.

[SimplifyUR: Unsupervised Lexical Text Simplification for Urdu](http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.428.pdf)

```
@InProceedings{qasmi-EtAl:2020:LREC,
  author    = {Qasmi, Namoos Hayat  and  Zia, Haris Bin  and  Athar, Awais  and  Raza, Agha Ali},
  title     = {SimplifyUR: Unsupervised Lexical Text Simplification for Urdu},
  booktitle      = {Proceedings of The 12th Language Resources and Evaluation Conference},
  month          = {May},
  year           = {2020},
  address        = {Marseille, France},
  publisher      = {European Language Resources Association},
  pages     = {3484--3489},
  url       = {https://www.aclweb.org/anthology/2020.lrec-1.428}
}

```

# License(s)

Copyright (c) 2020 CSaLT, ITU

Code licensed under the MIT License: http://opensource.org/licenses/MIT.
Data licensed under CC-BY 4.0: https://creativecommons.org/licenses/by/4.0/
