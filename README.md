# AI Travel Planner

## Overview
A multi-agent system for comprehensive travel planning powered by OpenAI's GPT models.

## Architecture
- **Manager Agent**: Orchestrates the planning process by delegating to specialized agents
- **Specialized Agents**:
  - Destination Research Agent: Gathers location information and highlights
  - Travel Ticket Search Agent: Finds optimal transportation
  - Weather Forecast Agent: Analyzes ideal travel seasons
  - Local Route Travel Agent: Optimizes travel between attractions
  - Budget Planner Agent: Estimates trip costs
  - Final Itinerary Generator: Compiles information into a structured plan

## Features
- Multi-location optimization
- Real-time pricing data
- Budget awareness
- Flexible transportation options
- Weather-optimized scheduling

## Requirements
- Python 3.9+
- OpenAI API key
- Google Maps API key
- SerpAPI key (for Google Search)
