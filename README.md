# Codepath_Honeypots

# Honeypots Deployed

I set up three (3) honeypots in total: one with Dionaea with HTTP, one with Dionaea, and one with Shockpot. The results between the three different greatly, and are summarized below.


# MHN-Honeypot-1

This first honeypot was run using the Ubuntu Dionaea with HTTP script. Honeypot-1 was by far the most successful in data-collecting, being attacked 3,202 times as of the time of writing. The attacks came from countries all over the world, using a variety of ports and protocols. It was interesting to note that the vast majority of the attacks used pcap as their protocol, although SipSession, smbd, mssqld, and ftdp were all used. 


# MHN-Honeypot-2

Honeypot-2 was run using the Ubuntu Shockpot script. Strangely enough, this honeypot was completely unsuccessful, garnering not a single attack. Despite it being run during the same time period as my other 2 honeypots, and run using an Ubuntu script, this honeypot was left alone. I am unsure as to why it wasn't attacked, but I assume that Dionaea is a more popular script these days than Shockpot is, and therefore Honeypot-2 was much less likely to be attacked.


# MHN-Honeypot-3

My final honeypot was run with the Ubuntu Dionaea script as well, although it was the version without HTTP. This honeypot was almost as successful as Honeypot-1, with it capturing 2,788 attacks up to this point in time. Similarly, the majority of the attacks were performed using pcap as their protocol, with the next most popular protocol being SipSession. This honeypot also attracted attention from users around the world, but there were far more instances of attacks coming from IPs in the United States. Curiously, there was one United States user who attacked my honeypot over 20+ times, each time trying out a different port each time. As observed with my first honeypot, it seems that Dionaea is an incredibly popular script, even the version without HTTP, which would account for the high number of attacks.


# Issues

I ran into several issues during the setup for this assignment. The instructions were at times extremely vague and misleading, but ultimately I was able to set everything up successfully. The most difficult part of the lab was linking the honeypots back to the MHN-admin console, but once that was done the rest of the assignment was easy.

# Unresolved Questions

At this stage, I am still curious as to why Dionaea is much more popular than Shockpot, as well as why pcap is used more often than the other protocols. 
