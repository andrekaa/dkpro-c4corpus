# DKPro C4CorpusTools

DKPro C4CorpusTools is a collection of tools for processing CommonCrawl corpus, including Creative
Commons license detection, boilerplate removal, language detection, and near-duplicate removal. 

* **DKPro C4CorpusTools** (or C4CorpusTools) refers to the project source codes
* **C4Corpus** refers the preprocessed CommonCrawl data set (**C4** =
 **C**reative **C**ommons from **C**ommon **C**rawl)

Please use the following citation if you use C4Corpus or C4CorpusTools

```
@InProceedings{Habernal.et.al.2016.LREC,
  author    = {Habernal, Ivan and Zayed, Omnia, and Gurevych, Iryna},
  title     = {{C4Corpus: Multilingual Web-size Corpus with Free License}},
  booktitle = {Proceedings of the Tenth International Conference on Language Resources
               and Evaluation (LREC 2016)},
  pages     = {914--922},
  month     = {May},
  year      = {2016},
  address   = {Portoro\v{z}, Slovenia},
  publisher = {European Language Resources Association (ELRA)},
  editor    = {Nicoletta Calzolari and Khalid Choukri and Thierry Declerck and Marko Grobelnik
               and Bente Maegaard and Joseph Mariani and Asuncion Moreno and Jan Odijk
               and Stelios Piperidis},
  isbn      = {978-2-9517408-9-1},
  url       = {http://www.lrec-conf.org/proceedings/lrec2016/pdf/388_Paper.pdf}
}
```

The full LREC article is available at the [UKP website](https://www.ukp.tu-darmstadt.de/publications/details/?tx_bibtex_pi1[pub_id]=TUD-CS-2016-0023).

* **Contact person:** Ivan Habernal, habernal@ukp.informatik.tu-darmstadt.de
    * UKP Lab: http://www.ukp.tu-darmstadt.de/
    * TU Darmstadt: http://www.tu-darmstadt.de/


Consult the official [C4CorpusTools documentation](https://zoidberg.ukp.informatik.tu-darmstadt.de/jenkins/job/DKPro%20C4Corpus/org.dkpro.c4corpus$dkpro-c4corpus-doc/doclinks/1/)
which contains

* C4Corpus Users's Guide
    * How to access C4Corpus at S3
    * Running boilerplate removal outside Hadoop
    * Examples of simple search in C4Corpus
* C4Corpus Developers's Guide
    * How to run the full processing pipeline on CommonCrawl
* Corpus statistics reported in the LREC article

As of May 2017, thanks to CommonCrawl the C4Corpus is hosted at their S3 bucket. This makes it much easier to access the data using HTTP (see the documentation). 