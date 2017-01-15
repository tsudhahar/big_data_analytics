# big_data_analytics
# real time analytics from big data sets

### Big Data Technology Stack
* We are in the age of big data. Data has not only become the lifeblood of any organization, but is also growing
exponentially. 
Data generated today is several magnitudes but the challenge is how to get business value out of this data. This is the problem that big data–related
technologies aim to solve. 
* Although the term “big data” is hot, its definition is vague. An example of the former would be a dataset whose
volume exceeds petabytes or several terabytes. If this data were stored in a traditional relational database
(RDBMS) table, it would have billions of rows. Another popular definition of big data is data characterized by three Vs: volume, velocity, and variety.
* Technology for processing and analyzing large datasets has been extensively
researched and available in the form of proprietary commercial products for a long time. For example, MPP
(massively parallel processing) databases have been around for a while. MPP databases use a “shared nothing”
architecture, where data is stored and processed across a cluster of nodes. Each node comes with
its own set of CPUs, memory, and disks. They communicate via a network interconnect. Data is partitioned
across a cluster of nodes. There is no contention among the nodes, so they can all process data in parallel.
Examples of such databases include Teradata, Netezza, Greenplum, ParAccel, and Vertica. Teradata was
invented in the late 1970s, and by the 1990s, it was capable of processing terabytes of data. However,
proprietary MPP products are expensive. Not everybody can afford them.

*Hadoop was one of the first popular open source big data technologies. It is a scalable fault-tolerant system
for processing large datasets across a cluster of commodity servers. It provides a simple programming
framework for large-scale data processing using the resources available across a cluster of computers.
Hadoop is inspired by a system invented at Google to create inverted index for its search product. Jeffrey
Dean and Sanjay Ghemawat published papers in 2004 describing the system that they created for Google.
The first one, titled “MapReduce: Simplified Data Processing on Large Clusters” is available at research.
google.com/archive/mapreduce.html. The second one, titled “The Google File System” is available at
research.google.com/archive/gfs.html. Inspired by these papers, Doug Cutting and Mike Cafarella
developed an open source implementation, which later became Hadoop.
* Hadoop is not really a single product. It consists of
three key components: a cluster manager, a distributed compute engine, and a distributed file system
* Until version 2.0, Hadoop’s architecture was monolithic. All the components were tightly coupled and
bundled together. Starting with version 2.0, Hadoop adopted a modular architecture, which allows you to
mix and match Hadoop components with non-Hadoop technologies.
* The concrete implementations of the three conceptual components are HDFS,
MapReduce, and YARN