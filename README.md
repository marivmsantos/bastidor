# bastidor
Bastidor (Portuguese for “backstage”): the assistant runs the backstage, the owner stays on stage with the client.

> An assistant that runs the admin side of WhatsApp for service micro-businesses, so the owner can stay focused on the client in front of them.

🌱 **Status:** early stage, problem definition and first prototype. Built with [Claude Code](https://claude.com/product/claude-code).

---

## The problem

Nail technicians, hairdressers and contractors run their whole business through WhatsApp: scheduling, answering the same questions, sending prices. That work happens in the middle of a service, late at night, or not at all, and clients slip through the cracks.

## Who it's for

Service micro-businesses in Brazil, starting with beauty (nail and hair salons) and home services (contractors).

## Design principles

1. **Not a chatbot that replaces the owner.** The client relationship stays personal. The assistant organizes the day and takes the bureaucratic part off the conversation.
2. **One standard product, not custom setups.** Every customer gets the same product. Per-customer configuration is what makes "do it yourself" assistants hard to maintain.
3. **Simple and affordable.** It has to make sense for someone billing per appointment.

## Scope (draft, to be validated)

- [ ] _To define: first use case (e.g. scheduling, price list, reminders)_
- [ ] _To define: what the assistant does on its own vs. what it hands back to the owner_
- [ ] _To define: technical approach to WhatsApp integration_

## Roadmap

- [ ] Interview 5 micro-business owners about their WhatsApp routine
- [ ] Define the first use case
- [ ] Build a prototype
- [ ] Test with 1–2 real businesses

## Decision log

| Date | Decision | Why |
|---|---|---|
| 2026-10 | Standard product, no per-client customization | Maintenance cost is what breaks DIY assistants |

## About

Built by [Mariana](PROFILE-URL), an operations builder who automates customer operations with AI.
