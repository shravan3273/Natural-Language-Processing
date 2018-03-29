# Natural-Language-Processing
As the worldwide use of phones has grown, a new avenue for electronic junk mail has opened for disreputable marketers. These advertisers utilize Short Message Services(SMS) text message to target potential consumers with unwanted advertising known as SMS spam.This type of spam is paticularly troublesome because, unlike e-mail spam, many cellular phone users pay a fee per SMS received. Developing a classification algorithm that could filter SMS spam would provide a useful tool for cellular phone providers.


Since Naive Bayes has been used succesfully for e-mail spam filtering, it seems likely that it could also be applied to SMS spam.However, relative to e-mail spam, SMS spam poses additional challenges for automated filters. SMS messages are often limited to 160 characters, reducing the amount of text that can be used to identify whether a message is junk. The limit, combined with small mobile phone keyboards, has led many to adopt a form of SMS shorthand lingo, which further blurs the line between legitimate message and spam.Let's see how a simple Naive Bayes classifier handles these challenges.


This dataset includes the text of SMS messages along with a label indicating whether the message is unwanted. Junk messages are labeled spam, while legitimate messages are ham. 
