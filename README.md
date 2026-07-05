# AI Content Factory

A self-hosted AI-powered content automation platform built with Docker.

## Project Structure

This repository follows a modular architecture.

* **compose.yaml** – Docker services
* **data/** – Persistent application data
* **workflows/** – Exported n8n workflows (version controlled)
* **docs/** – Project documentation
* **scripts/** – Utility scripts
* **backups/** – Manual backup files

Every completed n8n workflow should be exported to the `workflows/` directory and committed to Git.
