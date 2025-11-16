# HSP-JSON Reflex Loop Demo (v0.1)

## JSON Core
- File: `core/HSP-JSON_Core_v0.1.json`
- Protocol: Hybrid Reflex Protocol
- Version: 1.0.0

## Roles
- R_Facilitator: Human (SchwarzeKatze)
- R_Lang: ChatGPT / Claude
- R_Theo: Gemini / Claude
- R_Ethic: Copilot
- R_Social: Grok

## Demo Task
Explain how Hybrid Reflex Protocol can reduce hallucinations
in multi-AI collaboration.

### Step 1 - ChatGPT (R_Lang)
- Load `HSP-JSON_Core_v0.1.json`
- Generate Draft_v1

### Step 2 - Gemini (R_Theo)
- Receive Draft_v1
- Validate logical consistency
- Return Issues_list

### Step 3 - ChatGPT (R_Lang)
- Revise Draft_v1 -> Draft_v2 using Issues_list

### Step 4 - Copilot (R_Ethic)
- Audit Draft_v2 for transparency & bias
- Compute Transparency Score (TS)

### Step 5 - Human (R_Facilitator)
- If TS >= 0.8 -> Approve Final_output
- Else -> return to Step 3
