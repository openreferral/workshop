---
layout: default
---

<blink><h1>NIEM</h1></blink>
<h2>NIEM in a Nutshell</h2>
* The Big Idea: A common vocabulary across government and partner organizations


NIEM Functional Overview Graphic
![NIEM Functional Overview Graphic]({{ site.baseurl }}assets/img/niem_functional_overview.png)

<h2>How NIEM and Open Referral can work together</h2>
* Use NIEM UML to tie your logical model to government systems
    * You don't have to use XML Schema if you don't want to
    * NIEM UML is a technology agnostic, lowest common denominator model which the exchanging parties can build upon, using their preferred technologies (JSON, CSV, web services, linked data, you-name-it)
* Adapter classes in logical model 
* A lot of potential tie-ins between I&R and NIEM are at the client data level
    * example: Linking human services to Justice is  "excarceration".  A community human services agency  is notified that a person in the prison system is being freed within 45 days, since they are completing their prison sentence (Orange County, FL is/was building such an exchange).  A path from a human services model to a NIEM model would be very useful in such work for harmonizing terminology, before the exchange project even started.
    * another example: integration between county funded community behavioral health, schools, and law enforcement.  This is a way school shootings can be prevented. 
* as the NIEM Human Services Domain, NHSIA, and the NIEM Children Youth and Family Service develop, the potential tie-ins will increase
* HHS Connect in NYC uses NIEM to specify Human Services exchanges

<h2>National Human Services Interoperability Architecture</h2>
http://www.acf.hhs.gov/nhsia-definition
NHSIA Conceptual Model Graphic
![NHSIA Conceptual Model](http://raw.github.com/hserv/open-human-services/master/doc/NHSIA_conceptual_data_model.jpeg)
