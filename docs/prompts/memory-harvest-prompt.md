# Memory Harvest — End-of-Session Capture Prompt

> Paste this into your AI conversation when you're about to close a session.
> It primes the AI to walk you through a structured debrief so nothing important
> gets lost. Takes 2–5 minutes and compounds across sessions.

---

## PROMPT (copy everything below this line)

Before we close this session, I want to do a quick memory harvest — a structured
capture of what's worth keeping. Walk me through these five questions one at a
time. After I answer each, draft a capture for Cici using the `capture` MCP tool.
Label every capture with a durability class and at least one canonical tag.

---

**1. Decisions made**
What decisions did we reach in this session? For each one, what was the reason?
(Format: "Decided X because Y." — the reason is what I'll forget first.)
→ Durability: `persistent` | Tags: `#decision` + relevant domain tag

**2. Experiments — what worked, what didn't**
Did I try anything new or test an approach? What was the result?
(Captures of failures are as valuable as successes — they prevent repeating mistakes.)
→ Durability: `persistent` if the finding has future relevance; `transient` otherwise
→ Tags: `#project` or `#work` or `#brewmind`

**3. Open threads**
What questions or tasks are still unresolved? What do I need to pick up next session?
→ Durability: `persistent` | Tags: `#project` + domain

**4. Preferences or style discoveries**
Did I notice anything about how I like to work, what I find useful, or what to avoid?
→ Durability: `persistent` | Tags: `#preference`

**5. What to discard**
What from this session has no ongoing relevance? (Exploratory scratches, dead ends
that won't recur, one-off lookups.) These can be captured as `transient` or skipped.
→ Durability: `transient` | Tags: whatever fits

---

After all five questions, run `stats` to confirm the captures landed, and tell me
the new total thought count.
