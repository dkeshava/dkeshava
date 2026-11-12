# Hi there, I'm Dhondi Keshava 👋

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dhondi%20Keshava-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dhondi-keshava-34139322a)
[![GitHub](https://img.shields.io/badge/GitHub-dkeshava-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dkeshava)
[![Email](https://img.shields.io/badge/Email-dhondikeshava12k%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhondikeshava12k@gmail.com)
[![IIT Kharagpur](https://img.shields.io/badge/IIT%20Kharagpur-B.Tech%20'25-B31B1B?style=for-the-badge&logo=academia&logoColor=white)](https://www.iitkgp.ac.in)

**Manager – Data Engineering @ National Stock Exchange of India (NSE)**  
*Building mission-critical data platforms & architecting high-concurrency backend systems in Java & Go.*

```text
IIT Kharagpur '25  •  Enterprise Data Platforms  •  Backend Architecture (Java/Go)  •  Low-Level System Design
```

</div>

---

### 👨‍💻 About Me

I am an engineer with a passion for building robust, scalable backend systems and high-throughput data platforms. Currently, I serve as **Manager – Data Engineering at the National Stock Exchange of India (NSE)**, where I work on enterprise ETL modernization, distributed query engines, and mission-critical infrastructure handling high-volume financial data.

Alongside enterprise platform engineering, I have a deep technical focus on **Software Development & Backend Systems (SDE)**—crafting clean object-oriented architectures, low-level designs (LLD), concurrency primitives, and microservices in **Java (Spring Boot)** and **Go (Golang)**.

- 🏛️ **Alma Mater:** Graduated from **IIT Kharagpur (2025)** with a B.Tech in Instrumentation Engineering (CGPA: 8.17 / 10.0; Top 0.5% in JEE Main - AIR 5219).
- 🏢 **Current Impact:** Modernizing enterprise data infrastructure at **NSE** across Cloudera Hadoop (HDFS, Hive, Spark, Impala), Oracle 19c, Informatica DEI, and federated SQL engines (Starburst / Trino).
- 🛠️ **Systems & Backend Enthusiast:** Love digging into concurrency (`goroutines`, `sync.RWMutex`, Java threading), transactional consistency (pessimistic locking, ACID guarantees), and cache design.
- 🎯 **Target Roles:** Software Development Engineer (Backend / SDE), Systems Engineer, Forward Deployed Engineer (FDE), Data Platform Engineer.

---

### 🚀 Featured Engineering Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🃏 Poker Settlement Management System</h3>
      <p><em>Full-stack ledger & financial settlement platform with debt simplification.</em></p>
      <ul>
        <li><b>Architecture:</b> Layered LLD architecture built with <b>Java</b>, <b>Spring Boot</b>, <b>PostgreSQL</b>, and <b>React/TypeScript</b>.</li>
        <li><b>Algorithm:</b> Engineered a <b>recursive backtracking debt simplification algorithm</b> that minimizes the total cash transactions required to settle multi-party balances.</li>
        <li><b>Concurrency & ACID:</b> Enforced strict monetary accuracy using <code>BigDecimal</code> and database-level pessimistic write locking (<code>PESSIMISTIC_WRITE</code>) to prevent balance race conditions.</li>
        <li><b>Security & Testing:</b> Stateless JWT security filter chain, containerized with Docker, deployed on Render & Neon, covered by comprehensive JUnit 5 & Mockito test suites.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
        <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ Concurrent In-Memory Cache & Key-Value Store</h3>
      <p><em>High-throughput, thread-safe in-memory cache implemented in Go.</em></p>
      <ul>
        <li><b>Core Primitives:</b> Built from scratch in <b>Go (Golang)</b> featuring <b>O(1) LRU eviction</b> (doubly linked list + hash map) and TTL-based background key expiration.</li>
        <li><b>High-Throughput Concurrency:</b> Utilized <code>sync.RWMutex</code> to allow concurrent, non-blocking read operations with exclusive write safety, eliminating lock contention.</li>
        <li><b>Verification:</b> Validated race condition resilience using Go's race detector (<code>go test -race</code>) under heavy concurrent read/write loads.</li>
        <li><b>API Layer:</b> Exposed RESTful HTTP endpoints (<code>GET</code>, <code>SET</code>, <code>DELETE</code>, <code>/stats</code>) with custom metrics reporting.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
        <img src="https://img.shields.io/badge/Concurrency-sync.RWMutex-orange?style=flat-square" />
        <img src="https://img.shields.io/badge/LRU_Cache-O(1)-green?style=flat-square" />
        <img src="https://img.shields.io/badge/REST_API-net/http-blue?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    
    <td width="50%" valign="top">
      <h3>🏛️ Enterprise Data Infrastructure @ NSE</h3>
      <p><em>Mission-critical platform modernization at the National Stock Exchange of India.</em></p>
      <ul>
        <li><b>Platform Provisioning:</b> Multi-node enterprise infrastructure deployment across Development and Production bare-metal RHEL servers for Informatica DEI.</li>
        <li><b>Ecosystem Integration:</b> High-security enterprise network configuration across Cloudera CDP (Hadoop, Hive, Impala, Spark) and Oracle 19c.</li>
        <li><b>Data Integrity:</b> Automated complex SQL reconciliation workflows between relational and big data storage layers ensuring zero discrepancies.</li>
        <li><b>Federated SQL:</b> Technical evaluation of Starburst Enterprise Platform (Trino) for federated querying across heterogeneous data lakes.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
        <img src="https://img.shields.io/badge/Hadoop-FFD700?style=flat-square&logo=apachehadoop&logoColor=black" />
        <img src="https://img.shields.io/badge/Trino-Starburst-brightgreen?style=flat-square" />
        <img src="https://img.shields.io/badge/Oracle_19c-F80000?style=flat-square&logo=oracle&logoColor=white" />
        <img src="https://img.shields.io/badge/Linux_RHEL-EE0000?style=flat-square&logo=redhat&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

---

### 🛠️ Technical Stack & Tooling

<div align="center">

| Domain | Technologies |
| :--- | :--- |
| **Languages** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) |
| **Backend & Architecture** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white) ![REST APIs](https://img.shields.io/badge/RESTful_APIs-005571?style=flat-square) ![Microservices](https://img.shields.io/badge/Microservices-34495E?style=flat-square) ![Low Level Design](https://img.shields.io/badge/LLD_&_OOP-4A154B?style=flat-square) ![Goroutines](https://img.shields.io/badge/Goroutines_&_Channels-00ADD8?style=flat-square) |
| **Data & Cloud Platforms** | ![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![Hadoop](https://img.shields.io/badge/Hadoop_CDP-FFD700?style=flat-square&logo=apachehadoop&logoColor=black) ![Hive](https://img.shields.io/badge/Apache_Hive-FDEE21?style=flat-square&logo=apachehive&logoColor=black) ![Trino](https://img.shields.io/badge/Trino_/_Starburst-DD00A1?style=flat-square) ![Informatica](https://img.shields.io/badge/Informatica_DEI-FF4F00?style=flat-square) |
| **Databases & Storage** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![Oracle 19c](https://img.shields.io/badge/Oracle_19c-F80000?style=flat-square&logo=oracle&logoColor=white) ![Impala](https://img.shields.io/badge/Apache_Impala-268B99?style=flat-square) |
| **DevOps & Infrastructure** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Linux RHEL](https://img.shields.io/badge/Linux_RHEL-EE0000?style=flat-square&logo=redhat&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) |
| **Testing & Quality** | ![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white) ![Mockito](https://img.shields.io/badge/Mockito-brightgreen?style=flat-square) ![Go Test](https://img.shields.io/badge/Go_Race_Detector-00ADD8?style=flat-square) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) |

</div>

---

### 📈 GitHub Analytics & Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=dkeshava&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&title_color=7aa2f7&icon_color=bb9af7&text_color=c0caf5&bg_color=1a1b26" alt="Dhondi Keshava's GitHub Stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dkeshava&layout=compact&theme=tokyonight&hide_border=true&title_color=7aa2f7&text_color=c0caf5&bg_color=1a1b26" alt="Top Languages" height="165" />

<br/>

[![GitHub Streak](https://streak-stats.demolab.com/?user=dkeshava&theme=tokyonight&hide_border=true&border_radius=6&background=1a1b26&ring=7aa2f7&fire=e0af68&currStreakLabel=7aa2f7)](https://git.io/streak-stats)

</div>

---

### 🏆 Academic & Professional Milestones

- 🎓 **IIT Kharagpur (2025):** Graduated with **8.17 / 10.0 CGPA**; ranked in the **Top 9%** among 1,400+ students in first-year engineering.
- 🎯 **JEE Main:** Achieved **All India Rank 5219** (Top 0.5% nationwide among 10+ Lakh aspirants); Top 5% in JEE Advanced.
- 📈 **NSE Enterprise Impact:** Spearheaded platform migration and automated verification across 400+ ETL pipelines for mission-critical stock exchange operations.
- 💡 **Open Systems Development:** Actively exploring high-throughput concurrency models, transactional integrity, and distributed data systems.

---

### 📬 Get In Touch

Whether you want to discuss low-level system design, backend architectures, data infrastructure, or high-performance concurrent systems—feel free to reach out!

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dhondi-keshava-34139322a)
[![Email](https://img.shields.io/badge/Email-dhondikeshava12k%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhondikeshava12k@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow%20%40dkeshava-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dkeshava)

</div>
