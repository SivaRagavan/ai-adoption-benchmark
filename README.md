# AI Adoption Benchmark

A Bun + React app to assess a single company’s AI adoption journey using a modular, editable benchmark. The flow starts with guided questions to select relevant modules, then scores metrics on a five-point scale with notes.

## Features

- Guided questions to select applicable pillars and metrics
- Slider-based scoring with labeled anchors and notes per metric
- Composite score, pillar scores, and maturity band
- Benchmark editor for pillars, metrics, weights, and slider labels
- Basic results visualization (bar chart)

## Local Development

```bash
bun install
bun dev
```

The app runs on `0.0.0.0:5173` and allows `http://alien:5173` as a host.

## Project Structure

- `src/routes` — Home, Questions, Assessment, Results, Benchmark Editor
- `src/data` — Benchmark schema and guided questions
- `src/state` — Benchmark and assessment state stores
- `src/utils` — Scoring utilities
- `src/components/ui` — shadcn/ui components
