# Cosmiq

An AI authority that decides when data deserves human attention.

## Key Features

- Cosmiq does:

  - Decide whether streaming operational data should become an incident
  - Govern human attention using confidence + time windows
  - Produce decisions as events

- Cosmiq does NOT:

  - Fix systems
  - Execute infra actions
  - Replace monitoring tools
  - Be a chatbot

Repository Structure
cosmiq/
  - streaming/        # Confluent + Flink jobs
  - producer/         # Synthetic ops data generator
  - backend/          # API / WebSocket layer
  - ui/               # Next.js 16 app
  - docs/             # Architecture & diagrams
  - README.md
  
