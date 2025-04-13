---
title: "On Phishing Training And Phishing Simulations: The Rant"
date: 2025-04-11
---
If you're here, you have either been exposed to <i>EmsK Rants About Phishing Simulations</i> before, or inexplicably the Internet has led you here. Welcome. 

Phishing training and/or phishing simulations. They're an inextricable part of the security landscape these days. Chances are you've been exposed to them, been asked to run them, and have strong opinions about them (what is a security person without strong opinions? do those even exist?) 

Let's look at the goals most orgs <i>say</i> they have.  
<ul><li>Well educated end users</li><li>A more secure organisation.</li></ul>
  
Let's look at the goals most orgs have.  
<ul><li>Appeasing the various audit bodies, cyber insurers, and other bureaucratic behemoths overshadowing the day job.</li></ul>

Okay, let's look at the goals that are handed to you in Security. 
<ul><li>Make people stop clicking on phishing, so that I can report security posture improvements to the Board next quarter.</li></ul>

Reality check: 

<h2>You cannot train people out of human error.</h2>

Just witness every single IT Security person ever who's fallen for a phish, clicked on the "free things!" scam, had their credit card details lifted online... 
<center><a href="https://www.mimecast.com/the-state-of-email-and-collaboration-security-2024"><img src="https://emsknz.github.io/images/mimecast_2024.png"></a><br><i>Mimecast 2024</i></center><br>

"But the CIO says I have to run phishing simulations."

Well, yeah, of course they do. They're dealing with the aforementioned bureaucratic behemoths that all advocate phishing simulations. <br><sub>Also  vendors, other C-levels at other orgs who've been told and sold the same thing, and look is this the conversation you really want to have or do you want to spend your time in more useful ways...?</sub>

<div style="background-color:black; width:100%;">
  <center>
<img src="https://emsknz.github.io/images/stolen_creds.png">
  <br><br>
<img src="https://emsknz.github.io/images/falling_for_phishing_fast.png">
</center>
</div>
<br>
"But my users are really smart!" 

Mate, so are mine.  And in every simulation campaign we've run since 2017, at least one person falls for it in under sixty seconds.  People are, first and foremost, PEOPLE. 

It is their JOB to read the emails in their inbox and click on the links.  It is their JOB to download that invoice from the supplier, to open the quotation, to read the document their colleague just sent them.  Phishing gets more and more believable every day. You know this. I know this. So why do we expect our end users to somehow magically get everything right? 

But, your CIO says you have to run phishing simulations, etc.  So, Instead of arguing about it<sup><a href="#footnote-1">1</a></sup>, let's reframe it and get something useful out of the exercise.

Remember those goals?
<ul><li>Well educated end users</li><li>A more secure organisation.</li></ul>

<h3>Goal one: Training</h3>

First, you should have a training program.  Phishing simulations <b>ARE NOT TRAINING I WILL DIE ON THAT HILL</b> phishing simulations are a simulated <i>attack</i>. 

Your org will have it's own goals for training, but in the phishing space, you want it to cover: 
<ul><li>What is a phish 101</li><li>What to do if you see a phish</li></ul>

And for the love of little apples, don't get punitive about it. People are going to make mistakes. YOU are going to make mistakes. 

We are on the same side. Your end users need to trust Security, and believe that we'll help them. Don't treat users like muppets when they <i>inevitably</i> get tricked by the weapons threat actors are using to break into our organisations. 

My org's security training - which every employee has to do as part of onboarding, and yearly as a refresher - focuses on that fact. We're there to HELP. TALK to us. Use the button in Outlook. Pick up the phone. Do whatever the thing is in your organisation to get in contact with IT, and make sure that your IT and Security teams are kind when they get those calls.  

<h3>Goal two: A more secure organisation</h3>

Okay, training is done. How can you use the phishing simulations you're required to run to help improve security? 

Another hill I will die on: your phishing simulations <b>should not be cruel</b>.  Don't target your people with financial attacks, or HR themed attacks.  Look at the real phishing you get, every day. Use that. You want to know REAL stats about your REAL organisation, not to prove that you're a clever enough asshat to fool everyone in the business into clicking on your super custom crafted email that looks super realistic built with insider knowledge.  

<b>What do your mail stats look like? </b>

At my org, about 10% gets blocked at the gateway; 2.5% gets blocked as phishing/malware/etc; and about that amount gets ZAPed after delivery<sup><a href="#footnote-2">2</a></sup>.  

So we <b>know</b> phishing is getting through to the inbox. What do your people do with it? 

Our simulated phishing campaigns, which we've run using one platform or another since 2017, tell us the following:
<ul><li>approx 30% of our people click the little "report message" button in Outlook</li><li>approx 10% of our people click the links, depending on the believability of the campaign</li><li>approx 1% of our people enter the creds</li></ul>

Every. Time. 

<b>Why is this useful information?</b>

Because the actual <i>math</i> has 5 people in my organisation, <b>every single day</b>, entering their credentials into a phishing email. 

Our successful simulated phishes include people from every level and role across the company. The C-suite, the newest of grads, seniors in the ICT team. No part of the business is immune from human error. 

"Hello, Finance Department, please provide monies so that defense in depth can continue to happen."

I don't know what your org needs. Investment in phishing-resistant multifactor authentication? Endpoint protection? URL filtering? CASB? Your SIEM and SOC? DLP? 

Well, now you've got stats providing justifiction for ... whatever it is that would <b>practically</b> enhance your security posture. 


<h3>Summary:</h3>
Phishing is a fact of life. Phishing simulations are probably a fact of life. 

Let's use the tools we have to work WITH our people, to uplift our organisations, and make our corners of the world a slightly better place. 

<hr>

Footnotes

<ol><li id="footnote-1">Yes, there are very good arguments for not doing phishing simulations at all.  That discussion is for another day.</li><li id="footnote-2">I am not here to be sold things by vendors. If you're a mail gateway vendor and you can prove to me that you block ALL phishing and never accidentally block necessary email, we can talk, and while we're at it I'd like a pony.</li></ol>

References:

<a href="https://security.googleblog.com/2024/05/on-fire-drills-and-phishing-tests.html">The Google blog "On Fire Drills and Phishing Tests"</a> is a great read.
