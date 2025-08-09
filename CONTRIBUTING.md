## Summary
Replaced the OpenAI GPT-4o model calls with the Phi model using Ollama for local inference.

## Changes Made
- Updated model reference in [file_name.py] from `gpt-4o` to `phi`.
- Added Ollama client integration for running Phi locally.
- Updated README.md with setup instructions for Ollama and Phi.
- Adjusted API call parameters to match Phi’s input/output format.

## Motivation
- Phi is lightweight and runs locally via Ollama, reducing reliance on cloud APIs.
- Useful for offline development and lower latency.

## Impact
- Requires Ollama to be installed locally.
- Phi must be pulled with `ollama pull phi` before running.
- Some responses may differ slightly from GPT-4o.

## Testing
- Verified that all example scripts run successfully with Phi.
- Output correctness checked for [list of test cases].
