# Defensive Security Intro (TryHackMe)

Link: https://tryhackme.com/room/defensivesecurityintroezn39

What it was: An introductory lab from the other side — not an attack, but a defense. The task was to detect and stop an attack on FakeBank, playing the role of a SOC analyst.

What I did:
1. Opened the monitoring dashboard and viewed the latest alerts (notifications about suspicious activity)
2. Identified a suspicious IP address that generated anomalous traffic
3. I analyzed the list of "URL Discovery Attempts" and determined that the attacker was trying to find hidden pages of the site (the same type of attack that I did in the previous room - only now from the defender's side)
4. Blocked the attacker's IP address through a firewall rule (Add Firewall Rule → BLOCK)

What I learned:
- What does the SOC analyst's work look like: monitoring dashboards and searching for anomalies in traffic
- The difference between offensive and defensive security: the attacker looks for weaknesses, the defender - detects and stops the attack
- What is containment - the main priority in an attack: stop first, then understand the details
- Response methods: blocking IP, rate limiting, tightening access rules
