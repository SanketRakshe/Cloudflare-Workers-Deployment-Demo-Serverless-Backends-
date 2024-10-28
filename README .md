# Cloudflare Workers - Hello World Application

This project is a simple **serverless application** deployed on **Cloudflare Workers**. It responds with a JSON message: "Hello from Sanket!" when accessed.

## Overview

Cloudflare Workers is a serverless platform that enables developers to run JavaScript, Rust, C, and C++ code at the edge (in Cloudflare's data centers worldwide). This allows for high-performance, low-latency applications without the need for managing traditional servers. The main benefits of Cloudflare Workers include automatic scaling, quick global deployment, and the ability to handle complex tasks close to end-users, enhancing performance.

### Key Features
- **Serverless**: No need to manage or scale infrastructure; Cloudflare Workers automatically scale based on incoming traffic.
- **Global Reach**: Deploy code to data centers across the globe, enabling faster access from anywhere.
- **Performance**: Workers run on Cloudflare’s V8 engine, designed for ultra-fast performance.
- **Data Integration**: Workers can access Cloudflare KV storage for caching, D1 (managed SQLite) for databases, and Durable Objects for state management.

### Project Details
- **Application URL**: [my-app.sanketrakshe11.workers.dev](https://my-app.sanketrakshe11.workers.dev)
- **Main Functionality**: Returns a JSON message containing a welcome message.

## Getting Started

1. **Run Locally**:
   - Install dependencies.
   - Start a local development server with:
     ```bash
     npm run dev
     ```
   - Visit `http://localhost:8787` to see your Worker in action.

2. **Deploying to Cloudflare**:
   - Ensure you're logged into Cloudflare via `wrangler` CLI.
   - Deploy with:
     ```bash
     npm run deploy
     ```

## Cloudflare Workers Documentation

For more information, refer to the [Cloudflare Workers Documentation](https://developers.cloudflare.com/workers/).
