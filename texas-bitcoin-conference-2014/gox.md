---
title: Gox (2014)
transcript_by: Bryan Bishop
categories: ['meetup']
---

Ryan is a founder of BitBits. They donate to any charity in the US. BitBits was a 2013 Harvard Business School new venture finalist. Coming from Mass. As many of our speakers they have traveled a long way. Andreas from ... lawyer. Anti-money laundering specialist. He represents many companies for the transfer of money. He is a criminal defense attorney. He is a frequent speaker. On freedom too. All about freedom and frequent speakers at many money transmitting issues.

Gentlemen you have a bunch of important things to say. I am with Austin Bitcoin Meetup. What we have on the Skype, although I'm not sure it's being broadcast, the video yet, we have Charlie Shrem coming in from New York (applause). Charlie is picking up audio from my cell phone right now. Charlie you want to speak?

Alright it works. So we're here to talk about Empty Gox. Mt Gox. Empty Gox. We only have 20 minutes so I'm going to try to go through this panel as fast as it can. Maybe we can start with Andreas and give a history of goxxing and then pass it on to Ryan.

Yeah, sure. So for those of you who are new to this, this was not the first goxxing.  By my count this was the 6th goxing. Every single one of these goxing aused a simple drop in confidence and revealed the gross incompetence of a single organization headed by someone who has very little experience in security and trying to implement a financial stock exchange in PHP. Caused untold damage to our industry. This was the same person as a visionary bought an organization... initially created for magic the gathering online exchange. There is no mountain. There is no MtGox. There is Empty Gox, that should be the first hint. Took that organization and built a PHP backend that couldn't possibly scale. NOthing wrong with PHP. It's a great languge for building applications, but not great for building stok exchanges. Not as a monolithic application stack. This doesn't scale.

Gox was always running behind the curve. They were always trying to catch up with demand. Back in April 2013 we had a serious goxxing when the exchange collapsed under the ridiculous load of 7 trades per minute. By the way, that was when there was a call to arms and they created Buttercoin. Within 2 weeks of code hacking i saw the first implementation on my laptop and got about 100k trades per second. Monolithic PHP/MySQL ... it produced an hour of lag. They didn't halt trading. They never did the responsible thing. And that I was think by my count the second goxxing. And then we saw the second goxxing which was blamed on DOS. They were behind a cloudfront service. Their firewall was configured to allow direct access to the IP address, so you can attack just the IP address instead of going through cloudfront. That was so basic. Basic was way above the abilities of this team. Then we saw the goxing about withdrawal halts on USD. And then the other one was the transaction malleability.. this was only effecting Gox. They didn't get roped because of this.

I am sure we will have a lot of theories. Incompetence explains a lot. There was a famous IRC conversation where Mark Karpeles said let me connect to the server and transfer. If you can connect to a firewall and access the cold storage, it's not cold.

Gox is the story of a person who took on a challenge much too big, never asked for help, and always stood one step behind and was scrambling to catch up. This was entirely incompetence. Why do we trust an exchange that takes money off the exchange? Why make it custodianized by one company? They ended up in the worse of both worlds. That's the story of gox.

While Gox has filed for bankruptancy, most of what we know comes out of the crisis sstrategy dock. Who was your source? So it was given to me by Satoshi. No, I'm just kidding. I wish I could share Andreas' confidence that this is an isolated incident. How I came to get the document started last Sunday afternoon where I learned from a source that SecondMarket was accelerating their announcement. I knew about this but I was sitting on the information. This was about the same time that MtGox deleted its entire twitter feed. I started to reach out to my industry connections to see if these two events were related. I got the document fall into my lap.

SecondMarket did everything professionally and correct. The document fell into my lap and I was able to authenticate it. The person who sent it to me is an industry insider. I was able to confirm with a source at the Bitcoin Foundation that the numbers were correct. I was able to confirm with a leading industry investor that the numbers were correct. I was able to confirm that the author of the pdf was from Midala Consulting who did advising for MtGox. High profile member of the Tokyo Bitcoin community. I was able to confirm this with Charlie SHrem who has a direct line with Mark Karpele... while Mark said that this was not Gox, he was full of shit because he paid the guys that wrote it.

Afterwards there was speculation that this leak blew up deals. They claimed that there were investors in bailing out Gox. If so, they were corrupt and criminal investors that were not based in the US. SecondMarket was approached, but they immediately halted trading with their employees and went into lockdown mode in terms of compliance and doing everything by the book to not continue to defraud investors.

