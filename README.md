# Process mining
## Core resourses
* [Process Mining Manifesto](https://www.win.tue.nl/ieeetfpm/downloads/Process%20Mining%20Manifesto.pdf)
* http://www.processmining.org/

## Conferences
* https://icpmconference.org

## Videos
* [Process Mining Data Science in Action - Wil van der Aalst](https://youtu.be/kIeLaNzw9hI)

## Research divisions
* [Laboratory of Process-Aware Information Systems](https://pais.hse.ru/en/)

## Books
* [A Primer on Process Mining.Practical Skills with Python and Graphviz](https://www.springer.com/gp/book/9783319564265)

## Competitions
* [First International Business Process Intelligence Challenge (BPIC’11)](https://www.win.tue.nl/bpi/doku.php?id=2011:challenge)
* [Conformance Checking Challenge 2019](https://icpmconference.org/2019/icpm-2019/contests-challenges/1st-conformance-checking-challenge-2019-ccc19/)

## Courses
* [Introduction to process mining with ProM](https://www.futurelearn.com/courses/process-mining)
* [Process Mining: Data science in Action](https://www.coursera.org/learn/process-mining)
* [Process mining in healthcare](https://www.futurelearn.com/courses/process-mining-healthcare)

## Software
* [PM4PY](http://pm4py.org/)
* [ProM](http://www.promtools.org/)
* [Disco](https://fluxicon.com/disco/)
* [ProcessExplorer](https://fileserver.tk.informatik.tu-darmstadt.de/AS/processexplorer/)

## Reviews
* [Process Mining: A DATABASE OF APPLICATIONS](https://www.win.tue.nl/ieeetfpm/lib/exe/fetch.php?media=news:process_mining_database_applications_2018b.pdf)

The reason for carrying out this research is to create the most complete list of all the adoptions of process mining techniques and
to collect, directly from who has been involved, basic information about the utilization of this methodology.
The purpose of the study is to create a database of practical cases, no matter the specific industries and the final results, with the
only aim of completeness and validity.
The intended audience includes all those researchers, data scientists, managers and firms that are willing to implement process
mining solutions or simply explore business potentials of process mining in improving business processes or in developing new
performance management practices based on real data, extracted from IT systems.
Therefore, the final goal of this knowledge endeavour still remains the same of the first edition, which is to contribute to build
awareness and confidence about process mining methods

## Papers

### Data preprocessing

* [Developing Process Mining ToolsAn Implementation of Sequence Clustering for ProM](https://fenix.tecnico.ulisboa.pt/downloadFile/395139038542/Resumo_Alargado_54276.pdf)

**Abstract**

The goal of process mining is to discover process models from event logs. However, for processes that are not well structured and have
a lot of diverse behavior, existing process mining techniques generate highly complex models that are often difficult to understand; these are called spaghetti models. One way to try to understand these models is to divide the log into clusters in order to analyze reduced sets of cases. However, the amount of noise and ad-hoc behavior present in real-world logs still poses a problem, as this type of behavior interferes with the clustering and complicates the models of the generated clusters, affecting the discovery of patterns. In this work we present an approach that aims at overcoming these difficulties by extracting only the useful data and presenting it in an understandable manner. The solution has been implemented in ProM and is divided in two stages: preprocessing and sequence clustering. We illustrate the approach in a case study where it becomes possible to identify behavioral patterns even in the presence of very diverse and confusing behavior.

**Key words:** Process Mining, Preprocessing, Sequence Clustering, ProM, Markov Chains, Event Logs, Hierarchical Clustering, Process Models


### Model quality
* [Filtering Toolkit: Interactively Filter Event Logs to Improve the Quality of Discovered Models](http://www.alessandroberti.it/interactive_filtering.pdf)

**Abstract** 

Process discovery algorithms discover process models on the basis of
event data automatically. These techniques tend to consider the entire log to discover a process model. However, real-life event logs usually contain outlier behaviour that lead to incomprehensible, complex and inaccurate process models
where correct and/or important behaviour is undetectable. Hence, removing outlier behaviour thanks to filtering techniques is an essential step to retrieve a good
quality process model. Manually filtering the event log is tricky and requires a
significant amount of time. On the other hand, some work in the past is focused
on providing a fully automatic choice of the parameters of the discovery and filtering algorithms; however, the attempts were not completely successful. This
demo paper describes an easy-to-use plug-in in the ProM process mining framework, that provides a view where several process discovery and outlier filtering
algorithms can be chosen, along with their parameters, in order to find a sweet
spot leading to a ’good’ process model. The filtered log is easily accessible, and
the process model is shown inside the view, in this way the user can immediately
evaluate the quality of the chosen combination between process discovery and
filtering algorithms, and is effectively assisted in the choice of the preprocessing
methodology. Some commonly used metrics (fitness, precision) are reported in
the view provided by the plug-in, in order to ease the evaluation of the process
model. With the options provided by our plug-in, the difficulties of both fullymanual and automatic choice of the filtering approach are effectively overcome.

**Keywords:** 
Process Mining, Process Discovery, Outlier Detection, Interactive Filtering, Quality Improvement

* [Process Discovery using Classification Tree Hidden Semi-Markov Model](https://arxiv.org/ftp/arxiv/papers/1807/1807.04415.pdf)

**Abstract**

Various and ubiquitous information systems are being used in monitoring, exchanging, and collecting information. These systems are generating massive amount of event sequence logs that may help us understand underlying phenomenon. By analyzing these logs, we can learn process models that describe system procedures, predict the development of the system, or check whether the changes are expected. In this paper, we consider a novel technique that models these sequences of events in temporal-probabilistic manners. Specifically, we
propose a probabilistic process model that combines hidden semi-Markov model and classification trees learning. Our experimental result shows that the proposed approach can answer a kind of question–“what are the most frequent sequence of system dynamics relevant to a given sequence of observable events?”. For example, “Given a series of medical treatments, what are the most relevant patients’ health condition pattern changes at different times?”

**Keywords:** Hidden Semi-Markov Models, Classification and Regression Tree, Process Discovery, Temporal Data Mining

### Hidden Markov Models

* [Using Hidden Markov Models to Evaluate the Quality of Discovered Process Models](http://bpmcenter.org/wp-content/uploads/reports/2008/BPM-08-10.pdf)

**Abstract**

Hidden Markov Models (HMMs) are a stochastic signal modeling formalism that is actively used in the machine learning community
for a wide range of applications such as speech and activity recognition.Efficient techniques exist to learn HMM models from a given data set, and to estimate the data likelihood with respect to a given HMM (i.e., “How probable is it that these data were produced by this HMM?”). The latter enables the evaluation and selection of suitable models. In the domain of process mining the evaluation of models (i.e., “How can we measure the quality of a mined process model?”) is still subject to ongoing research. Because the types of models used in process mining are typically on a higher level of abstraction (i.e., they are more expressive as
they, for example, allow to capture concurrency), the problem of model evaluation is challenging. In this paper, we investigate the possibilities and limitations of using HMMs for evaluating process models and compare the resulting quality measurements to the metrics typically used in the process mining domain.

* [Evaluating the Quality of Discovered Process Models](http://www.padsweb.rwth-aachen.de/wvdaalst/publications/p473.pdf)

**Abstract**

In the domain of process mining the evaluation of models (i.e., “How can we measure the quality of a mined process model?”) is
still subject to ongoing research. Because the types of models used in process mining are typically on a higher level of abstraction (they, for example, allow to capture concurrency), the problem of model evaluation is challenging. In this paper, we elaborate on the problem of process model evaluation, and we evaluate both new and existing fitness metrics for different levels of noise. The new metrics and the noise generation are based on Hidden Markov Models (HMMs).

* [A Novel Approach for Process Mining : Intentional Process Models Discovery](https://hal-paris1.archives-ouvertes.fr/hal-00994157v2/document)

**Abstract**

So far, process mining techniques have suggested to model processes in terms of tasks that occur during the enactment of a process. However, research on method engineering and guidance has illustrated that many issues, such as lack of flexibility or adaptation, are solved more effectively when intentions are explicitly specified. This paper presents a novel approach of process mining, called Map Miner Method (MMM). This method is designed to automate the construction of intentional process models from process logs. MMM uses
Hidden Markov Models to model the relationship between users’ activities logs and the strategies to fulfill their intentions. The
method also includes two specific algorithms developed to infer users’ intentions and construct intentional process model (Map)
respectively. MMM can construct Map process models with different levels of abstraction (fine-grained and coarse-grained process models) with respect to the Map metamodel formalism (i.e., metamodel that specifies intentions and strategies of process actors). This paper presents all steps toward the construction of Map process models topology. The entire method is applied on a large-scale case study (Eclipse UDC) to mine the associated intentional process. The likelihood of the obtained process model shows a satisfying efficiency for the proposed method.

**Keywords:** Intention-oriented Process Modeling, Process Mining, unsupervised learning

* [Hidden Markov Model for Process Mining of Parallel Business Processes](https://pdfs.semanticscholar.org/d8db/ce6e94734983d83af0a8e380c4611dd3ba14.pdf)

**Abstract**

One of all the works on process mining is the process discovery which produces a representation of a parallel business process. This representation is called process model and it consists of sequence and parallel control-flow patterns. The parallel control-flow patterns contain XOR, AND, and OR relations. Hidden Markov Model is rarely used to represent a process model since XOR, AND and OR relations are not visible. In Hidden Markov Model, the control-flow patterns are represented by probabilities of state transitions. This research proposes an algorithm consisting in a process discovery based on Hidden Markov Model. This algorithm contains equations and rules: the equations are used to differentiate XOR, AND, and OR relations, while the rules are used to establish the process model utilizing detected control-flow patterns. The experiment results show that the proposed algorithm obtain the right control-flow patterns in the process model. The paper demonstrates that the fitness of process models obtained by the proposed algorithm are relatively higher respect to those obtained by Heuristics Miner and Timebased Heuristics Miner algorithms. This paper also shows that the validity of process models obtained by the proposed algorithm are better than those obtained by other algorithms. 

**Keywords:** Fitness, Hidden Markov Model, Parallel Business Process, Process Mining, Validity

* [Coupled Hidden Markov Model for Process Mining of Invisible Prime Tasks](https://lbeifits.files.wordpress.com/2018/03/9555-17553-1-pb-chmm.pdf)

**Abstract**

Process mining provides process improvement in a variety of application domains. A primary focus of process mining is transferring information from event logs into process model. One of the issues of process mining is dealing with invisible prime tasks. An invisible prime task is an additional task in the process model to assist in showing real processes. However, a few of algorithm solves the issue. This research proposes an algorithm for dealing with invisible prime tasks. The proposed algorithm contains rules and equations utilizing probability of state transition of Coupled Hidden Markov and double time-stamped in event logs. The rules and equations are
used for determining invisible prime tasks and parallel control-flows patterns. In addition to dealing with invisible prime tasks, the experiment results also show that the proposed algorithm obtains right parallel control-flow patterns from non-complete event logs. This proposed algorithm also decreases usage of the invisible prime task in A# algorithm without reducing the quality of discovered process models. It has proven with the fitness of process models obtained by the proposed algorithm are relatively high as those obtained by A# algorithm.

**Keywords:** Coupled Hidden Markov Model, Double Time-stamped Event Log, Fitness, Invisible Prime Tasks, Process Mining
