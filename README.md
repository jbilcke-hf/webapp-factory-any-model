---
title: Webapp Factory (any model)
emoji: 🏭
colorFrom: brown
colorTo: red
sdk: docker
pinned: false
app_port: 7860
---

A basic demo of generating HTML content using the Hugging Face Inference API

This version can use any model from the Hugging Face Inference API.

Ready to be used in a Hugging Face Space.

# Examples


```
http://localhost:7860/?prompt=A%20simple%20page%20to%20compute%20the%20BMI%20(use%20SI%20units)
```

# Installation
## Building and run without Docker

```bash
nvm use
npm i
npm run start
```

## Building and running with Docker

```bash
npm run docker
```

This script is a shortcut executing the following commands:

```bash
docker build -t webapp-factory-any-model .
docker run -it -p 7860:7860 webapp-factory-any-model
```
