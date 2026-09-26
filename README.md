# Ask HR: Voice Agent for Employee Questions

A voice agent built on ElevenLabs ElevenAgents that answers employee questions about benefits, PTO and pay for a sample company, and hands off to a person when it should.

**Status:** in progress

## Why this use case
Employee questions about pay, time off and benefits are one of the most common requests HR and finance teams handle. Most are answerable from policy and the system of record. The ones that aren't need a clean handoff to a person.

## What it does
- Answers policy questions from a knowledge base (benefits, PTO, pay schedule, expenses)
- Looks up an employee's own PTO balance after verifying their employee ID
- Escalates disputes, leave requests and sensitive topics to a person, with a written call summary

## Architecture
- **Agent:** ElevenLabs ElevenAgents
- **Knowledge base:** sample policy documents for a fictional company
- **Data:** Supabase tables for employees and escalation tickets
- **Tool call:** a verified PTO balance lookup
- **Front end:** web widget on a single page, deployed on Vercel

## Roadmap
- [ ] Knowledge base and agent prompt
- [ ] Employee verification and PTO lookup tool
- [ ] Escalation handoff with a ticket and summary
- [ ] Deploy the widget page
- [ ] Walkthrough video and lessons learned

## Notes
All company data here is fictional.
