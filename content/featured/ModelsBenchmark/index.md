---
date: '4'
title: 'Models Benchmark'
cover: './ModelsBenchmark.png'
# external: 'https://chess-tournament-tracker.bartoszwarchol.pl/'
tech:
  - C#
  - WinForms
  - Python
  - Flask
  - Scikit-learn
  - JSON
  - REST API
---

WinForms-based frontend application that allows users to select ML models and specify parameters for training and benchmarking. The available models and their parameter configurations are stored as a JSON file on the server, accessible via dedicated API endpoints. The backend, implemented in Python, handles model training and benchmarking, returning results such as accuracy through endpoint responses.