Finally the joint statement that came out when I leaked the document.. the statement was 80% complete leading up to the leak. WHat bothers me isn't that Gox is grossly negligent and incompetent and perpetrating massive fraud. But also the willful neglect of the Bitcoin Foundation. They knew that there was red flags since the US govt seizures. There was nothing to protect consumer interests, technical etc. Coinlab and MtGox had a conflict of interest. Neither board member- Mark or Peter- decided to step down. There's a lot of overlap between Coinlab and Bitcoin Foundation employees. The organization had no safeguards in place. This may have contributed to less informed and less connected investors keeping their money in much longer than they would have at MtGox.

Most troubling that Peter and John have not expressed an interest in resigning from the board of directors. CUrrently the Foundation is at a retreat and they are discussing the next steps and will release something in the next few days. I don't think that all of the responsibility falls on John.. an elected board needs to be on the foundation by next year. One of the close connections to the BOard was not only that Peter does not intend to step down but he wants to go for re-election. The general counsel for the foundation said that it was in his right to do that. The board itself was ready to vote Peter out. They don't like that idea. Giving the opportunity for Peter to resign. Just like I was given after my arrest. I think we will see some announcements over the next few weeks. I am the source. I am still a founding member on the Bitcoin foundation. The bylaws are available for all to read. You can find out how the foundation works and what the structure. What are the rules for election, resignation and firing?

There are specific clauses that protect the founding members from being fired unless they are involved in criminal activities. It is difficult to kick out the founding mebers. That's actually very common in professional associations. The founding members.. a situation to not be squeezed out by future generations. It would serve everyone if we would look up the bylaws and see how this organization work. If you are a member, then you have power. Please get involved if you are a member. The last election had terrible turnout. Your voice is the voice of the foundation. Charlie, just let me finish, I didn't interrupt your rebuttals. The bitcoin community has lost its moral mandate to self-regulate. This has done irreperable harm. The Bitcoin Foundation was complicit in allowing this to happen.

If the sponsors of the Bitcoin Foundation don't insist that the board takes responsibility, then we all have blood on our hands. These two gentlemen should do the right thing and step down for the good for the entire industry's image. There's more to the story, I'm going to continue to release it. I am not going to rest until these guys stop fucking up our industry.

Charlie, a lot of us heard your live reaction on the Let's Talk Bitcoin broadcast, which was published a few hours after your reaction. Want to give us an update about what you take out of this collapse and what you have been talking with Mark about? Before this all went down, everyone knew for the past months or years that MtGox was a big problem. I agree that neough wasn't done to warn people about what was happening. Everyone was in the dark including myself. When the document was leaked, I pleaded to Ryan to prove who he was or that it was real, I didn't believe that it actually existed. The first thing he did was call me up on my cellphone, here's the doc, help me confirm the authenticity. I sent a message to Mark, I asked him,  what's the situation. He said it's true.

Mark, you understand that this could be a striking blow to Bitcoin? He said I know. That's the last thing he's said to me. At that night, I got into Let's Talk Bitcoin podcast with .. Coding in my sleep. To talk about what happened. We were all caught off guard by this. We don't know where this money is. A lot of people thing that.. hacked.. where is the proof of that? A lot of people are doing, 100%.. I think their assets could be a lot more. That's the biggest problem. Trying to develop a transparent.. to prove to the world that a culture of knowledge and.. needs to.. and not with a central point of control or.. and we're failing ourselves by allowing us to have these central points of failure. I'm getting texts about bitcoin dying. I am afraid. I can't go out of my house. Well, I can't actually go out anyway.

I got to know Mark personally back in 2010 and 2011. Nobody had thought that he was running this ponzi scheme. A lot of people met his wife and his child and saw where he lived and saw that he had a regular family anyd everything, but nobody would think that Bernie Madoff was doing the same thing. Let's talk about that for a second.

Like you were saying... he's a family man and a nice person and things like this. But the issue of trust in a particular person is problematic. And in the case of, for example, the former CEO fo Goldman Sachs, a former US Senator, John, raided customer funds to a tune of a billion dollars. There is no one person that is going to be able to solve that type of problem.. let's talk with Andrew for a few minutes. You're an expert in this.. you had business with egold before?

Let me just distinguish egold from a ponzi scheme right away. Let's go to a point that Charlie was just making. I've seen a lot of ponzi schemes. I do criminal defense work in Miami. We could get into social security later. With a ponzi scheme, nobody sets out to operate a ponzi scheme. It's not really the desire of the fund or whatever else it may be. At the onset of the company. Typically including with Madoff, early on in the lifespan of a business and this might be the case with Gox. They lost money somewhere along the way. THe value of Bitcoin fluctuated too wildly, and it went too high or too low at a given point in time. What Mark had to start doing was using.. the money from old customers in order to pay new money or newer customers. That's probably the reason why we see him going into cold storage to replenish hot storage accounts. But I highly doubt that it was his intentions to operate a fraudulent scheme.

