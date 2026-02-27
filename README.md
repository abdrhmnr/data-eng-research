# Data Engineering Research Lab 🧪

A structured workspace for data engineering learning, research, and hands-on projects.
Built and maintained by **Abdrhmn** as part of a Master's research journey.

---

## Structure

data-engineer/
├── notes/                     # Conceptual notes
│   ├── data-drift/
│   ├── big-data-systems/
│   ├── streaming/
│   ├── databases/
│   └── machine-learning-ops/
├── research/                  # Master's thesis preparation
│   ├── papers/
│   │   └── summaries/
│   └── ideas/
├── environments/              # Environment setup
│   ├── python-venv/
│   └── docker/
├── data-infrastructure/       # Data infrastructure
│   ├── databases/
│   │   ├── postgres/
│   │   └── mongodb/
│   ├── ingestion/
│   └── storage/
├── pipelines/                 # Data pipelines
│   ├── batch/
│   ├── streaming/
│   └── orchestration/
├── projects/                  # Applied projects
│   ├── data-drift-monitoring/
│   ├── smart-agriculture-dss/
│   └── mini-projects/
├── experiments/               # Quick experiments
│   ├── testing-tools/
│   ├── benchmarks/
│   └── prototypes/
└── docs/                      # Documentation
    └── architecture-diagrams/

---

## Tech Stack

| Category        | Tools                              |
|-----------------|------------------------------------|
| Languages       | Python 3.11                        |
| Databases       | PostgreSQL, MongoDB                |
| Containerization| Docker, Docker Compose             |
| Orchestration   | Apache Airflow (planned)           |
| Streaming       | Apache Kafka (planned)             |
| ML Ops          | MLflow (planned)                   |

---

## Setup

### 1. Clone the Repository
git clone https://github.com/abdrhmnr/data-eng-research.git
cd data-eng-research

### 2. Create Python Virtual Environment
python3 -m venv dt-eng-research
source dt-eng-research/bin/activate
pip install -r requirements.txt

### 3. Start Docker Services
cd environments/docker
docker compose up -d

---

## Services

| Service       | URL                    | Description        |
|---------------|------------------------|--------------------|
| MongoDB       | localhost:27017        | NoSQL Database     |
| Mongo Express | http://localhost:8081  | MongoDB UI         |
| PostgreSQL    | localhost:5432         | Relational Database|

---

## Research Focus

- Data Drift Detection & Monitoring
- Smart Agriculture Decision Support Systems
- Real-time Data Pipelines
- Big Data Infrastructure

---

## Author

**Abdrhmn**
- GitHub: [@abdrhmnr](https://github.com/abdrhmnr)

---

## License

MIT License
