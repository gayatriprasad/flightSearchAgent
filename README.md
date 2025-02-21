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

For Flight Data APIs, the top contenders are :

- Amadeus API - Has a free tier, comprehensive data
- Skyscanner API - Recently changed access model but still usable
- FlightLabs API - Good free tier, easier to integrate
- Duffel API - Modern API, good for actual bookings

For Open Source LLMs:

- Llama2 (7B or 13B) - Good overall performance, manageable size
- Mistral 7B - Excellent performance-to-size ratio
- ONNX optimized models for faster inference

Let's start with FlightLabs API for data (simpler to integrate) and Mistral 7B for our LLM.
