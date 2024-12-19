# Matcopvili

<p align="left">
  <br />
  <a href="https://docs.copilotkit.ai/coagents" rel="dofollow"><strong>Explore the docs »</strong></a>
  <br />
 


## Prerequisites

Before you begin, ensure the following is installed:

- [pnpm](https://pnpm.io/installation)
- [Langgraph CLI](https://langchain-ai.github.io/langgraph/cloud/reference/cli/) (requires Docker to be installed and running)

---

## 🚀 Getting Started

## 👨‍💻 Running the UI

First, navigate to the frontend and install the dependencies:

   ```bash
   cd ./frontend
   pnpm install
   ```

 **Start the application**:

  - To use the **local version** of the agent:

     ```bash
     pnpm run dev
     ```

  - To use the **remote version** of the agent:

     ```bash
     pnpm run remote-lgc-dev
     ```

---

## 💻 Running the Agent Locally

**Navigate to the agent directory**:

   ```bash
   cd agent
   ```

**Start the Agent**:

   ```bash
   langgraph up
   ```

