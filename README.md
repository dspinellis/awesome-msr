# awesome-msr [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated repository of data sets and tools that can be used for data-driven empirical software engineering, a method also known as _mining software repositories_ (MSR). For examples of such work see the [Mining Software Repositories](http://2016.msrconf.org/#/hall-of-fame) conference.
Many of the data set can also be useful in research using [search-based software engineering](https://en.wikipedia.org/wiki/Search-based_software_engineering).


- This list requires your input for its continuous improvement.
  Read the [contribution guide](contributing.md) for instructions on how
  you can contribute.
  Alternatively, you can send me an [email](mailto:dds@aueb.gr)
  if you find the process too cumbersome or confusing.
- For more awesome lists, see [awesome](https://github.com/sindresorhus/awesome).

## Contents

- [Data Sets](#data-sets)
- [Tools](#tools)


## Data Sets

* [AndroZoo](https://androzoo.uni.lu/) - A growing collection of Android Applications
* [Boa](http://boa.cs.iastate.edu/) - A domain-specific language and infrastructure that eases mining software repositories
* [Bug Prediction Dataset](http://bug.inf.usi.ch/index.php) - A collection of models and metrics from Eclipse JDT Core, PDE UI, Equinox Framework, Lucene, Mylyn, and their histories 
* [Code Reviews](http://kin-y.github.io/miningReviewRepo/) - Code reviews of OpenStack, LibreOffice, AOSP, Qt, Eclipse
* [CoREBench](http://www.comp.nus.edu.sg/%7Erelease/corebench/) - A collection of 70 realistically Complex Regression Errors that were systematically extracted from the repositories and bug reports of four open-source software projects: Make, Grep, Findutils, and Coreutils
* [Defects4J](https://github.com/rjust/defects4j) - A collection of 395 reproducible bugs collected with the goal of advancing software testing research
* [Enron Spreadsheets and Emails](https://figshare.com/articles/Enron_Spreadsheets_and_Emails/1221767) - All the spreadsheets and emails used in the paper 'Enron's Spreadsheets and Related Emails: A Dataset and Analysis'
* [Findbugs-maven](https://github.com/istlab/maven_bug_catalog) - A set of FindBugs reports for the Java projects of the [Maven repository](https://maven.apache.org)
* [GHTorrent](http://ghtorrent.org/) - A scalable, queriable, offline mirror of data offered through the Github REST API
* [GitHub on Google BigQuery](https://cloud.google.com/bigquery/public-data/github) - GitHub data accessible through Google's BigQuery platform
* [KaVE](http://www.kave.cc/datasets) - Developer tool interaction data
* [Maven metrics](https://github.com/bkarak/data_msr2015) - A collection of software complexity & sizing metrics for the [Maven Repository](https://maven.apache.org)
* [mzdata](https://github.com/jxshin/mzdata) - Multi-extract and multi-level dataset of Mozilla issue tracking history
* [RepoReapers Data Set](https://reporeapers.github.io) - A data set containing a collection of _engineered software projects_ from GHTorrent.
* [SIR](http://sir.unl.edu/portal/index.php) - Software-artifact infrastructure repository; Java, C, C++, and C# software together with test suites and fault data
* [STAMINA](http://stamina.chefbe.net/download) - (STAte Machine INference Approaches) data are used to benchmark techniques for learning deterministic finite state machines (FSMs)
* [Stack Exchange](https://archive.org/details/stackexchange) - An anonymized dump of all user-contributed content on the Stack Exchange network.
* [tera-PROMISE](http://openscience.us/repo/) - A research dataset repository specializing in software engineering research datasets. This has now been moved to [Zenodo](https://zenodo.org) and is called [SeaCraft](http://zenodo.org/communities/seacraft)
* [TravisTorrent](http://travistorrent.testroots.org) - Provides free and easy-to-use Traivs CI build analyses.
* [Unix history](https://github.com/dspinellis/unix-history-repo) - A Git repository with 46 years of Unix history evolution

## Tools

* [ckjm](http://www.spinellis.gr/sw/ckjm/) - Chidamber and Kemerer Java Metrics
* [MetricMiner](http://www.github.com/mauricioaniche/metricminer2) - A lean Java DSL to
mine and extract data (e.g. commits, developers, modifications, diffs) from Git and SVN repositories
* [qmcalc](https://github.com/dspinellis/cqmetrics) - Calculate quality metrics from C source code
* [reaper](https://github.com/RepoReapers/reaper) - A Python tool to compute a score for a repository from GHTorrent. The score quantifies the extent to which the project contained within the repository is _engineered_.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Diomidis Spinellis](http://www.spinellis.gr) has waived all copyright and related or neighboring rights to this work.
