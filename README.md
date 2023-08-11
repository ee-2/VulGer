# VulGer

VulGer is a lexicon covering words from the lower end of the German language register — terms typically considered rough, vulgar, or obscene. Instead of discrete categorical annotations, it includes continuous gradings of vulgarity, from -1 for most vulgar to +1 for most neutral.

The 3,300 words in VulGer were gathered utilizing lexicographic resources and similarity computations based on word embeddings. The vulgarity scores were determined via crowdsourcing (data workers were German native speakers) and Best-worst scaling.

Attention: The dataset contains abusive words. Use it responsibly!

If you use VulGer, please cite:

```
@inproceedings{Eder19,
    title = "At the Lower End of {L}anguage{---}{E}xploring the Vulgar and Obscene Side of {G}erman",
    author = "Eder, Elisabeth  and
      Krieg-Holz, Ulrike  and
      Hahn, Udo",
    booktitle = "Proceedings of the Third Workshop on Abusive Language Online",
    month = aug,
    year = "2019",
    address = "Florence, Italy",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/W19-3513",
    doi = "10.18653/v1/W19-3513",
    pages = "119--128",
}
```
