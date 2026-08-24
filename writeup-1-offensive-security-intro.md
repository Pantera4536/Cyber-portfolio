# Offensive Security Intro (TryHackMe)

Link: https://tryhackme.com/room/offensivesecurityintrokKx12

What it was: An introductory lab where you had to hack a FakeBank test site in a secure learning environment.

What you did:
1. Launched a virtual machine with a fake bank site called FakeBank
2. Used the dirb tool to find hidden pages on the site (dirb http://fakebank.thm)
3. Found a hidden admin panel page that was not accessible through normal site navigation
4. Made a fake bank transfer through the found page, increasing the balance of the test account

What you learned:
- How to find hidden pages on a site using directory brute-force (dirb tool)
- Why hidden/unprotected pages are a real vulnerability, even if they are not linked to on the site
- Basics of working with a simple scanner in the Linux terminal