He probably didn't know what he was doing. He got in way over his head. It got way over his head. At the time that it got out of control, we start seeing cover ups and desperate management situations. In hindsight they might be stupid, but at the time they genuinely think it was a good idea. When the FBI looks, it's just completely damning and that's what this document that Ryan shared with us is. It's nothing short of damning.

As far as, I guess, moving forward. Charlie, I don't know if you want to jump in real quick, I ..Charlie? I agree with your point, I should have seen the signs myself. There were so many things that happened that I blamed on other things. Anything you say here will be used against you in court. 100%. There are things like, um, bank delays and a lot of people were saying, it's because of the banks and there are issues that it takes weeks to withdraw dollars and the idea that was floated around was that Mark was using the dollars that he was getting to buy bitcoins so that he could make sure that so that people would not be worried about using exchanging, that withdrawals would happen instantly, and that dollars being withdrawn could be blamed on your bank, his bank, etc., and bitcoin withdrawals can't be blamed on that because you either have the bitcoins or you don't have the bitcoins.

I don't know how you're going to take this, but, you might boo me, but it's this kind of case, and this might be feeding off of what Ryan said earlier, it's this kind of incident that will be empowering to State Regulators down the road. State regulation of money transmitter businesses are designed to deal with this type of incident. The federal government has come out and said that any type of business engaged in bitcoins are money transmitters. The states are probably going to agree. If I become a state licensed money transmitter, one of the requirements is that I have a bond in place in every state where I'm licensed, and the bond value is going from $100k to millions of dollars depending on the volume of business that I'm doing. The purpose of that bond is to make the users of that money transmitter in the individual states whole in the case where the money transmitter collapses so that I don't have to ... international forfeiture in order to be made whole. There's a thing there that is located there.. in my state. A bond.

We have just a few minutes here left. We are going to go to Justus here. He is going to talk a bout self-regulation. There's a thread on the Bitcoin talk forums called List of major hacks, scams thets and licenses. It only lists the major ones and that list is several dozen long. Those of us in the bitcoin community have watched how each company has stolen or "lost" or lost customer funds. This has been an ongoing topic about how do we stop that. Well, we just need to educate users to not let 3rd parties hold bitcoins. That's a valid solution. Nobody has ever lost bitcoins under their own control due to someone else's mismanagement.. our ability to educate users is linear, whereas bitcoin is growing exponential. There is always going to be a new batch of users that will not be aware of it. If a bank dies, the money is recoverable. But in bitcoin it's just gone, and users don't realize that. Anyone who has not been in a coma since 2008.. if the Federal Reserve can default on 50 tons of golds delivered to Germany, then we can't trust them to keep our bitcoins safe.

I discsovered a project called Open Transactions which is a lot like the counterpart to the transaction ledger. It's a cryptographically secure liability .. he floated a proposal called voting pools. It's a way to merge the cryptographically secure transactions of OT with the multi-sig transactions of the blockchain. Competing bitcoin companies like hosted wallets, banks, or exchanges, instead of holding deposits themselves, they pool them into a multi-sig pool or pot and they all issue their customer receipts based on OT to make sure that all customers have unimpeachable proof of what the exchange owes them. All members must audit each other in real time to make sure the receipts stay clean.

They can't let anyone cheat because fraudulent receipts would be pay ing out from the voting pool's balance. They all have the requirement to watch each other. No single company acting alone can lose or fail to deliver customer deposits on demand. This is the future. It's not completely ready to go yet. Chris Odom and yamamushi are still coding it back there in the back. They think it will be ready in Q2 or Q3 of this year. We will have the ability for third party bitcoin companies to be incapable of defaulting on their holdings.

So this is one of many techniques for having.. within Bitcoin. We can implement surety bonds that involve depositing the surety bonds. Separate from the money that the exchange has, we can also do this with pooled insurance funds similar to FDIC. They pull insurance fees from banks and .. make whole those who are defrauded. This is very important in fractional reserve banking. IN bitcoin you shouldn't have fractional reserve bankings. We can have cryptographic proof of no fractional reserve where you use Merkle tree to add up the balances of the accounts and then prove those against the public blockchain. Every user can individually check that they have been included in the Merkle tree. If everyone can check that, anyone can blow the whistle if their funds are not included. We can do multisig transactions not just for esrow but also for backup. At this particular conference on this topic there will be announcements.

