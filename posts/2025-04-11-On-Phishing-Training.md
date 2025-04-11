---
title: "On Phishing Training And Phishing Simulations: The Rant"
date: 2025-04-11
---
If you're here, you have either been exposed to <i>EmsK Rants About Phishing Simulations</i> before, or inexplicably the Internet has led you here. Welcome. 

Phishing training and/or phishing simulations. They're an inextricable part of the security landscape these days. Chances are you've been exposed to them, been asked to run them, and have strong opinions about them (what is a security person without strong opinions? do those even exist?) 

Let's look at the goals most orgs <i>say</i> they have.  
<ul><li>A more secure organisation.</li><li>Well educated end users</li><sub><li>Appeasing the various audit bodies, cyber insurers, and other bureaucratic behemoths overshadowing the day job.</li></sub></ul>

Nice goals; let's look at reality. 
<ul><li>People <s>are stupid</s> make mistakes.</li></ul>

<h2>You cannot train people out of human error.</h2>

Just witness every single IT Security person ever who's fallen for a phish, clicked on the "free things!" scam, had their credit card details lifted online... 
<center><a href="https://www.mimecast.com/the-state-of-email-and-collaboration-security-2024"><img src="https://emsknz.github.io/images/mimecast_2024.png"></a></center>

"But the CIO says I have to run phishing simulations."

Well, yeah, of course they do. They're dealing with the aforementioned bureaucratic behemoths that all advocate phishing simulations. 
<div style="background-color:black; width:100%;">
  <center>
<img src="https://emsknz.github.io/images/stolen_creds.png">
  <br><br>
<img src="https://emsknz.github.io/images/falling_for_phishing_fast.png">
</center>
</div>
"But my users are really smart!" 

Mate, so are mine.  And in every simulation campaign we've run since 2017, at least one person falls for it in under sixty seconds.  People are, first and foremost, PEOPLE. 

It is their JOB to read the emails in their inbox and click on the links.  It is their JOB to download that invoice from the supplier, to open the quotation, to read the document their colleague just sent them.  Phishing gets more and more believable every day. You know this. I know this. So why do we expect our end users to somehow magically get everything right? 

But, your CEO says you have to run phishing simulations, etc.  So, Instead of arguing about it, let's reframe it and get something useful out of the exercise. 

What do your mail stats look like? At my org, about 10% get blocked at the gateway; 2.5% of mail gets blocked as phishing/malware/etc; and about that amount gets ZAPed after delivery.  
I am not here to be sold things by vendors. If you're a mail gateway vendor and you can prove to me that you block ALL phishing and never accidentally block necessary email, we can talk, and while we're at it I'd like a pony.  

So you know phishing is getting through to the inbox. What do your people do with it? 

Our simulated phishing campaigns, which we've run using one platform or another since 2017, tell us the following:
<ul><li>approx 30% of our people click the little "report message" button in Outlook</li><li>approx 10% of our people click the links, depending on the believability of the campaign</li><li>approx 1% of our people enter the creds</li></ul>

Every. Time. 

<b>Why is this useful information?</b>

Because the actual <i>math</i> has 5 people in my organisation, <b>every single day</b>, entering their credentials into a phishing email. 

Our successful simulated phishes include people from every level and role across the company. The C-suite, the newest of grads, seniors in the ICT team. No part of the business is immune from human error. 

"Hello, Finance Department, please provide monies so that defense in depth can continue to happen."

Phishing-resistant multifactor authentication. Endpoint protection. URL filtering. CASB. Your SIEM and SOC. Whatever it is that would <b>practically</b> enhance your security posture.  

And for the love of little apples, don't get punitive about it.  People are going to make mistakes. YOU are going to make mistakes. 

We're there to support the business.  Our security training - which every employee has to do as part of onboarding, and yearly as a refresher - focuses on that fact. We're there to HELP. TALK to us. Use the button in Outlook. Pick up the phone. 

<b>Summary:</b>
Phishing is a fact of life. Phishing simulations are probably a fact of life. 

We can use the tools to work together, to uplift the businesses we support, and help out our people. 

<a href="https://security.googleblog.com/2024/05/on-fire-drills-and-phishing-tests.html">The Google blog "On Fire Drills and Phishing Tests"</a> is a great read. Please go read it.  
