<p align="center">
  <img src="assets/logo.svg" width="120" alt="Fitimio logo" />
</p>

<h1 align="center">Fitimio</h1>

<p align="center">
  <b>AI diet, nutrition, workout, and health tracker MCP server for ChatGPT and Claude.</b>
</p>

<p align="center">
  Give your AI assistant real meals, macros, workouts, goals, supplements, shopping lists, body metrics, and health context instead of making it guess.
</p>

<p align="center">
  <a href="https://fitimio.com"><img alt="Website" src="https://img.shields.io/badge/website-fitimio.com-d97706?style=for-the-badge"></a>
  <a href="https://fitimio.com/mcp"><img alt="MCP endpoint" src="https://img.shields.io/badge/MCP-remote_server-111827?style=for-the-badge"></a>
  <img alt="OAuth required" src="https://img.shields.io/badge/auth-OAuth_required-2563eb?style=for-the-badge">
  <img alt="Status" src="https://img.shields.io/badge/status-public_beta-16a34a?style=for-the-badge">
</p>

---

## Installation

Fitimio is a remote MCP server. You only need the server URL:

```text
https://fitimio.com/mcp
```

### ChatGPT

1. Open ChatGPT connector settings.
2. Add a custom MCP connector.
3. Paste the Fitimio server URL:

```text
https://fitimio.com/mcp
```

4. Sign in with OAuth when ChatGPT asks.
5. Ask: `Show me my dashboard.`

### Claude

1. Open Claude connectors.
2. Add a custom connector.
3. Paste the Fitimio server URL:

```text
https://fitimio.com/mcp
```

4. Sign in with OAuth when Claude asks.
5. Ask: `What did I eat today?`

### Custom MCP Clients

Use Fitimio as a remote MCP server:

```json
{
  "mcpServers": {
    "fitimio": {
      "url": "https://fitimio.com/mcp"
    }
  }
}
```

OAuth authentication is required.

## Introduction

Fitimio is a personal nutrition and fitness tracker built around the Model Context Protocol (MCP).

It connects your saved diet and health context to AI assistants like ChatGPT, Claude, and other MCP-compatible clients. Instead of asking generic nutrition questions, you can ask your assistant questions based on what you actually ate, what your goals are, what workout is planned, what supplements you take, and what restrictions or preferences you saved.

Fitimio is for people who already spend more time with AI assistants than with separate tracking apps.

## What You Can Ask

After connecting Fitimio, ask your AI assistant:

```text
What did I eat today?
```

```text
How much protein am I missing?
```

```text
Plan a dinner that keeps me under 1700 kcal today.
```

```text
Remember that I should not eat tomatoes.
```

```text
Show me my dashboard.
```

```text
How has my weight changed recently?
```

## Features

- Track daily calories, protein, carbs, fat, and other nutrition data
- Set daily and long-term goals
- Track workouts and planned training
- Save health notes, diet notes, restrictions, allergies, and preferences
- Track weight, body measurements, and progress
- Scan food barcodes and store nutrition data
- Create reusable meals and meal templates
- Track supplements and shopping lists
- Open interactive dashboard widgets inside ChatGPT or Claude

## Use Cases

### Daily Nutrition Check

Ask what you ate today and Fitimio can show calories, macros, meals, water, supplements, and progress toward your goals.

### Remaining Macros Planning

Ask for a dinner idea based on your remaining calories, protein target, preferences, and what you already logged.

### Barcode Food Lookup

Scan a barcode and ask whether the product fits your day. Fitimio can return calories, macros, sugar, fat, and other useful nutrition details.

### Workout and Progress Context

Track planned workouts, completed sessions, body weight, measurements, and trends so your assistant can answer from real history.

### Health-Aware Food Context

Save food restrictions, allergies, conditions, or diet notes so your assistant can avoid suggestions that do not match your context.

## Why Fitimio

Most tracking stacks are split across many apps:

- one app for calories
- one app for workouts
- one app for weight
- one app for notes
- one app for shopping lists

Fitimio keeps the context in one place and exposes it through MCP, so your AI assistant can help with practical questions:

- what changed
- what is missing
- what to eat next
- what to buy
- how your plan is going

## Example Workflow

1. Connect Fitimio to ChatGPT or Claude.
2. Log meals, scan foods, or import your day.
3. Ask: `What did I eat today?`
4. Ask: `What should I eat for dinner based on my remaining macros?`
5. Open the Fitimio dashboard directly inside the assistant.

## For MCP Clients

Server URL:

```text
https://fitimio.com/mcp
```

Authentication:

```text
OAuth 2.0
```

Supported client types:

- ChatGPT MCP connectors
- Claude MCP connectors
- custom MCP clients with remote server support

## Safety Note

Fitimio is not a medical device. It does not diagnose, treat, or replace a doctor, dietitian, or other healthcare professional.

Fitimio is a tracking and context tool. Use it to organize your own data and ask better questions, not as a substitute for medical advice.

## Keywords

AI diet tracker, nutrition MCP server, ChatGPT diet tracker, Claude nutrition tracker, MCP health tracker, AI workout tracker, macro tracking MCP, calorie tracking MCP, personal health context for AI assistants, barcode nutrition tracker, AI meal planner.
