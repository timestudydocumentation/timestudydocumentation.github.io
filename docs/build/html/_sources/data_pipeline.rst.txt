Data description and codebook
============================

The rich data collected in TIME study are processed and stored at different levels to serve different purposes and researchers with various programming backgrounds. They include data and logs in original form that preserves maximal information, intermediate data that are processed with modest manners to have a cleaner format, pre-processed data that have a refined format and can be directly imported into statistical softwares, and project-specific data that are generated for project-specific purposes. Details about these datasets can be found in their codebooks.

.. image:: /images/flowcharts.png

**Baseline, 6-month, and 12-month online questionnaires**

*Description*: Sociodemographic variables, mental health characteristics, health status, health behaviors, and other covariates are assessed at three time points (baseline, 6 months, 12 months) using online electronic questionnaires completed remotely on a computer, tablet, or smartphone. The surveys were administered through USC’s REDCap system. 

*Location*: REDCap system

*Codebook*: `Link <https://docs.google.com/document/d/141SUkhgxjFvOxgMI8WeZ6W0PfGbvQeFm/edit?usp=sharing&ouid=114892255827597694084&rtpof=true&sd=true>`_

**Raw data and logs (recommended for experienced programmer)**

*Description*: all data and logs are encrypted and stored in their raw format after being directly pulled from devices. It contains all kinds of logs including those used for debugging purposes. Most files have data format issues, such as missing headers, duplicate rows, logging errors, etc.

*Location*: discovery cluster

*Codebook*: `Link <https://docs.google.com/document/d/1P_EFLPf1ovy7Q1KxJqeJcsvjVorTU3F5/edit?usp=sharing&ouid=114892255827597694084&rtpof=true&sd=true>`_

**Intermediate data (recommended for experienced programmer)**

*Description*: data and logs are extracted from the raw data and logs and cleaned to be free of format issues as in raw data format. Every file is stored in csv format with a header. Researchers with strong programming skills can start analysis with data at this stage. See more details about data processing of first, second, and third passes on discovery cluster `here <https://docs.google.com/presentation/d/16MweNpNtCRuGesIusS8MOqcHZurvukfOXVf_9RZ9iCU/edit?usp=sharing>`_.

*Location*: discovery cluster

*Codebook*: `Link <https://docs.google.com/document/d/1ICuqKXCl5JkM5RjU1WNQs4hphxWwTz-E/edit?usp=sharing&ouid=114892255827597694084&rtpof=true&sd=true>`_

**Daily report**

*Description*: a single csv file that contains an aggregated summary of statistics for each day and participant. Files are at day level for each participant, and stored in /participantID/YYYY-MM-DD/. This file was originally used for compliance check during the study.

*Location*: discovery cluster

*Codebook*: `Link <https://docs.google.com/document/d/1LqaMriSpHDn5IUJGW9jtkihuh8c13KEB/edit?usp=sharing&ouid=114892255827597694084&rtpof=true&sd=true>`_

**EMA dataset**

*Description*: a single csv file of all prompted EMA surveys and responses, including EMA Measurement Burst Data, EMA Daily Data, and EMA Weekly (i.e., Sunday) Data (with the COVID questionnaire).

*Location*: discovery cluster

*R code and instruction*: `Link <https://docs.google.com/document/d/13EoBgT_0VB44rKQFtlAsggnM2fLqUag061D9LTSnE04/edit?usp=sharing>`_

*Codebook*: `Link <https://docs.google.com/document/d/1FWptC9_fXnegkQQ83WY8QS1hdh_tjm9jZjQftkp3qyo/edit?usp=sharing>`_
