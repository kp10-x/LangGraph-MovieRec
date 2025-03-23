# LangGraph Movie Recommendation System
A stateful LLM-powered movie recommendation system built with LangGraph.

## Overview
Demonstrates using LangGraph to create a graph-based recommendation system that maintains context across interactions.

### Usage
```python
# Set API key
os.environ["OPENAI_API_KEY"] = "your-key-here"
```
### Implementation

- Graph nodes: Extract preferences → Generate recommendations → Router
- State management: Tracks messages, preferences, and recommendations
- Data source: TMDB movie dataset

Built for MLOps tool exploration (11-685/17-445/17-645 Machine Learning in Production).
