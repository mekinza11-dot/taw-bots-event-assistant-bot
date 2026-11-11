
# Event Assistant Bot - Testing Checklist

## Functional Testing

| Test Case | Expected Result | Status |
|---|---|---|
| Ask for event agenda | Displays agenda and timings | Passed |
| Ask about speakers | Displays speaker names and topics | Passed |
| Ask about venue | Displays event location | Passed |
| Ask about event date and time | Displays correct details | Passed |
| Ask about session timings | Displays session schedule | Passed |
| Ask an unknown question | Says information is unavailable | Passed |
| Ask a follow-up question | Answers using conversation context | Passed |
| Open public chat URL | Chatbot loads and responds | Passed |

## Technical Testing


- [x] Invalid or unclear input handling
- [x] Unrelated questions are politely rejected
- [ ] Gemini API failure handling
- [ ] Workflow execution error handling
- [ ] Retry behavior
## Tools Used

- n8n
- Google Gemini
- n8n Chat Trigger
- AI Agent
- Simple Memory
