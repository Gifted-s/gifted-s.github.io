![Adewumi Sunkanmi](https://firebasestorage.googleapis.com/v0/b/generalsapi.appspot.com/o/DOC-20230730-WA0025.jpeg?alt=media&token=44963a33-8f13-4825-94e8-d48b411660e5)


[![Email](https://img.icons8.com/material-outlined/24/000000/email.png)](mailto:sunkanmiadewumi477@gmail.com) 
[![Twitter](https://img.icons8.com/material-outlined/24/000000/twitter.png)](https://x.com/gifted_dl) 
[![LinkedIn](https://img.icons8.com/material-outlined/24/000000/linkedin.png)](https://www.linkedin.com/in/adewumisunkanmi/) 
[![Recommendation](https://img.icons8.com/material-outlined/24/000000/checkmark.png)](https://www.linkedin.com/in/adewumisunkanmi/#:~:text=Recommendations,Recommendations)

# Adewumi Sunkanmi D.
_Passionate about Database Systems, Big Data, and Education_

<p>Data is crucial to many organizations, from daily transactions to driving decisions to training AI models. Despite this immense potential, it can come from diverse sources in different formats, structures, and sizes, making data management non-trivial. The wide range of use cases for data provides ample room for innovation, inspiring my interest in Database Systems, Big Data Analytics, and Data Engineering. My most recent project is <a href="https://x.com/andy_pavlo/status/1820436583977275426" target="_blank">VelarixDB</a>, which leverages the high throughput that <i>io_uring</i> provides and also reduces IO amplification by up to 50x by adopting the WiscKey paper from the University of Wisconsin-Madison. </p>

<p>I come from a developing country (Nigeria) where database research is not a thing yet, but I believe scientific contributions have no boundaries. I have a long-term goal to persuade the organizers of the VLDB conference to host at least one conference in Nigeria; perhaps this would make Nigerians see themselves as part of the broader database research community.</p>

---

## Research Interests
- **Database Systems**
- **Big Data Analytics** 
- **Date Engineering**

---

## Education  
**Federal University of Technology Akure**  
**Degree:** B.Tech Computer Science (2017 - 2024)  
**Grade:** First Class Honors  
**GPA:** 4.54/5.00, 3.71/4.00 <i>(Class Rank 3 of 50 students)</i>  
**Relevant Coursework:**  
- Data Modelling and Management  
- Linear Algebra  
- Data Analysis  
- AI and Expert Systems
- Differential Calculus  
- Data Storage Networks

---

## Research Experience

### Independent Researcher
**Title:** VelarixDB, an LSM Storage Engine that reduces IO amplification <br/>
**Advisor:** Adewumi Sunkanmi (self)  
**Synopsis:** [Recognized](https://x.com/andy_pavlo/status/1820436583977275426) as the first database emerging from Nigeria by Professor Andy Pavlo from Carnegie Mellon University. VelarixDB is a key-value store that reduces IO amplification during compaction by separating keys from values inspired by the WiscKey Paper from the University of Wisconsin-Madison. It uses asynchronous IO based on the recent adoption of <i>io_uring</i> on Linux, which outperforms existing asynchronous mechanisms on Linux, such as Linux AIO and POSIX AIO ([benchmark](https://www.scylladb.com/2020/05/05/how-io_uring-and-ebpf-will-revolutionize-programming-in-linux/0/#:~:text=(enhanced)-,1%2C486%2C000,-11%2C483%2C468)). It is developed in Rust for memory safety. WiscKey benchmark shows 1.4 to 14 times faster random lookups and 2.5 to 111 times speedier database loading than RocksDB.

- Built experimental version in Rust with features such as Size-Tier Compaction, Garbage Collector, Crash Recovery, Bloom Filter, and Value Log.
- Leveraged a Lock-Free data structure (SkipMap) from the Crossbeam library for the Memtable, eliminating traditional locking mechanisms like Mutexes and reducing thread contention <br/>
- Reduced IO amplification based on the WiscKey model and then improved file IO throughput by adopting async IO with io_uring <br/>
 [Official Documentation](https://crates.io/crates/velarixdb) | [Code](https://github.com/Gifted-s/velarixdb) | [WiscKey Paper](https://www.usenix.org/system/files/conference/fast16/fast16-papers-lu.pdf)


### Undergraduate Thesis (Jun 2023 - Dec 2023)
**Title:** Design and Implementation of a Road Safety Database in Nigeria  
**Advisor:** Professor O.C Akinyokun  [Google Scholar Profile](https://scholar.google.com/citations?user=4l_GGDQAAAAJ&hl=en) <br/>
**Synopsis:** A relational database that integrates verified datasets from major institutions involved in road safety in Nigeria, such as the Federal Road Safety Corps (FRSC), the World Health Organization (WHO), and the National Bureau of Statistics (NBS), to help research groups generate and publish accurate statistics.

- Leveraged ETL (Extract, Transform, Load) mechanism to consolidate road safety data from various agencies, enabling comprehensive and more accurate data analytics for research groups and policymakers.
- Modelled all entities (32) using Entity Relationship Diagram to showcase all entities and the relationships between them  
- Implemented indexing by location to optimize the performance of queries related to geographical data   
- Wrote SQL queries to generate 10 statistics on road accidents presented during the final year project defense

---

## Conference Talk
- **SysConf 2023:** "Demystifying Data Structures Behind Database Storage Engines"  
  _Audience: 200+ ([Virtual](https://www.youtube.com/@sysdsgn))_

---

## Professional Experience

### **Acronis (Senior Software Engineer), Jan 2023 - Jan 2024**  
- Built a data pipeline that periodically collects and computes 45 metrics and sends it to the data warehouse for analysis, used by product managers to determine aspects of the product to improve.
- Ensured a newly developed service, Advanced Automation, aligned with customer needs by coordinating meetings with the Acronis Customer Experience (ACEP) team
- Resolved 50+ bugs using Kubernetes pod logs, Kibana logs, Grafana and collaborating with the QA team, 

---

### **Droppofy (Software Engineer), Feb 2022 - Jan 2023**
- Reduced latency of fetching users' analytics data by 52% by caching on Redis to prevent redundant database calls  
- Designed, implemented, and documented over 70% of the API endpoints with NodeJS and MongoDB

---

### **RemoteAfrica (Software Engineer Intern), Sep 2020 - Dec 2020**
- Convinced a team of 11 to adopt effective MongoDB schema design patterns, leading to a 40% increase in query speed.
- Mentored a junior intern through pair programming sessions, enhancing their confidence and promoting teamwork.


---


## Teaching Experience

### Academic Unit Tutor, Christian Student Fellowship (CSF), Federal University of Technology Akure  
- **CSC 201: Python Programming**  
  - ***Topics:*** Object Oriented Programming, Control Flows, Function, Data Types. Variables, Modularization, Comments  
  - ***Duties:*** Taught theoretical and practical classes, prepared assignments and test questions, evaluated students’ performance

- **CSC 305: Systems Programming in C**  
  - ***Topics:*** Socket programming, Control Flows, Data Types, Functions, Variable, Modularization, Library usage 
  - ***Duties:*** Taught theoretical and practical classes, prepared assignments and test questions, evaluated students’ performance

- **PHY 101, General Physics**  
  - ***Topics:*** Scalar and Vector Quantities, Kinematics, Projectile, Work, Power, Energy, Electricity, Equilibrium,  Gravitation 
  - ***Duties:*** Taught theoretical classes, prepared assignments and test questions, evaluated students’ performance

---

## Awards & Scholarships
- **Ekiti State Scholarship Award:**  Awarded by the Ekiti State Government for being on the Dean's list by 2nd year at the Federal University of Technology Akure. A sum of ₦60,000 is awarded every session from the second year to the final year [Read More](https://www.ekitistate.gov.ng/archives/18923) <br/>
- **Dean's List:** Placement on the [Dean's List](https://drive.google.com/file/d/1UMrIP8XLigWOWi6GEfqPjcHKgoBPXqkT/view) for the 2018/2019 academic session by the Senate of the Federal University of Technology Akure after achieving a 4.72 GPA in the 2017/2018 academic session. <br/>
- **Awards of Community Service:** [View All](https://drive.google.com/file/d/1iBsmMJ4lMY2i0KX25FiokFZeIu6v0eCB/view?usp=sharing)
  
---

## Leadership

### **Academic Coordinator, Christian Student Fellowship (CSF), Jun 2023 - Mar 2024**
- Appointed and chaired 20 committee members to oversee an academic conference to enlighten students on scholarships, grants, and strategies for achieving academic excellence.
- Oversaw the planning of timetables, conduction of pre-tests and pre-exams, and onboarding process for new tutors 

### **Technical Lead, EFina Hackathon Oct 2020 - Nov 2020**
- Directed a team of 3 while building a savings and financial advisory platform, _Coin Planner_, which enables individuals and MSMEs to manage their spending by helping them save from periodic earnings. The team won a sum of [₦1.5 Million](https://efina.org.ng/publication/team-inclusion-wins-efinas-fintech4wd-hackathon/#:~:text=with%20Adebayo%20Olorunfemi%2C-,Adewumi%20Sunkanmi%2C,-and%20Aanuoluwa%20Babalola)
  
---

## Volunteer Experience

### Social Media Manager, IA Foundation [Website](https://ia-foundation.org/) 
**Jun 2024 - Pres**  
- Helped raise awareness of Nigeria’s 18.3 million out-of-school children through engaging content.

---

## Skillset
- **Technical Leadership**, **Technical Writing**, **Teaching**
- **Data Modelling**,**SQL**, **Rust**, **Golang**, **Node.js**, **Postgres**, **MongoDB**
- **Kubernetes**, **RabbitMQ**, **Redis**, **Jenkins**, **Git**, **Grafana**, **Kibana**

---

## Extra Curricular Activities
- **Pianist:** Jazz genre, Watch me play! [♫!](https://drive.google.com/file/d/1Oc-XcdZHvhnOCG9Xm4bv6m47AHfW7a_u/view?usp=sharing)
- **Men’s Gymnastics (Ekiti State Team):** Floor, Parallel Bars, and Vault Exercise  [Ekiti State Blog](https://www.ekitistate.gov.ng/archives/6116)

