---
layout: default
title: "Journal 1 — WREC App Login UX"
permalink: /journals/journal1/
---

**The Wildcat WREC App has a poorly designed Login Design**

![wrec dashboard]({{ "/journals/barcode.png" | relative_url }})
![wrec login barcode]({{ "/journals/dashboard.png" | relative_url }})

I often find myself opening the Chico State WREC app to bypass the entry gate of the gym facility. Given my tight schedule I like to enter and exit the facility as smoothly as possible but I often find myself having a harder time enterring.

I open the app and enter my chico state credentials, clicking login. The app freezes, goes completly static, and if I'm lucky I'm met with the UNIQUE barcode for my chico state student ID. This time after a what felt like minutes my app refreshes the login page, and I have to type all of my credentials in again manually. I often assume I typed something wrong but the app will actually tell me if I did that. So the issue isn't my login credentials. 

After a few failed login attempts I often go to the front desk staff and tell them my issue, they often just bypass the gate for me to enter after confirming my identity.

UX Analysis: A big issue at play here is **visibility of system status**. The app should be clearly showing how much progress is being made. For login pages we often get a small change in the display, whether that be a spinner or another indicator. But in this case it doesn't tell me what went wrong.

Another issue at play here is the users **mental model** the idea that they carry experience of a similar task from previous applications. So they are expecting certain behavior when typing in their credentials.

Another problem is just plain **feedback**. In fact, the app doesn't show us much at all unless it one of two results. The app attempts to push the user along by refreshing the entire process to try again? Some strengths, the app works, the login interface is actually super simple. When the app does work it is fast.

The weaknesses, there is little to no confirmation of progress, it is error prone, and very inconsistent. 

Suggestions for imrpovement, let me use FACE ID to sign in so I don't need to use both hands (when i carry things into the gym) to get through the door.