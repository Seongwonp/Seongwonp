<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,52:312E81,100:0F766E&height=230&section=header&text=Seongwon%20Park&fontSize=54&fontColor=F8FAFC&fontAlignY=38&desc=Backend%20Systems%20-%20Platform%20Engineering&descSize=17&descAlignY=58&animation=fadeIn" width="100%" alt="Seongwon Park — Backend Systems and Platform Engineering"/>

<br/>

[![ Portfolio](https://img.shields.io/badge/Portfolio-191F28?style=for-the-badge&logo=github&logoColor=white)](https://seongwonp.github.io/)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSI4IiByPSI0LjIiLz48cGF0aCBkPSJNMy41IDIxYTguNSA4LjUgMCAwIDEgMTcgMHoiLz48L3N2Zz4%3D)](https://www.linkedin.com/in/seongwon-park-10108035b/)
[![Tistory](https://img.shields.io/badge/TISTORY-000000?style=for-the-badge&logo=tistory&logoColor=white)](https://time-is-limit.tistory.com/)
[![Email](https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:swp20138993@gmail.com)

### I build backend systems, then stay around to see how they behave.

Spring Boot and FastAPI are my usual tools.<br/>
I enjoy the part after “it works”: deployment, load testing, failure analysis, and the next iteration.

<sub>만들고 끝내기보다, 직접 운영하고 측정하면서 다음 개선점을 찾습니다.</sub>

</div>

<br/>

## `01 / WHAT I BUILD`

<table>
<tr>
<td width="33%" valign="top">

### 🚗 Streaming systems

MQTT, Kafka, time-series storage, consumer design, and load tests that check the final stored result—not just queue health.

</td>
<td width="33%" valign="top">

### 📄 Deterministic pipelines

Parsers, layout engines, stable IDs, snapshot tests, and one-way data flows with explicit layer boundaries.

</td>
<td width="33%" valign="top">

### 🔐 Reliable web services

Authentication, payments, async workers, caching, monitoring, recovery paths, and security-conscious API design.

</td>
</tr>
</table>

## `02 / SELECTED WORK`

<table>
<tr>
<td width="50%" valign="top">

### [Telemetrix](https://github.com/Seongwonp/vehicle-telemetry-platform) · `Java`

Vehicle telemetry pipeline: MQTT → Kafka → InfluxDB/PostgreSQL, with anomaly consumers and a DLQ.

`Spring Boot` `Kafka` `fault injection`

**Reproduced a 72.1% message loss during a 90-second broker outage, then confirmed zero loss under the same conditions after the fix.**

<sub>Simulated data on a single host. Limits are documented in the repository.</sub>

</td>
<td width="50%" valign="top">

### [AI Exam Generator](https://seongwonp.github.io/AI-ExamGenerator/) · `Python`

PDF-to-exam service in a live pilot, registered under an academy's business license. I build and operate it solo, fix issues from real user feedback, and review logs weekly. [Visit service ↗](https://ai-examgenerator.co.kr/)

`FastAPI` `Redis/RQ workers` `PostgreSQL`

**Idempotent credit ledger and bounded retries keep failed jobs from double-charging or silently dropping questions.**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Touch Bridge](https://github.com/Seongwonp/touch_bridge) · `Flutter / FastAPI`

Voice-driven input assistance that presses touch-panel appliance buttons for blind users (Hanium Dream-Up).

`safety contracts` `fault injection` `BLE (ESP32)`

**Conference paper accepted at KIPS ACK 2026 (poster, first author).** In 8 fault-injection scenarios, commands sent after an emergency stop dropped from 7–20 lines to 0.

<sub>Measured at an app-side virtual transport layer; not yet verified on physical hardware.</sub>

</td>
<td width="50%" valign="top">

### [HoneyRest](https://github.com/Seongwonp/honeyRest_user) · `Java`

Lodging reservation platform split into user, host, and admin apps over one 30-table schema. [Live demo ↗](https://honeyrest.onrender.com)

`Spring Boot` `JPA` `Toss Payments`

**Team lead of three: built the 65-endpoint User API and React client, then hardened IDOR and privilege checks after the bootcamp.**

<sub>Free-tier hosting — the first load may take up to a minute.</sub>

</td>
</tr>
</table>

<details>
<summary><b>More things I have built</b></summary>

<br/>

- [AIDA](https://github.com/Seongwonp/AIDA) — label-error diagnosis research prototype for object detection; 29 error conditions, multi-seed reruns, and documented failed hypotheses
- [Han-Flow](https://github.com/Seongwonp/han-flow) — HWPX/HWP desktop viewer with PDF export and source-preserving limited editing
- [No-Click](https://github.com/Seongwonp/NoClick) — AI-assisted review analysis for promotional content and missing drawbacks
- [Smart Parking](https://github.com/Seongwonp/SmartParking_System) — JSP/Servlet team project I led (4 people, 89 PRs integrated)
- [C Data Structures](https://github.com/Seongwonp/C_Data_Structures) · [Linux C System Programming](https://github.com/Seongwonp/C_LinuxSysprog) — C foundations

</details>

## `03 / TOOLBOX`

<div align="center">

**Languages & backend**

![Java](https://img.shields.io/badge/Java_17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

<sub>C foundations: pointers and dynamic memory, data structures, and Linux system programming with processes, signals, sockets, pthreads, and IPC.</sub>

**Data & messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white)

**Build, ship & observe**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=191F28)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

</div>

## `04 / GITHUB IN MOTION`

<div align="center">

<img src="https://github-stats-extended.vercel.app/api?username=Seongwonp&show_icons=true&include_all_commits=true&theme=tokyonight&hide_border=true&rank_icon=percentile&custom_title=Builds%2C%20bugs%20%26%20iterations" height="180" alt="Seongwon's GitHub activity stats"/>
<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=Seongwonp&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&exclude_repo=honeyRest_host&size_weight=0.5&count_weight=0.5&custom_title=Languages%20across%20my%20repositories" height="180" alt="Languages across Seongwon's repositories"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Seongwonp&bg_color=0d1117&color=8b95a1&line=38bdf8&point=8b5cf6&area=true&area_color=38bdf8&hide_border=true&custom_title=Contribution%20timeline" width="96%" alt="Seongwon's GitHub contribution timeline"/>

</div>

<details>
<summary><sub>How the language card is calculated</sub></summary>

<sub>
<code>honeyRest_host</code> is excluded because it vendors about 11.4 MB of third-party JavaScript libraries under its static assets. The chart weights both code size and repository count; it shows repository composition, not a proficiency score.
</sub>

</details>

## `05 / RIGHT NOW`

```text
studying       Information Security @ University of Suwon
presenting     Touch Bridge safety contracts at KIPS ACK 2026 (Nov 2026)
competing      Embedded SW Contest finals — smart appliance track
next           closing the MQTT ack gap in Telemetrix, then Engineer Information Processing cert
```

<div align="center">

### Good systems are not just built. They are observed.

If you want to talk about backend systems, strange bugs, or an ambitious project:

[![Say hello](https://img.shields.io/badge/SAY_HELLO-8B5CF6?style=for-the-badge&logo=minutemailer&logoColor=white)](mailto:swp20138993@gmail.com)

</div>
