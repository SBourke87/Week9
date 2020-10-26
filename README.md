# Project 8 - Pentesting Live Targets

Time spent: **5** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: Session Hijacking

Description: The blue site has a vulnerability where, using the provided php script, one can change their session to that of a logged in user


![gif 1](https://github.com/SBourke87/Week9/blob/main/Blue%2C%20Session%20Hijacking%20via%20given%20PHP.gif)

Vulnerability #2: Cross Site Request Forgery

Description: The blue site has a vulnerability where one can submit html to edit the site via the feedback section



## Green

Vulnerability #1: Username Enumeration

Description: The green site had an easy method of determining which users were valid and which were not.
The valid users were bolded on unsuccessful login while the invalid users were not!

![gif 1](https://github.com/SBourke87/Week9/blob/main/User%20Enumeration%2C%20Green%2C%20Login%20Bolded.gif)

Vulnerability #2: XSS

Description: An individual who is not logged in to the website may submit code through the feedback section. A logged in user triggers this code when it is viewed.

![gif 1](https://github.com/SBourke87/Week9/blob/main/XSS%20Vulnerability%2C%20Green%2C%20Able%20to%20inject%20XSS%20for%20logged%20in%20users%20via%20feedback%20page.gif)


## Red

Vulnerability #1: __________________

Description:

<img src="red-vuln1.gif">

Vulnerability #2: __________________

Description:

<img src="red-vuln2.gif">


## Notes

Describe any challenges encountered while doing the work

