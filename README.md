# Project 8 - Pentesting Live Targets

Time spent: **6** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQL Injection (SQLi)
- https://104.197.169.195/blue/public/salesperson.php?id=' OR SLEEP(5)=0--'

Vulnerability #2: Session Hijacking/Fixation
- The session token does not change on each login/logout.


## Green

Vulnerability #1: User Enumeration
<img src='http://i.imgur.com/HQLLQbh.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Vulnerability #2: Cross-Site Scripting (XSS)
<img src='http://i.imgur.com/Uqo83ca.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />


## Red

Vulnerability #1: Insecure Direct Object Reference (IDOR)
<img src='http://i.imgur.com/EPseWez.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Vulnerability #2: Cross-Site Request Forger (CSRF)
- Invalid CSRF token will still allow the form submission to be valid.

## Notes

Describe any challenges encountered while doing the work

