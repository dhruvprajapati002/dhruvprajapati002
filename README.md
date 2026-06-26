<div align="center">

<!-- Animated Header Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,20:0d0221,50:1a0533,80:2d1b69,100:0f0c29&height=250&section=header&text=Dhruv%20Prajapati&fontSize=72&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=⚡%20Architect%20%7C%20Full%20Stack%20Engineer%20%7C%20System%20Designer%20⚡&descAlignY=60&descSize=20&descColor=c4b5fd"/>

<!-- Animated Typing SVG -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=800&size=24&duration=2500&pause=700&color=C084FC&center=true&vCenter=true&multiline=false&width=750&lines=🏗️+System+Architect+%26+Design+Patterns;🚀+Full+Stack+Engineer+(React+%7C+Next.js+%7C+Node);🔬+Distributed+Systems+%26+Microservices;⚙️+High-Availability+%26+Fault-Tolerant+Systems;🧠+CAP+Theorem+%7C+CQRS+%7C+Event+Sourcing;☁️+Cloud+Native+%7C+AWS+%7C+Kubernetes;⚡+1M%2B+RPS+Architecture+Design;🛡️+Clean+Code+%7C+SOLID+%7C+DDD+Advocate;🔥+Always+Shipping.+Always+Scaling." alt="Typing SVG" />
</a>

<br/>

<!-- Shields Row -->
<p>
  <img src="https://komarev.com/ghpvc/?username=dhruvprajapati002&style=for-the-badge&color=7c3aed&label=👁️+PROFILE+VIEWS" alt="profile views"/>
  &nbsp;
  <img src="https://img.shields.io/github/followers/dhruvprajapati002?style=for-the-badge&color=7c3aed&label=🤝+FOLLOWERS" alt="followers"/>
  &nbsp;
  <img src="https://img.shields.io/badge/🔥_Open_To_Work-YES-22c55e?style=for-the-badge" alt="open to work"/>
  &nbsp;
  <img src="https://img.shields.io/badge/🏗️_System_Design-OBSESSED-a855f7?style=for-the-badge" alt="system design"/>
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

</div>

---

## 🧑‍💻 Who Am I?

```typescript
interface Engineer {
  identity    : string;
  roles       : string[];
  location    : string;
  superpower  : string;
}

const dhruv: Engineer & SystemArchitect = {
  identity    : "Dhruv Prajapati",
  roles       : ["System Architect", "Full Stack Engineer", "Distributed Systems Nerd"],
  location    : "Gujarat, India 🇮🇳",
  superpower  : "Turning complex problems into elegant, scalable systems 🧠",

  // What I'm obsessing over
  currentlyDesigning  : "Event-driven microservices with Kafka + CQRS",
  currentlyLearning   : ["Kubernetes Operators", "eBPF", "Consensus Algorithms", "ML Systems Design"],
  lookingToCollabOn   : "Open Source Infra Tools & High-Scale SaaS 🤝",

  // The philosophy
  designPrinciples    : ["SOLID", "DDD", "Clean Architecture", "12-Factor App"],
  scalePhilosophy     : "Design for 10x, build for today, optimize with data 📊",
  funFact             : "I draw system diagrams before writing a single line of code 📐",
  motto               : "Clarity of thought → clarity of architecture → clarity of code 💡",

  stack: {
    frontend        : ["React", "Next.js", "TypeScript", "Tailwind CSS", "Vue.js"],
    backend         : ["Node.js", "Express", "Python", "Django", "FastAPI", "GraphQL"],
    systemDesign    : ["Microservices", "Event Sourcing", "CQRS", "Saga Pattern", "Hexagonal Architecture"],
    messageBrokers  : ["Apache Kafka", "RabbitMQ", "Redis Pub/Sub"],
    databases       : ["PostgreSQL", "MongoDB", "Redis", "Cassandra", "Elasticsearch"],
    infra           : ["Docker", "Kubernetes", "AWS", "Terraform", "GitHub Actions", "Nginx"],
    observability   : ["Prometheus", "Grafana", "OpenTelemetry", "ELK Stack"],
  }
};
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

---

## 🏗️ System Design & Architecture

> *"A great system is invisible. A bad one is unforgettable."*

<div align="center">

### 🧩 Architectural Patterns I Live By

| Pattern | When I Use It | Why It Matters |
|:-------:|:-------------:|:--------------:|
| 🔄 **Event Sourcing** | Audit trails, financial systems | Never lose state history |
| ⚡ **CQRS** | Read-heavy systems, complex domains | Separate read/write concerns |
| 🌐 **Microservices** | Large teams, independent deployability | Scale what matters |
| 🔺 **Saga Pattern** | Distributed transactions | No 2PC in the wild |
| 🧅 **Hexagonal (Ports & Adapters)** | Domain-heavy apps | Infra is a plugin |
| 📨 **Pub/Sub** | Decoupled event-driven systems | Loose coupling, high cohesion |
| 🔒 **Circuit Breaker** | External service calls | Prevent cascading failures |
| 💾 **CQRS + Read Replicas** | Scale reads 100x | Reads ≠ writes |

</div>

### 📐 How I Approach System Design

```
STEP 1 — CLARIFY REQUIREMENTS
├── Functional: What does it do?
├── Non-Functional: Scale? Latency? Availability? Consistency?
└── Constraints: Budget, team size, timeline

