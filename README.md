# README
#CopilGpt
**Notebook:** `agent-assist1.ipynb`  
**Generated:** 2025-11-18 20:56 UTC

## Structure

- Total cells: **16**  
- Markdown cells: **0**  
- Code cells: **16**

## Key imports

- `import os`
- `from kaggle_secrets import UserSecretsClient`
- `import nltk`
- `from nltk.tokenize import sent_tokenize`
- `from google.adk.tools import AgentTool, ToolContext, load_memory`
- `from google.adk.models.google_llm import Gemini`
- `from google.genai import types`
- `from google.adk.agents import Agent, SequentialAgent`
- `from google.adk.runners import InMemoryRunner`
- `from google.adk.tools import google_search`
- `from IPython.core.display import display, HTML`
- `from jupyter_server.serverapp import list_running_servers`

## Package installs (notebook runs)

- `!pip install google-adk nltk google-generativeai`

## Functions defined (examples)

- `def get_adk_proxy_url():`
- `def set_user_context(tool_context: ToolContext, role: str, focus_area: str):`
- `def offline_meeting_fallback(text: str):`
- `def offline_research_fallback(text: str):`

## Notebook outputs summary

- Output 1: stream — Requirement already satisfied: google-adk in /usr/local/lib/python3.11/dist-packages (1.18.0)
Requirement already satisfied: nltk in /usr/local/lib/python3.11/dist-packages (3.9.2)
Requirement already
- Output 2: stream — ✅ ADK components imported successfully.

- Output 3: stream — ✅ Gemini API key setup complete.

- Output 4: stream — ✅ Helper functions defined.

- Output 5: stream — ✅ Retry config and callbacks defined.

- Output 6: stream — ✅ Fallback tools defined.

- Output 7: stream — ✅ Model initialized.

- Output 8: stream — ✅ Meeting Agent defined.

- Output 9: stream — ✅ Research Pipeline defined.

- Output 10: stream — ✅ Root Agent defined.

- Output 11: stream — ✅ Root Agent defined.

- Output 12: stream — ✅ Runner created.

- Output 13: stream — 
 ### Created new session: debug_session_id

User > What is Agent Development Kit from Google? What languages is the SDK available in?
helpful_assistant > The Agent Development Kit (ADK) from Google i
- Output 14: display_data — ['text/plain', 'text/html']
- Output 15: stream — /usr/local/lib/python3.11/dist-packages/google/adk/cli/fast_api.py:130: UserWarning: [EXPERIMENTAL] InMemoryCredentialService: This feature is experimental and may change or be removed in future versi

## How to run

1. Install requirements (if any). Common command:

```
pip install -r requirements.txt
```

2. Open the notebook in JupyterLab / Colab and run cells in order.

## Notes & suggestions

- Review code cells that use file paths and update paths to match your environment.  
- If the notebook installs packages via `!pip`, ensure the environment is compatible.  
- If large datasets are referenced, download them to the expected paths before running.

---
