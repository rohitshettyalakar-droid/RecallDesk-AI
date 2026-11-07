# RecallDesk — Customer Support Memory Prototype

A self-contained browser prototype demonstrating a customer-support workspace with two separate sample customer profiles, saved context cards, returning-customer responses, and local demo persistence.

## Run
Open `index.html` in Chrome, Edge, or Firefox. No build tools or server are required.

## Demo
1. Select Maya Chen and ask: “I'm still seeing the duplicate subscription charge.”
2. Ask: “What do you remember about my billing issue?”
3. Switch to Arjun Kumar and ask about the previous delivery issue.
4. Notice that each profile has separate demo memory.

## Honest implementation status
This is a frontend prototype. It uses browser `localStorage` and scripted demo responses. It does **not** currently call Hindsight, a language model, or a production backend. Do not claim that live Hindsight retain/recall has been implemented. To meet a requirement for Hindsight integration, connect a secure server-side Hindsight client, demonstrate real retain and recall calls, and capture genuine test evidence.

No real customer information should be entered. This prototype is for demonstration only.
