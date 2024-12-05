<p align="center">
    <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" align="center" width="30%">
</p>
<p align="center"><h1 align="center"><code>❯ Rsyslog Docker</code></h1></p>
<p align="center">
	<em><code>❯ lanakod-networking</code></em>
</p>
<p align="center">
	<!-- local repository, no metadata badges. --></p>
<p align="center">Built with the tools and technologies:</p>
<p align="center">
	<img src="https://img.shields.io/badge/Kibana-005571.svg?style=default&logo=Kibana&logoColor=white" alt="Kibana">
	<img src="https://img.shields.io/badge/Docker-2496ED.svg?style=default&logo=Docker&logoColor=white" alt="Docker">
</p>
<br>

##  Table of Contents

- [ Overview](#-overview)
- [ Features](#-features)
- [ Project Structure](#-project-structure)
  - [ Project Index](#-project-index)
- [ Getting Started](#-getting-started)
  - [ Prerequisites](#-prerequisites)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Testing](#-testing)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)

---

##  Overview

<code>❯ TODO</code>

---

##  Features

<code>❯ TODO</code>

---

##  Project Structure

```sh
└── /
    ├── docker-compose.yml
    ├── logs
    ├── logstash
    │   └── pipeline
    ├── README.md
    ├── rsyslog
    │   ├── conf
    │   ├── Dockerfile
    │   └── rsyslog.d
    └── rsyslog_kafka_elk.iml
```


###  Project Index
<details open>
	<summary><b><code>/</code></b></summary>
	<details> <!-- __root__ Submodule -->
		<summary><b>__root__</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='/docker-compose.yml'>docker-compose.yml</a></b></td>
				<td><code>❯ docker-compose file</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- logstash Submodule -->
		<summary><b>logstash</b></summary>
		<blockquote>
			<details>
				<summary><b>pipeline</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='/logstash/pipeline/logstash.conf'>logstash.conf</a></b></td>
						<td><code>❯ Logstash config file</code></td>
					</tr>
					</table>
				</blockquote>
			</details>
		</blockquote>
	</details>
	<details> <!-- rsyslog Submodule -->
		<summary><b>rsyslog</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='/rsyslog/Dockerfile'>Dockerfile</a></b></td>
				<td><code>❯ Rsyslog Dockerfile</code></td>
			</tr>
			</table>
			<details>
				<summary><b>conf</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='/rsyslog/conf/rsyslog.conf'>rsyslog.conf</a></b></td>
						<td><code>❯ rsyslog configuration file</code></td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>rsyslog.d</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='/rsyslog/rsyslog.d/01-json-template.conf'>01-json-template.conf</a></b></td>
						<td><code>❯ REPLACE-ME</code></td>
					</tr>
					<tr>
						<td><b><a href='/rsyslog/rsyslog.d/50-default.conf'>50-default.conf</a></b></td>
						<td><code>❯ REPLACE-ME</code></td>
					</tr>
					<tr>
						<td><b><a href='/rsyslog/rsyslog.d/60-output.conf'>60-output.conf</a></b></td>
						<td><code>❯ REPLACE-ME</code></td>
					</tr>
					</table>
				</blockquote>
			</details>
		</blockquote>
	</details>
</details>

---
##  Getting Started

###  Prerequisites

Before getting started with , ensure your runtime environment meets the following requirements:

- **Programming Language:** Error detecting primary_language: {'yml': 1, 'conf': 5}
- **Container Runtime:** Docker


###  Installation

Install  using one of the following methods:

**Build from source:**

1. Clone the  repository:
```sh
❯ git clone https://github.com/Lanakod-Networks/rsyslog_docker.git
```

2. Navigate to the project directory:
```sh
❯ cd rsyslog_docker
```

3. Install the project dependencies:


**Using `docker`** &nbsp; [<img align="center" src="https://img.shields.io/badge/Docker-2CA5E0.svg?style={badge_style}&logo=docker&logoColor=white" />](https://www.docker.com/)

```sh
❯ docker compose build
```




###  Usage
Run  using the following command:
**Using `docker`** &nbsp; [<img align="center" src="https://img.shields.io/badge/Docker-2CA5E0.svg?style={badge_style}&logo=docker&logoColor=white" />](https://www.docker.com/)

```sh
❯ docker compose up -d
```


###  Testing
Run the test suite using the following command:
echo 'INSERT-TEST-COMMAND-HERE'

---
##  Project Roadmap

- [X] **`Task 1`**: <strike>Implement feature one.</strike>
- [ ] **`Task 2`**: Implement feature two.
- [ ] **`Task 3`**: Implement feature three.

---