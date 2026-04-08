# Universal Web Search

## Instructions

You MUST use this skill whenever the user asks for current events, real-time information, or facts that require searching the broader internet beyond Wikipedia.

### Step 1: Execute Search
Call the `run_js` tool with `search.html` as the script name.
The JSON payload MUST include:
- **query**: String, Required. The search query to find the information.
- **search_depth**: String, Optional. Set to "advanced" for deeper research or "basic". Default is "basic".

### Invocation Triggers
You should invoke this skill when the user:
- Asks "What happened today in..."
- Asks for current stock prices or news.
- Needs information not found in your internal training data.

Output ONLY the final result which should be a comprehensive summary of the search results in Thai.
