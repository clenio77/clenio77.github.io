---
layout: essay  
type: essay  
title: Evidence of Scholarly Ability  
date: 2019-02-18
labels:
  - PhD Portfolio
---

*This page presents evidence of my scholarly ability in computer science as required for the [ICS Ph.D. Portfolio](http://www.ics.hawaii.edu/academics/graduate-degree-programs/ph-d-in-ics/#phd-portfolio). This includes evidence of ability to identify, critically analyze, and research a problem, as well as written communication skills.*

## Publications

*A Transient Classification System Implementation on an Open Source Distributed Power Quality Network*. Charles Dickens, Anthony Christe, Philip Johnson.
Submitted to The Ninth International Conference on Smart Grids, Green Communications and IT Energy-aware Technologies (ENERGY 2019) (2019).

Abstract: Capturing  and  classifying  power  quality  phenomena is  important  for  the  smooth  functioning  of  electrical  grids.  This paper presents methods for classifying the four types of transients(impulsive, arcing, oscillatory, and periodic notching) specified in the IEEE 1159 Power Quality standard. Our methods implement a tractable algorithm which applies   well understood signal processing methods and statistical inference for feature extraction and decision making. We tested our methods on simulated power quality  disturbances  in  order  to  demonstrate  the  capabilities  of the  system.  The  results  of  this  research  include  an  operational implementation of a transient classifier for Open Power Quality,an  open  source  distributed  power  quality  network.  Additional functionality can be easily incorporated into the system to extend the  utility  of  our  methods,  such  as  a  meta-analysis  to  capture higher  level  network  wide  events.

*REAL-TIME MONITORING AND DATA ANALYTICS IN MULTI-SENSING MOBILE SENSOR NETWORKS*. Karina Asmar, Anthony Christe, Brian Williams, Scott Watson, David Chichester, Milton Garces.
Submitted to the ACM Transactions on Data Science (February 2019).

Abstract: The collection of acoustic data through crowdsourcing schemes with multi-sensing smartphones results in
          broadband mobile networks. This introduces a versatile global infrastructure that internally generates vast
          amounts of semi-structured and heterogeneous data streaming at high velocities. In order to extract
          meaningful knowledge and insights from the incoming data streams, protocols related to data
          management, processing, and analytics need to be readdressed. This work presents a data science
          approach for real-time sensor monitoring and acoustic data analysis in multi-sensing mobile networks.
          The ability to generate visual products (e.g., text, tables, graphs, images, maps) in real-time and through
          batch analysis is shown, and the potential use of these products for acoustic feature extraction, signal
          detection, and data-driven decision making is described.

*OPQ Version 2: An Architecture for Distributed, Real-Time, High Performance Power Data Acquisition, Analysis, and Visualization*. Anthony Christe, Sergey Negrashov, Philip Johnson, Dylan Nakahodo, David Badke and David Aghalarpour.
Accepted for publication at the 7th Annual IEEE International Conference on CYBER Technology in Automation, Control, and Intelligent Systems (IEEE-CYBER 2017) (July 2017).

Abstract: OpenPowerQuality (OPQ) is a framework that supports end-to-end capture, analysis, and visualizations of distributed real-time power quality (PQ) data. Version 2 of OPQ builds on version 1 by providing higher sampling rates, optional battery backup, end-to-end security, GPS synchronization, pluggable analysis, and a real-time visualization framework. OPQ provides real-time distributed power measurements which allows users to see both local PQ events and grid-wide PQ events. The OPQ project has three principal components: back-end hardware for making power measurements, middleware for data acquisition and analysis, and a front-end providing visualizations. OPQBox2 is a hardware platform that takes PQ measurements, provides onboard analysis, and securely transfers data to our middleware. The OPQ middleware performs filtering on the OPQBox2 sensor data and performs high-level PQ analysis. The results of our PQ analysis and real-time state of the sensor network are displayed using OPQView. We've collected distributed PQ data from locations across Oahu, Hawaii and have demonstrated our ability to detect both local and grid-wide power quality events.

*OpenPowerQuality: An Open Source Framework for Power Quality Collection, Analysis, Visualization, and Privacy*.
Anthony Christe, Sergey Negrashov, Philip Johnson. 
In Proceedings of the Seventh Conference on Innovative Smart Grid Technologies (ISGT2016) (September 2016).

Abstract: As power grids transition from a centralized distribution model to a distributed model, maintaining grid stability 
requires real-time power quality (PQ) monitoring and visualization. As part of the Open Power Quality (OPQ) project, we 
designed and deployed a set of open source power quality monitors and an open source cloud-based aggregation and 
visualization system built with the utility customer in mind. Our aim is to leverage a flexible privacy model combined 
with inexpensive and easy to use PQ meters in order to deploy a high density power quality monitoring network across the
Hawaiian islands. In this paper we describe OPHub, a privacy focused open source PQ visualization along with results of 
a small scale deployment of our prototype PQ meter across the island of Oahu. Our results demonstrate that OPQ can 
provide useful power quality data at an order of magnitude less cost than prior approaches.

My specific contributions to this paper involve the discussions on privacy, visualizations, and sofwtware development.

[Full Paper](http://csdl.ics.hawaii.edu/techreports/2016/16-02/16-02.pdf)

## PhD Proposal

*Laha: A framework for adaptive optimization of distributed sensor networks*
Anthony Christe
November, 2018. CSDL Tech Report CSDL-18-02.

Abstract: Distributed Sensor Networks (DSNs) are faced with a myriad of technical challenges. This dissertation examines two important DSN challenges. One problem that is apparent in any DSN is converting “primitive” sensor data into actionable products and insights. For example, a DSN for power quality (PQ) might gather primitive data in the form of raw voltage waveforms and produce actionable insights in the form of classified power quality events such as voltage sags or frequency swells or provide the ability to predict when PQ events are going to occur by observing cyclical data. For another example, a DSN for infrasound might gather primitive data in the form of microphone counts and produce actionable insight in the form of determining what, when, and where the signal came from. To make progress towards this problem, DSNs typically implement one or more of the following strategies: detecting signals in the primitive data (deciding if something is there), classification of signals from primitive data (deciding what is there), localization of signals (when and where did the signals come from), and by forming relationships between primitive data by finding correlations between spatial attributes, temporal attributes, and by associating metadata with primitive data to provide contextual information not collected by the DSN. These strategies can be employed recursively. As an example, the result of aggregating typed primitive data provides a new higher level of types data which contains more context than the data from which is was derived from. This new typed data can itself be aggregated into new, higher level types and also participate in relationships. A second important challenge is managing data volume. Most DSNs produce large amounts of (increasingly multimodal) primitive data, of which only a tiny fraction (the signals) is actually interesting and useful. The DSN can either utilize one of two strategies: keep all of the information and primitive data forever, or employ some sort of strategy for systematically discarding (hopefully uninteresting and not useful) data. As sensor networks scale in size, the first strategy becomes unfeasible. Therefore, DSNs must find and implement a strategy for managing large amounts of sensor data. The difficult part is finding an effective and efficient strategy deciding what data is interesting and must be kept and what data to discard. This dissertation investigates the design, implementation, and evaluation of the Laha framework, which is intended to address both of these problems. First, the Laha framework provides a multi-leveled representation for structuring and processing DSN data. The structure and processing at each level is designed with the explicit goal of turning low-level data into actionable insights. Second, each level in the framework implements a “time-to-live” (TTL) strategy for data within the level. This strategy states that data must either “progress” upwards through the levels towards more abstract, useful representations within a fixed time window, or be discarded and lost forever. The TTL strategy is interesting because when implemented, it allows DSN designers to calculate upper bounds on data storage at each level of the framework and supports graceful degradation of DSN performance.

[Full Paper](http://csdl.ics.hawaii.edu/techreports/2018/18-02/18-02.pdf)

## Literature Review

*Data Management for Distributed Sensor Networks: A Literature Review*
Anthony Christe. CSDL Tech Report CSDL-17-01.

Abstract: Sensor networks are spatially distributed autonomous sensors that monitor the physical world around them and often communicate those reading over a network to a server or servers. Sensor networks can benefit from the generally ``unlimited resources'' of the cloud, namely processing, storage, and network resources. This literature review surveys the major components of distributed data management, namely, cloud computing, distributed persistence models, and distributed analytics.

[Full Paper](http://csdl.ics.hawaii.edu/techreports/2017/17-01/17-01.pdf)

## Technical Reports

*OPQ Cloud: A scalable software framework for the aggregation of distributed power quality data*
Anthony Christe.
April, 2014. CSDL Tech Report CSDL-14-04.

Abstract: Power quality issues can be caused in a variety of situations. Voltage fluctuations, frequency fluctuations, and 
harmonics are all power quality issues which can be caused by weather, high penetration of renewables, man-made issues, 
or other natural phenomena. We designed a software framework which can aggregate crowdsourced distributed power quality 
measurements in order to study power quality issues over a dense geographic area.

[Full Paper](https://github.com/csdl/techreports/raw/master/techreports/2014/14-04/14-04.pdf)
