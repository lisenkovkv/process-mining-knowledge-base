# Process mining

## Datasets
* [Real life Event Logs](https://data.4tu.nl/repository/collection:event_logs_real)
* [Synthetic Event Logs](https://data.4tu.nl/repository/collection:event_logs_synthetic)

## Core resourses
* [Process Mining Manifesto](https://www.win.tue.nl/ieeetfpm/downloads/Process%20Mining%20Manifesto.pdf)
This manifesto is written by members and supporters of the IEEE Task Force on Process Mining. The goal of this task force is to promote the research, development, education, implementation, evolution, and understanding of process mining.
* http://www.processmining.org/
* [PM^2: a Process Mining Project Methodology](http://www.processmining.org/_media/blogs/pub2015/pm2_processminingprojectmethodology.pdf) A methodology to guide the execution of process mining projects.
* [IEEE CIS Task Force on Process Mining](https://www.win.tue.nl/ieeetfpm/doku.php)  The IEEE has established a Task Force on Process Mining. The goal of Task Force is to promote the research, development, education and understanding of process mining.

## Conferences
* [Process Mining Conference Series](https://icpmconference.org)

## Videos
* [Process Mining Data Science in Action - Wil van der Aalst](https://youtu.be/kIeLaNzw9hI)
* [Introduction to Event Log Mining with R](https://youtu.be/_KMiEEStB9g). Content: the scenarios and benefits of event log mining; The minimum data required for event log mining; Ingesting and analyzing event log data using R; Process Mining with ProM; Event log mining techniques to create features suitable for Machine Learning models; Where you can learn more about this very handy set of tools and techniques.

## Research divisions
* [Laboratory of Process-Aware Information Systems](https://pais.hse.ru/en/)

## Books
* [Process Mining: Data Science in Action](http://www.processmining.org/book/start). This is the second edition of Wil van der Aalst’s seminal book on process mining, which now discusses the field also in the broader context of data science and big data approaches. It includes several additions and updates, e.g. on inductive mining techniques, the notion of alignments, a considerably expanded section on software tools and a completely new chapter of process mining in the large. It is self-contained, while at the same time covering the entire process-mining spectrum from process discovery to predictive analytics.
* [A Primer on Process Mining.Practical Skills with Python and Graphviz](https://www.springer.com/gp/book/9783319564265).The main goal of this book is to explain the core ideas of process mining, and to demonstrate how they can be implemented using just some basic tools that are available to any computer scientist or data scientist. It describes how to analyze event logs in order to discover the behavior of real-world business processes. The end result can often be visualized as a graph, and the book explains how to use Python and Graphviz to render these graphs intuitively. Overall, it enables the reader to implement process mining techniques on his or her own, independently of any specific process mining tool. An introduction to two popular process mining tools, namely Disco and ProM, is also provided.

## Competitions
* [First International Business Process Intelligence Challenge (BPIC’11)](https://www.win.tue.nl/bpi/doku.php?id=2011:challenge)
* [Second International Business Process Intelligence Challenge (BPIC’12)](https://www.win.tue.nl/bpi/doku.php?id=2012:challenge)
* [Third International Business Process Intelligence Challenge (BPIC’13)](https://www.win.tue.nl/bpi/doku.php?id=2013:challenge)
* [Fourth International Business Process Intelligence Challenge (BPIC’14)](https://www.win.tue.nl/bpi/doku.php?id=2014:challenge)
* [Fifth International Business Process Intelligence Challenge (BPIC’15)](https://www.win.tue.nl/bpi/doku.php?id=2015:challenge)
* [Sixth International Business Process Intelligence Challenge (BPIC’16)](https://www.win.tue.nl/bpi/doku.php?id=2016:challenge)
* [Seventh International Business Process Intelligence Challenge (BPIC’17)](https://www.win.tue.nl/bpi/doku.php?id=2017:challenge)
* [Eighth International Business Process Intelligence Challenge (BPIC’18)](https://www.win.tue.nl/bpi/doku.php?id=2018:challenge)
* [Ninth International Business Process Intelligence Challenge (BPIC’19)](https://icpmconference.org/2019/icpm-2019/contests-challenges/bpi-challenge-2019/)
* [Process Discovery Contest](https://icpmconference.org/2019/process-discovery-contest)
* [Conformance Checking Challenge 2019](https://icpmconference.org/2019/icpm-2019/contests-challenges/1st-conformance-checking-challenge-2019-ccc19/)

## Courses
* [Introduction to process mining with ProM](https://www.futurelearn.com/courses/process-mining)
* [Process Mining: Data science in Action](https://www.coursera.org/learn/process-mining)
* [Process mining in healthcare](https://www.futurelearn.com/courses/process-mining-healthcare)

## Software
* [PM4PY](http://pm4py.org/). PM4Py is a python library that supports (state-of-the-art) process mining algorithms in python. It is completely open source and intended to be used in both academia and industry projects.
* [ProM](http://www.promtools.org/). ProM is an extensible framework that supports a wide variety of process mining techniques in the form of plug-ins. It is platform independent as it is implemented in Java, and can be downloaded free of charge. We welcome and support practical applications of ProM, and we invite researchers and developers to contribute in the form of new plug-ins.
* [Disco](https://fluxicon.com/disco/)
* [ProcessExplorer](https://fileserver.tk.informatik.tu-darmstadt.de/AS/processexplorer/). ProcessExplorer is an academic process mining tool which guides analysts through event logs by suggesting subset and insights recommendations.
* [bupaR](https://www.bupar.net/). bupaR is an open-source, integrated suite of R-packages for the handling and analysis of business process data. It currently consists of 8 packages, including the central package, supporting different stages of a process mining workflow.

## Reviews
* [Process Mining: A DATABASE OF APPLICATIONS](https://www.win.tue.nl/ieeetfpm/lib/exe/fetch.php?media=news:process_mining_database_applications_2018b.pdf). The idea of creating the present database of applications came up within HSPI in 2016, during an informal meeting about process mining technology and its spread over several business – and not only – situations. The need to collect, to put into an ordered system all the historical information about process mining techniques implementations has led the creation of the very first version of " Process Mining: A Database of Applications".
* [Automated Discovery of Process Models from Event Logs: Review and Benchmark](https://arxiv.org/abs/1705.02288). Process mining allows analysts to exploit logs of historical executions of business processes to extract insights regarding the actual performance of these processes. One of the most widely studied process mining operations is automated process discovery. An automated process discovery method takes as input an event log, and produces as output a business process model that captures the control-flow relations between tasks that are observed in or implied by the event log. Various automated process discovery methods have been proposed in the past two decades, striking different tradeoffs between scalability, accuracy and complexity of the resulting models. However, these methods have been evaluated in an ad-hoc manner, employing different datasets, experimental setups, evaluation measures and baselines, often leading to incomparable conclusions and sometimes unreproducible results due to the use of closed datasets. This article provides a systematic review and comparative evaluation of automated process discovery methods, using an open-source benchmark and covering twelve publicly-available real-life event logs, twelve proprietary real-life event logs, and nine quality metrics. The results highlight gaps and unexplored tradeoffs in the field, including the lack of scalability of some methods and a strong divergence in their performance with respect to the different quality metrics used.

## Implemenation (github)
* [Predictive Performance Monitoring of Material Handling Systems Using the Performance Spectrum"](https://github.com/processmining-in-logistics/psm/tree/ppm)
* [Assessing Big Data SQL Frameworks for Analyzing Event Logs; Classifying Processes Instances Using Recurrent Neural Networks; Exploiting Event Log Event Attributes in RNN Based Prediction; Structural Feature Selection from Event Logs](https://github.com/mhinkka/articles)
* [MINERful](https://github.com/cdc08x/MINERful)
* [Comprehensive Process Drift Detection with Visual Analytics (VDD technique)](https://github.com/yesanton/Process-Drift-Visualization-With-Declare)
* [pmbot - A Telegram Bot for Process Mining tasks](https://github.com/delas/pmbot), [paper](https://andrea.burattin.net/public-files/publications/2019-bpm-demo.pdf)