I think we have solutions. I tweeted to Ben Lawsky that he should look at cryptographic proof of reserves. Old style human style is just not going to work. I am going to go show them how they can use this. We can do better than the institutional regulators. Not only did the bankers ... at least Mark is going to jail if he stole this money. We are going to do better than the banks at cleaning up our own mess. Don't just talk about self-regulation, talk about algorithmic regulation, and they like this idea because it automates the reporting and gives them the certainty about the status of the exchanges.

Things that are sufficient in fiat terms are not always sufficient in Bitcoin terms. Bitcoin is far more profitable to steal than fiat dollars. Weve never heard a case where gangsters ... bank wires are slow and reversible. Bitcoin is neither of those two. We haven't seen organized crime really going after people who hold other people's bitcoins, but that just means we've been lucky. I don't think.. I've seen this pushed for proof of solvency.. proof of solvency is great, I don't think that goes nearly far enough, we have to take care of the future risks, not just the ones that have popped up.

Voting pools remove the control from the custodian and they can't be blackmailed into giving up their money because they don't have the power. We can't steal your funds even if we want to because we don't have your private keys.

You can add the federal government to the list of organized crime when you're talking about... I've seen it happen before where.. any type of company that deals in money, digital currency or anything else, they have a user agreement, they have rules in place, they have policies in place that they wont disclose information to the government, and then the government comes in and it becomes a game of uncle and they get the information regardless of what the user agreement was... if you're going.. you're probably going to do. it. I think that just ... we're all in this government gridlock.

Question for Ryan.. I am a member of the Bitcoin Foundation. Over what time period were the funds from MtGox were lost? Who knew what when? Nobody knows that. I don't think anyone knows for sure right now. I think there's more technically proficient people.. I'm a finance guy. I know that a lot of people are trying to crowdsource that, and authorities and forensics will get involved. I think if you look at the Wells Fargo accounts, Dwolla, etc., I don't think that it's unreasonable to think that those issues were going on at least at mid last year. The thing that really blows my mind is that I can understand the Bitcoin losses a little bit.. I don't understand how this business could.. could lose that much money... I've heard a lot of people saying things.. bulls make money, bears make money, and pigs get slaughtered. We may want to focus our ability on audits... if they do not comply with this level of transparency, then go do smear campaigns on... Andreas.. did a one-off spot checks. I think it's bad to do a quick audit on one individual and not thorough. I checked that they had solvency at the time that I checked... that was a very narrow scope.

We do need audits. But they require weeks of work. They require independent professional auditors. I have run teams like that for banks. It's not something you do quickly. It was neceessary to do it quickly to ensure the market that we did not have a systemic problem... we need to go much further. One of the ways we can do that is by having the exchange have a common risk pool.. and then the banks and the exchanges and brokerages with custodial access to funds will police each other. If you ... I think thats' a much better solution because you have the experts policing each other. If Coinbase and Bitstamp and BTCE were partly liable for Gox's losses, would they have allowed them to continue without audit if they were in a common risk pool? They would have demanded greater transparency and either kicked gox out of the pool or forced them to reform.

Audits can be week long processes.. or they can be automated. gmaxwell's... there are two parts to the audit. You can do technological verification of funds and things like that, but you still have to do the audit of the operational process of the team. This is a maintenance function. You can't do this by technology. You have to verify that people are trained and this is something that you do in a bank with firewalls and security systems.. you audit for social engineering weaknesses, you audit their employee bakground venting weaknesses. Even if we can prove the Bitcoin prove, we need to audit the fiat side because that does not have cryptographic nature.

There were a lot of insiders that knew better and they pulled their money out. Some people were trying to exploit the price difference. That wasn't arbitrage.. there was a systemic failure of leadership. I know a lot of people that lost millions. Including myself.. I have legal fees to pay for. I'm just trying to tell you that a lot of insiders did pull money out as far as last Spring.. you might not be objective because you trusted Mark, and if I was in your shoes and one of my .. I probably would have stayed loyal to my friends too. Roger lost a lot of money too.

The insider /// when SecondMarket figured out that something was wrong, they told everyone to stop trading. I found out on Monday afternoon that something was going down that was big.. and half an hour later I saw the leak. So I said that everyone must not buy or sell. You have information that has just been taken public, you do not touch your bitcoin. I did not sell anything that day. I knew well before.. when Ryan's went out. I had 30 minutes notice. I heard rumors. I could have sold all my bitcoins that maybe the price would go down. No. We do not use that information to trade on insider's information. That's the professional thing to do.