STEP 2 — ESTIMATE SCALE
├── Daily Active Users → QPS → Storage → Bandwidth
├── Read/Write ratio → Database choice
└── Hotspots? Thundering herd? Cache everything?

STEP 3 — HIGH-LEVEL DESIGN
├── API Design (REST / GraphQL / gRPC)
├── Data Flow: Client → LB → Service → DB
└── Identify bottlenecks early

STEP 4 — DEEP DIVE
├── Database schema & indexing strategy
├── Caching layers (L1: in-memory, L2: Redis, L3: CDN)
├── Message queues for async decoupling
└── Sharding, partitioning, replication

STEP 5 — RELIABILITY & RESILIENCE
├── Circuit Breakers, Retries with Exponential Backoff
├── Rate Limiting (Token Bucket / Leaky Bucket)
├── Health checks, graceful degradation
└── Observability: Metrics, Logs, Traces (The Golden Triangle)
```

### 🔥 Systems I've Designed / Can Design

<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║  URL Shortener (Bitly)  │  Chat System (WhatsApp scale)         ║
║  Rate Limiter           │  Notification Service                  ║
║  Search Autocomplete    │  Distributed Cache (Redis Clone)       ║
║  News Feed (Instagram)  │  Payment Processing System             ║
║  Video Streaming (YT)   │  Ride-Sharing Backend (Uber)          ║
╚══════════════════════════════════════════════════════════════════╝
```

</div>

### 🧠 Key System Design Concepts I Obsess Over

```yaml
Consistency Models:
  - Strong Consistency  → Single-leader replication, 2PC
  - Eventual Consistency → DNS, shopping carts, social media
  - Causal Consistency   → Vector clocks, distributed logs

Database Selection Matrix:
  Relational (PostgreSQL)   → ACID, complex joins, financial data
  Document (MongoDB)        → Flexible schema, hierarchical data
  Key-Value (Redis)         → Sub-ms reads, sessions, caching
  Wide-Column (Cassandra)   → Time-series, write-heavy, massive scale
  Search (Elasticsearch)    → Full-text search, analytics

CAP Theorem Trade-offs:
  CP (consistent + partition tolerant) → HBase, Zookeeper
  AP (available  + partition tolerant) → Cassandra, CouchDB
  CA (consistent + available)          → Single-node RDBMS

Scaling Strategies:
  Vertical   → Bigger machines (limited ceiling)
  Horizontal → More machines (preferred, needs stateless design)
  Caching    → Redis, Memcached, CDN (kill the DB at scale)
  Sharding   → Horizontal partitioning by key range or hash
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

---

## 🚀 Full Tech Arsenal

<div align="center">

### 🎨 Frontend
<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,html,css,tailwind,redux,vue&perline=9" />
</p>

### ⚙️ Backend & APIs
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,python,django,fastapi,graphql&perline=9" />
</p>

### 🏗️ Architecture & Infra
<p>
  <img src="https://skillicons.dev/icons?i=kafka,docker,kubernetes,aws,terraform,nginx,linux&perline=9" />
</p>

### 🗄️ Databases & Caching
<p>
  <img src="https://skillicons.dev/icons?i=mongodb,postgres,mysql,redis,firebase,cassandra,elasticsearch&perline=9" />
</p>

### 🔭 Observability & DevOps
<p>
  <img src="https://skillicons.dev/icons?i=prometheus,grafana,githubactions,vercel,netlify&perline=9" />
</p>

### 🛠️ Tools
<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman,figma&perline=9" />
</p>

</div>

<details>
<summary>📋 <b>View All Tech Badges</b></summary>
<br/>

**Frontend:**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=flat-square&logo=vuedotjs&logoColor=4FC08D)
![Redux](https://img.shields.io/badge/Redux-593D88?style=flat-square&logo=redux&logoColor=white)

**Backend:**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)

**Architecture & Messaging:**
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=google&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-Architecture-7c3aed?style=flat-square)
![Event Sourcing](https://img.shields.io/badge/Event_Sourcing-CQRS-a855f7?style=flat-square)

**Databases:**
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=flat-square&logo=redis&logoColor=white)
![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=flat-square&logo=apachecassandra&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**DevOps & Cloud:**
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326ce5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

</details>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

---

## 📊 GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=dhruvprajapati002&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=ffffff&count_private=true&rank_icon=github"/>
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=dhruvprajapati002&theme=tokyonight&hide_border=true&background=0d1117&ring=a78bfa&fire=ff6b6b&currStreakLabel=a78bfa&sideLabels=ffffff"/>

<br/>

<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dhruvprajapati002&layout=donut&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=ffffff&langs_count=8"/>
<img width="49%" src="https://github-readme-activity-graph.vercel.app/graph?username=dhruvprajapati002&bg_color=0d1117&color=a78bfa&line=7c3aed&point=ff6b6b&area=true&hide_border=true&area_color=302b63"/>

</div>

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=dhruvprajapati002&theme=tokyonight&no-frame=true&row=1&column=7&margin-w=8&margin-h=8"/>
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

---

## 💡 What I'm Up To

<table>
<tr>
<td>

- 🏗️ Designing **event-driven microservices architectures**
- 🔬 Deep-diving into **Distributed Systems & Consensus Algorithms**
- ☸️ Learning **Kubernetes Operators & Service Mesh (Istio)**
- 🧪 Exploring **eBPF, WASM, and edge computing**
- 📐 Drawing system diagrams before every project (it's a ritual)
- 📫 Reach me: **dhruvprajapati0023@gmail.com**
- 🌐 Portfolio: **[Visit Here](https://dhruv-portfolio-23.vercel.app/)**
- ⚡ Motto: **Design → Build → Ship → Scale → Repeat ☕**

</td>
<td>

```text
📐 System Design   ████████████  10/10 obsession
🌅 Morning         ████████░░░░  architecture planning
🌞 Afternoon       ████████████  deep implementation
🌙 Night           ████████░░░░  debugging & shipping
🌃 Late Night      ███████░░░░░  reading papers & RFCs
```

</td>
</tr>
</table>

---

## 🧠 Architecture Mindset

<div align="center">

```
                    ┌─────────────────────────────────────┐
                    │        THE DHRUV STACK™              │
                    └─────────────────────────────────────┘

  CLIENT                    GATEWAY                  SERVICES
  ┌──────┐    HTTPS     ┌──────────┐   gRPC/REST  ┌──────────────┐
  │React │ ──────────► │  Nginx   │ ────────────► │ User Service │
  │Next.js│            │  + LB    │               │ (Node.js)    │
  └──────┘             └──────────┘               └──────────────┘
                             │                           │
                        Rate Limit                  ┌────▼────────┐
                        Auth (JWT)                  │   Kafka     │
                             │                      │  (Events)   │
                    ┌────────▼───────┐              └────┬────────┘
                    │  API Gateway   │                   │
                    │  (GraphQL)     │         ┌─────────▼──────────┐
                    └────────────────┘         │  Order Service     │
                                               │  (Python/FastAPI)  │
  DATABASES              CACHE                 └──────────┬─────────┘
  ┌──────────┐      ┌──────────┐                         │
  │PostgreSQL│      │  Redis   │◄────── Read-Through ────┘
  │(Primary) │      │Cluster   │
  └────┬─────┘      └──────────┘     OBSERVABILITY
       │                             ┌─────────────────┐
  ┌────▼─────┐                       │ Prometheus       │
  │Read      │                       │ Grafana          │
  │Replicas  │                       │ OpenTelemetry    │
  └──────────┘                       │ ELK Stack        │
                                     └─────────────────┘
