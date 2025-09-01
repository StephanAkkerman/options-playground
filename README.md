# Options Playground

An interactive playground for experimenting with option pricing parameters using the Black–Scholes model. Adjust values like strike price, expiration, interest rate, dividend yield, and volatility to see how they affect option prices, Greeks, and payoff diagrams.

## Live Demo

👉 [Try it here](https://akkerman.ai/options-playground/)

## Features

* Interactive charts (via Plotly):

  * Option price vs. spot (with multiple volatilities)
  * Time decay (price vs. days)
  * Delta vs. spot
  * Payoff at expiry
* Greeks panel (Δ, Γ, Vega, Θ, ρ)
* Put/Call toggle with put–call parity check
* Scenario table generator with live preview
* Dark mode toggle
* URL state sharing for easy link sharing

## Usage

Just open the [website](https://akkerman.ai/options-playground/) — no installation needed. Adjust parameters using sliders and inputs, and the charts & scenario table update instantly.

## Development

This project is a single static `index.html` page built with:

* Tailwind CSS (for styling)
* Plotly.js (for charts)
* Vanilla JavaScript (for Black–Scholes math & interactivity)

Deploy to GitHub Pages by placing `index.html` at the repo root and enabling Pages in your repository settings.
