# OpenFlightAgent

An open-source agentic service for finding the lowest priced flights based on user constraints. Built using open-source LLMs and frameworks.

## Features

- Search flights across multiple providers
- Filter by:
  - Departure and return dates
  - Origin and destination locations
  - Number of passengers (adults and infants)
  - Preferred currency
- Return optimized results based on price

## Architecture

The system uses a multi-agent architecture:
- Coordinator Agent: Handles user interaction and orchestrates the search process
- Search Agent: Interfaces with flight data sources
- Filter Agent: Optimizes and filters results based on constraints

## Technology Stack

- Python 3.9+
- Open Source LLMs (specify which ones you'll use)
- Flight data APIs (to be determined)

## Project Structure