```

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

---

## 📚 System Design Resources I Swear By

<div align="center">

| 📖 Resource | 🔥 Why It's Gold |
|:-----------:|:----------------:|
| **Designing Data-Intensive Applications** (Kleppmann) | The bible of distributed systems |
| **System Design Interview** (Alex Xu Vol 1 & 2) | Real interview frameworks |
| **Building Microservices** (Sam Newman) | Service decomposition mastery |
| **Clean Architecture** (Uncle Bob) | Software structure done right |
| **The Art of Scalability** | Scaling at every dimension |

</div>

---

## 🌐 Connect With Me

<div align="center">

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-Visit_Now-7c3aed?style=for-the-badge&logoColor=white)](https://dhruv-portfolio-23.vercel.app/)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dhruv-prajapati-204549278/)
&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhruvprajapati0023@gmail.com)

<br/>

> *"Talk to me about system design, distributed systems, or why Postgres is secretly the best NoSQL database."* 😄

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

---

## 🐍 Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dhruvprajapati002/dhruvprajapati002/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dhruvprajapati002/dhruvprajapati002/output/github-contribution-grid-snake.svg"/>
    <img alt="snake animation" src="https://raw.githubusercontent.com/dhruvprajapati002/dhruvprajapati002/output/github-contribution-grid-snake.svg"/>
  </picture>
</div>

> ⚠️ **To enable the snake**, add `.github/workflows/snake.yml` → [Setup Guide](https://github.com/Platane/snk)

---

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" width="90%"/>

<br/><br/>

```
"First, solve the problem. Then, design the system. Then, write the code."
                                                        — Dhruv Prajapati
```

**💜 Thanks for visiting! If something here resonates, drop a ⭐ — it means everything.**

<!-- Footer Wave -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,30:1a0533,60:2d1b69,100:0a0a0a&height=150&section=footer&animation=fadeIn"/>

</div>
