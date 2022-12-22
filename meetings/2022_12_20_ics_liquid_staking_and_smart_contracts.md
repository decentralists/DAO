## Side A

**Twitter Spaces Transcript: Jae Kwon - Decentralists, ICS and Smart Contracts (followed by Liquid Staking)**


**Jae Kwon:** Well, we're gonna wait like 2 minutes, but in the meantime, is anyone?
A smart contract system developer.
Or.
An ICS developer.
Please raise your hand.
We have to have one developer.




**Adriana:** Alright, so since.
We don't have anyone right now who would like to take the floor and maybe some of the questions that people have regarding smart contracts are related to what originally was the discussion of having cosm wasm on the hub, the proposal which failed and and maybe people are looking right now at maybe an alternative solution or how we are able to.
To have a solution that could can use smart contracts with ICS. So for those who are not developers here maybe discussing the the ways in which smart contract can be added as a solution in a safe way through ICS and how this can can be done could maybe.
Clarify some of the questions people have when they are referring a smart contract in relations to yeah, a possible implementation through CS.
clarify some of the questions people have when they are referring a smart contract in relations to yeah a possible implementation through ICS




**Jae Kwon:** Can can people request to speak here?
Thumbs up anyone?
It's not even yeah, OK.
You can't, alright.
Ohh someone requesting here we go.
Umm.
Direct.
What are you gonna do, wreck?
You can't do nothing and do it.
Thank you.
Yeah, sometimes I feel like Twitter spaces or Twitter is like this.
What's the word? I don't know.
Some sort of a.
Containment jail, you know, like.
I don't know. It's just.
Twitter's weird.
All right, we've got another request.
OK.




**Adriana:**
OK, we.
OK we have

**Jae Kwon:**
Ah madman.
Thanks for joining.



**MadMan:**
I can't stay long. The headset's gonna die. I was in the middle of charging it. But the demand for, you know, some guest speakers up here, you know, I was.
I didn't want to fall to a fear that you know you might end the space, you know earlier than you would have had. You would have liked to kept it running out of lack of involvement and participation from the listeners. I was going to trying to wait towards the liquid staking portion of the conversation.
you know for for my questions and whatnot



**Jae Kwon:**
OK, yeah, let's let's jump into it.



**MadMan:**
you know for for my questions and what not but i didn't want to just like dive and steer the conversation out, you know, outside of what you were trying to, scope this for.

**Jae Kwon:**
OK, let's start with liquid staking and then let's go back to smart contracts. I'm sure we'll have a chance to talk about both here like you're here. I'll start off unless you want to start the conversation.




**MadMan:**
but by all means please start you know like i'm i'm not the you know



 **Jae Kwon:**
OK.




**MadMan:**
Um, but by all means, please start. You know, like I'm, I'm not the, you know, like the the big guy here, you know, I'm just, I'm just breaking in, you know?


**Jae Kwon:**
Yeah. Well, thanks for joining.
OK, so.
How do I see it all coming together?
I'm not. I'm not opposed to liquid staking entirely.
I think the biggest problem with liquid staking is the governance takeover.
If we don't do this right and.
You know.
A lot of lot of things end up being like 80/20 were #1 gets 80%.
Right.
And.
And that might mean that, you know, for example, maybe Quicksilver as a zone might have control over your blockchain because they get voting rights through.
Interchain accounts, right so.
We can mitigate that class.
By having simple code.
Hosted on ICS interchain security (ICS).
That way.
It's not. It's not. We're not delegating control.
To another zone.
That is independent of the Cosmos hub, but rather the Cosmos hub validators are the ones.
Who are securing both the hub Cosmos Hub 4 blockchain as well as the ICS zone?
Writing the smart contracts probably or. Or maybe it's written in the SDK for.
For liquid staking.
Then we don't have the governance. Now, the only risk we have here is if we design it wrong or there's a bug in the system, right? But then if there's a bug in the system, we can, we can fix it. Well, now, generally we know it's a bug and so we know how to move forward, right?
But then that that leads to the question of, OK, what, what's the, what's the financial economic model for these liquid staking zones then if it's just going to run under ICS?
umm but then that that leads to the question of OK what what's the what's the financial economic model for these liquid staking zones then if it's just going to run under ICS.
OK, I'll leave it there.
We're adding more people. Feel free to introduce yourself and.
They have blurb.



**MadMan:**
well yeah
Well, yeah, I didn't really introduce myself, I just jumped up here.


**Jae Kwon:**
Oh, yeah, yeah. You and I just added bullish.
Two, yeah.


**MadMan:**
Well.
I'm referred to as a madman, you can see I will gladly accept Piccolo.

I'm working on and I'm researching smart contract development for Terra and Terra classic. I've been.
You know, rather vocal in the community. I've been rather observant with some of the issues with, you know, with governance.
about the risks for liquid staking you would just starting a primer just a moment ago and i i kind of want you to continue on that and expand on the risks for LP stake derivatives as you know as kind of like a next level scenario because i could only imagine that that's you know it's only a matter of time before that's you know kind of pushed forward between different projects not to say the number by myself i've been doing it but you know it's
About the risks for liquid staking, you would just starting a primer just a moment ago and I kind of want you to continue on that and expand on the risks for LP staking derivatives as you know as kind of like a next level scenario because I could only imagine that that's you know, it's only a matter of time before that's you know kind of pushed forward between different projects not to say the number by myself we've been doing it but you know it's.



**MadMan:**
Or to say that it's worth the exploration and I don't know who to ask in or what to ask.



**Jae Kwon:**
Hmm. OK, I'll try. Thank you for that.
And, and by the way, one thing I need better understanding on is how other projects use the term liquid staking. I don't know how Luna’s Liquid staking works, but in in the Cosmos hub in general, you know it's about.
Tokenizing the atoms that you delegate toward particular validator and there's many ways you can group.

You know many ways you can define this token. Either it's a token that tokenizes delegations towards a particular validator or or or a subset of validators or something like that anyways.
Because I've I noticed that some people are calling the photon token in the ATOM 1.0 proposal liquid staking and ATOM 2.0, and and I don't really think of it that way.
But anyways, moving on.
OK, yeah, the risks with liquid staking.
Umm.
OK. So generally?
I remember that thread and I'll try to touch on all the ones.
But I'll start off with this. I think that the risk to liquid staking some I know, and I'll talk about the ones I know, but also.
The general risk, right, the whole point.
Of liquid staking or the whole point of staking is that you have skin in the game. And if you if your skin in the game is liquid, do you really have skin in the game? Depends on how you do it.
Self sabotage.
So.
You know, validator itself generally doesn't wanna.
Sabotage itself. But but imagine, imagine you have a… You know, it could be as simple as assigning component. You know someone or some entity, somebody is responsible.
For deciding device right?
Umm.
And this person might not have a huge stake.
In the validator or the company but but has control.
Umm.
Over what this validator signs and this asymmetry allows them to potentially.
Short.
The leak was staking tokens and the validator.
With leverage.
And be able to profit from it.
Um, of course this is completely illegal.
So, you know, probably people won't do it, but you know, some people would. I mean, if the incentive is there.
Right.
How do you prevent people from taking advantage?
Of.
A systemic corruption?
And again, this also requires a liquid market and again this also requires a liquid market that..
At least has shorting capabilities and probably leverage too right yeah you'll need leverage or at least the ability to get a loan right large loan.

OK, so these are two cases that require many components to come together. So these are complex cases, but they're ways in which liquid staking can subvert the system.
And beyond that, I don't know. I honestly don't know how I thought before there was some compounding thing. I'm not so sure about that anymore.
Like OK, so I'll try to think this through for validator.

You know what's gonna happen, I suppose for me, if I were running a validator and there was a liquid staking market, you know, and what I could imagine happening wrong. Maybe, like I over leverage, I borrowed too much money.
And.
You know, suppose buy up my liquid stake and tokens, or buy atoms liquid stake, right, and try to sell these. Promote these liquid staked tokens out in the market to just make a whole meme or whatever. Market out of it. That in itself is dangerous because now you have this token that's being promoted.
That really shouldn't be promoted out of context.
Right.
And theoretically it's OK, but in practice, if you have a tradable token and the reason to incentivize, you know, people to buy it, then you're going to have, you're gonna have all kinds of shitcoins.
That's the reality of it right? But anyways, going further and then so I would I would try to figure out a way to sell these liquid staked tokens and then buy more atoms compound in that way as opposed.
But, but it's yeah, it's it's more like I'm over leveraged.




**MadMan:**
Right. And that just becomes a risk to the user's choice for doing that at that point.



**Jae Kwon:**
Yeah, yeah, but I don't understand this case fully, but I think there's something here that also includes the fact that, you know, because I'm incentivized to do it, all the other validators are going to do it too, otherwise they'll get pushed out of the market. And so you end up with systemic issue because everyone's pressuring each other to over leverage.



**MadMan:**
Gotcha. OK.



**Jae Kwon:**
But but at least I know two cases that are.
Precisely. Problems right now we should. I'm sure there are more. We can, we can you know and of course there's a whole category of.
If your liquid staking application is running on the zone and it's happening through ICA, you're delegating governance to the other zone. Maybe you want to put a limit there, or better yet.
Run it under ICS.
In the parallel blockchain.
So that there is no external validator set risk.
Right.
So, but then, but then the question is, I'm going to go back to the question I asked earlier. How do we deal with, you know, what do we do with this market? I don't understand first of all, why there's such a huge liquid staking market. I don't get it.
Because, yeah, it's exciting, you know, and but there's also like.
All kinds of potential pitfalls and.
It is an exciting field of research and there's there's going to be real value ultimately in the end, if you run this right with ICA, you know, ICS and so on.
But you know.
The benefit.
Is what you're ultimately saving on.
The unbonding period when you're unbonded.
So, you know it's already got this limited utility and I don't understand why it became such a big deal supposing ethereum?
It started with Ethereum right? When they proved, well, we started with us. We were already looking into it. Other other massive post Teslas was working on it too. And then any ethereum, you know, every single idea gets implemented as a smart contract. And then and now.
Ethereum is where I suppose a lot of liquid stake and stuff happened and it translated back into our ecosystem, right?
Umm.
And.
You know, I think, I think we should reward good implementations. Just put it in the road map to really enable the ICS for security’s sake, so that everyone benefits both from security and from.
You know, return on investment for implementing something good.
And simple. It has to be simple.
Feel like I'm rambling?
Anyone else wanna talk?


**MadMan:**
No, you're you're not rambling. I'm, I'm picking up what you're putting down.



**Jae Kwon:**
All right.


**Michael Sofaer:**
Hey, hi, I'm Michael. I built a smart contracting app chain. It's got its own smart contracting language designed for games and and for art. Trying just trying to be super, super fast at doing you know very limited set of stuff.
Um, and you know, I wanted to. Sort of.
I guess I'm sort of, I've been thinking a lot about, you know, ever since CosmWasm proposal, you know, I voted against it because I was just like, OK, putting CosmWasm on the hub, but like why?
And so I vote, I, you know, I didn't support it because I was just like but but why? And you know, that sort of is and I think that ties into what you were saying about.
Um.
About like we're seeking, which is also with the market like why is there a market, right? And I guess I sort of want to.
I guess sort of like.
That there is a certain amount of like that with with everything the hub is doing and I I what I really want to ask you is like what should like, what is like what is what should the hub be doing like like in service of what? Right like smart contracts or ICS or like or like liquid staking or whatever. But like in service of what? Like what's your dream for like the hub, what service should it provide to the interchain? Like ideally what what is the like? Why are people using the hub?
I don't know. I wanna know. I wanna know where you come down on that.



**Jae Kwon:**
Hey, thanks for asking. OK.
Um.
Alright, so I'll I'll just do sort of a shotgun approach.
So the basis, the hub is a token pegging systems for IVC, token pegs, right, but and that's that's a needed feature for the entire token crypto ecosystem in the future, you know, not necessarily right now but in the future we won't need it. We'll look back and say I'm glad we have that.
Because we need hub and spokes for decentralized systems, because zones can fail.
Right. And then.
Also offering ICS.
For scaling’s sake.
You know this isn't some weird add-on.
That is artificial. Any blockchain system that needs to scale is going to want to solve ICS.
Right, so we might as well solve it too.
And that opens the door to a lot of a lot of applications, right?
And so it's this secure?
Platform not only for token pegging, you can you know IVC, connective, token pegging, but it also is a place for you to run your smart contracts if you want. Or you can run it on some other zone because it offers something else.
You know, and and I think we should also have regional hubs too, like a US based hub that runs on, offers a different set of regulatory whatever. You know, every country should have their own blockchain and hub and they should all connect to Cosmos hub as an intergalactic hub for token pegging.
Umm.
On another side, I see this blockchain funding for.
Common goods.
You know, so we're we're creating open source projects, you know, and we're making things secure.
Along the way I see it.
Also funding for something we need right now, which is a DAO system for transparent management of Treasury funds, right? So now we have the common pool.
We need a way to use these funds in an accountable way. We need DAOs.
You know, we need to get there. We have everything on chain. Everything is by default transparent.


So the hub funding a team that maintains this system.
As it scales to ICS and refines the UX of this DAO system.
Which you know also in the middle of that layer is caked in smart contract system, right? And funding for that and also better versions of that.
Is this what I see us doing?
With the Cosmos hub.
Yeah, you know.
I should also mention the political landscape.
Right.
Because there's a war going on. I mean, I'm sure you've noticed things are weird.
Right.
And and some people want to chip you and and control you and make sure you know only certain people get access and other people want to say, you know we want to preserve privacy, we don't want.
To be subjected to a particular regime, we want permissionlessness and openness.


**Adriana:**
We have three speaking requests.




**Michael Sofaer:**
Um, let me, let me just.
Follow up on that for a second. That was awesome. Thank you.
I guess you know aside from sort of you know the the atom as sort of like a as like a reference currency like the like you know the the hub dollar or whatever petrodollar of the of the cosmos space which I like I understand that and that makes sense you know when you when you talk.



**Jae Kwon:**
it's it's not a dollar



**Michael Sofaer:**
When you talk about being like a, uh, like an intergalactic like connectivity hub, should the hub be like building the kinds of features that like promote that, you know, I know there was a question of like IBC forwarding at one point. I personally believe that part of being a hub like that is to do like namespaces. I know there's a big battle about who should do namespaces right now. Should the hub get involved in like trying to sort of like do like name-spacing and discovery and routing and like
Transmission between like sub networks tools that in my opinion I think would really would really make that more powerful and and also probably you know make using Dows through interchange accounts more powerful where if you have these kinds of like discovery and and and forwarding tools for IBC for DAOs for whatever you know I think there's there's a there's a lot there that the hub could do technologically to like move in the direction of that if it wanted to and like is that stuff.
OK that's my question



**Jae Kwon:**
Yeah, you know, yes. But, but in a way, in a way, it doesn't have to focus on that right now because like, like.
Hmm.
I should say.
We should build those.
And we should host them.
Under ICS. So in a way, the Cosmos Hub doesn't really need to be aware.
You know. So what I described was like a bare minimum machine name system to get to where you need it's kind of like you know using IP's really you still need a name resolution system to get from a single name a word to that thing right. And and and I really think we need to we can consider API's and interfaces but you know and and specifications but we need to, we need to create.
Permission. Less experience experiments where different people implement these things in different ways.



**Michael Sofaer:**
Yeah, but the the risk is that there's like scammers, right you, you want to be able to not have someone put up osmosis, but like with with like the a different, a slightly different eye or something and you know.



**Jae Kwon:**
Yeah. Yeah. So that, that I suppose would make the hallmark of a good name system is one that solves that. Well, yeah, the ones, the ones that I see fail, probably all fail because they don't get that right.
You know what I mean? Like you need to actually make it a little less immutable and a little more moderated in that way



**Michael Sofaer:**
Yeah, that's.



**Jae Kwon:**
Immutable, and a little more moderated in that way. In the very least, you need to reserve quite a big chunk and go really slow, you know, because you're not going to figure it out, yeah.



**Michael Sofaer:**
that's exactly what i'm getting at is that is that like the permissionlessness i mean not the atom is permissionless so you know having some kind of way to say like hey like you know we as the governance of the hub have here's this list of 40 chains that we think are you know here's how you get to them and this is how you're not going to get scammed i mean i've seen people get scammed downloading the wrong capital extension, right.


**Jae Kwon:**
ah OK
OK, how how do not get scammed. OK, imagine this. I imagine we're gonna have… here's what I'm imagining for a particular implementation, right? So I'll describe what I'm gonna, how I want to solve it, and Gnoland through the GNO smart contract system, right?
But you know, this can be solved through other systems too.
The the GNL smart contract system know.
It also lets you render a web page from the smart contract, right? So you can produce a markdown file.
And it will get rendered. And that's when you go to the node land and you browse the boards and discussions. What you're seeing is the result of a smart contract call rendering a website OK.

What are we talking about? We're talking about.
How to not get scammed OK?
So, you know, if we make, if we make a DAO.
Something like the Decentralist style.
You know something and we hosted on a smart contract system that also does does a good job of moderating what is shown on the front page.
Then we would be able to produce.
A portal.
That is accessible from not only the browser, but also from the terminal.
Anywhere even different? I think we should get away from browsers. It's too clunky.
You know.
Too many, too much surface area.
But even with the minimal surface area client.
You can access.
A single web page.
On how to use the system without getting scanned, that's what we need, right?


**Michael Sofaer:**
yeah i agree with that i mean i just think there's this there's this place this is something and now i'm just going to sort of like come out and and say like sort of give my opinion for what it's worth but like



**Jae Kwon:**
Go for it.


**Michael Sofaer:**
I just think there's this, there's this place, this is something. And now I'm just going to sort of like come out and and say like sort of give my opinion for what it's worth. But like, you know, we as as a community, like we need some level of like authoritative guidance for people coming in and trying to figure it out. And we are permissionless, but there there's a balance there and I think we just really need more sort of like more.
So there has to be like something that's like authoritative for people getting in who need to figure stuff out. And I personally believe that if Cosmos Hub wants to be the heart of the cosmos ecosystem, like that's one of the things like the authoritative sort of, you know, these kinds of this is this is my opinion is that like hub should be trying to do things where authority is needed where you really only want to have one copy. Right. There was a point where we were talking about that for for
Multiple bridges maybe. That's fine. I don't know. But like for things where you only when you really want to have an authoritative copy of a thing. To me like that's something that the hub can do and and has a credible sort of claim as the only chain that can really do it right. If you're going to say OK I have a list you know, and I'm going to maintain all these projects and you can get on the list but you have to talk to us and you can't get on the list if we think you're scamming rig
And we can do it and it would really make the space better and it would start to like.
It would start to drive these unique use cases that I think are just really something only the hub can be. And and that's the thing that I've sort of been like been sort of like hungry to see. It's just like what is a use case that can only happen at the hub? What? Like what is a use case that really there has to be a Singleton of this service or of this thing, right. And we live in this world where like there's there's a continuum between permissionless and authoritative and without enough auth
unusable and won't get adoption and so it hasn't it hasn't given us any more freedom right if nobody uses it it didn't make us more free and there has to be enough authoritative you like like guide rails to make it usable and like to me the hub is the place that naturally wants to do that and i've just been like hungry to try to see use cases come up in the vision of the hub in the governance that like that give us that that give us that like we are the hub we are guiding this thing and like yea
Unusable and won't get adoption. And so it hasn't, it hasn't given us any more freedom, right? If nobody uses it, it didn't make us more free. And there has to be enough authoritative, you like like guide rails to make it usable. And like to me, the hub is the place that naturally wants to do that. And I've just been try to see use cases come up in the vision of the hub, in the governance that like that give us that, that, give us that. Like we are the hub, we are guiding this.
Right, here's the. Here's the hash of the of a Keplr extension we trust. Here's where you can find osmosis on Akash, whatever it is. You know, like.
Just just like that sort of like.
That voice has to be sort of singular I think and I think the hub is the place for stuff that's singular. So anyway, that's my opinion and that's sort of why I'm like trying to get your sense of like what do you think is the or you know, I think you did this, but like what do you think are like the things that has to be singletons have to be done by the hub? Because I think that like that's the question that gives us direction and like drives us forward as an ecosystem and and and really lets us
Like people fighting over pet projects but not having like a framework to even argue for why their pet projects are the right projects to sort of take us where we want to go, right? That's my speech.


**Jae Kwon:** 
thank you
You know, a short note on Keplr there. Wish, wish.
Wish they didn't make it so easy to enter your 24 words.
Umm.
And I wish.
it was easier for projects to get added here complaints about how it's not easy to get listed so



**Michael Sofaer:**
yeah but like
OK, so you know, let's talk about the name service for a bit. Maybe also it applies to Keplr, but.
OK, I agree with you that the hub should be.
The authority in practice for name services and and and various things you know not necessarily doesn't have to be the authority for name service, but you know it should be authority for a few things at least.
I just. I just think.
You know on the on the one hand, on the other hand.
Through ICS. So you know what that means is there should be these experiments and we should figure out, we should figure out the right solution over time. And then after the right solution has been found and identified, then we can more align with, you know, we can, we can choose that as a standard voluntarily, right? Like how do standards get made?
They don't really. They shouldn't be made through a convention, right? Ideally, they're made.
Through innovation by private parties that are made available to the public and and it gets adopted because it's the best design, you know, this would be like an ideal scenario, right?



**Michael Sofaer:**
I've I've been in rooms where standards got made and it wasn't that pretty.



**Jae Kwon:**
Yeah, yeah. That's what I mean.




**Michael Sofaer:**
It definitely has nothing to do with what is the best design.



**Jae Kwon:**
Yeah. So we so we agree we need bottom up innovation and and I think we also agree in practice we really need the cosmos have to be an authority. So. So I guess you know the way we get there is we have a, we have a plan.
You know a multi year plan with maybe in phases where we say for a name system you know we're going to, we're going to take all the ones that exist at this date evaluate them and see and and create a survey report right and then try to see you know see what we can recommend to get to the community to adopt the problem is.
The problem is.
The Cosmos hub should represent everyone, including groups.
That are.
Technically and philosophically opposed to each other. So we'll never.
Right. So I think, I think the answer has to include different groups, autonomous groups.



**Michael Sofaer:**
I mean, look, there's nothing wrong with having competing name servers, right? And I do think there's, I think there's.
Destroys a very large amount of usability and capacity for adoption. And like I'm like I'm very adoption focused or adoption is like my.
Like driving force like I'm you know if I have to choose between on my project which is not trying to be like a finance project it's like a little it's much more of like a toy project but like you know I'm I'm always going to pick adoption over like pure decentralization because I wanted to get used that that's so to me like yeah there's a lot of eventually occasionally like if there's going to be a name service on the hub the hub is going to have to make decisions about who gets a name because
Now it has to be in order for the thing to like be have to look coherent to someone coming in, trying to use this system, coming out of traditional banking, trying to use this system and then being like, oh, well, you know, what's a routing number? I'm supposed to go to Bank of, you know, I'm supposed to send something to Bank of Chile. Well, you know which ones really Bank of Chile. There's like 6 chains with six different routing and routing numbers, right. And like.
We just that's just not going to that's just not going to get adopted. And so I don't know I mean I think if the plan is like we're going to you know to me ICS is an implementation detail here and my suspicion is that it makes it harder. Like it's actually probably easier to put a name service on like in go directly on the chain then it would be to use ICS to do it. I don't know that doesn't mean it's a it's bad. It's just like it's an implementation detail and like the core of it is like do we
Tokens and these are these are there like you know here's how you find their validator sets and like this is how you get hooked up with the with the cosmos right at like a core level come to us and we'll tell you like all the changes a lot of usage and how you get hooked up and you won't get scammed and if you're building a wallet come to us and we'll get you know you don't no one has an advantage building a wallet and like which chain is where you know and and if you want to find like.
If you want to find Sunny, this is Sunny. You know this is how you can reach him. And it won't be someone pretending to be him on Twitter, right? Like all of these.

**Jae Kwon:**
Yeah, OK. But..
Don't we agree though, that the reason why name service hasn't really won out? It's generally because a lot of them fail in the implementation front. They're just not.
Rich enough to account for all the things, and especially they're not good at moderating right and and they're not provably fair or they're not fair enough or they're not fair enough over a variety of reasons. You know what, why, why is it?



**Michael Sofaer:**
I don't think any of them has failed for not being fair enough that that hasn't happened. The ones that like, you know, no one uses like Starname, right? Not for that reason. The ones that people use. The main name services that people use are Kepler and Sonny's GitHub.
And I think they use them because they basically are correct.
That's sort of it, right?



**Jae Kwon:**
I don't know what you mean. It's not. It's not a name resolution system on chain.


**Michael Sofaer:**
no it's not there isn't one on chain right and i just think that's a problem
No, it's not. There isn't one on chain, right? And I just think that's a problem. I just think that's a problem. And like.


**Jae Kwon:**
Yeah. So, OK, we will. Yeah, it doesn't exist, I say because we don't have the right programming paradigm. I honestly think that a name, a good name resolution system really does require quite a bit of complexity to build and that and our tools are not good enough for us to do this.
Well.
I really think that. Um um.
You know, like like if we were Ethereum we would have had multiple good approaches by now possibly, but like even solidity has issues too. I really think this is a tooling problem.



**Michael Sofaer:**
OK. I mean that that's actually a really optimistic view. So I appreciate hearing that.



**Jae Kwon:**
Yeah well and you know an example would be we also need to implement like a ticketing system. You know people are going to have to raise issues about oh I need this name because like I should because it was a mistake or you know it was it was stolen or you know and and and and look at the smart contract here there was a bug or you know like we really do I think a name resolution doesn't should try to account for.
such issues to arise and that requires a whole set of tooling we don't even we haven't even begun to build for blockchains, right? But if we if we if it was easier to just upload a feature.
To to enable it, and it was permissionless. I think it would happen really quickly.


**Michael Sofaer:**
That makes a lot. That makes a lot of sense if you think about it as like a problem of sort of like.
Having being able to have a Dow that's capable of being like, uh, you know, being able to sort of like say, oh, this person actually took someone else's name for nefarious purposes and we're not going to let that happen kind of thing like.
Yeah, we don't really have the tooling for that.



**Jae Kwon:**
Yeah. And and if there was a system that was working, then it would prove itself because people would say, Oh yeah, the system, you know, it, it, it responded to my needs and I believe in it, you know, and yeah.


**𝔟𝔲𝔩𝔩𝔦𝔰𝔥𝔦𝔱𝔱𝔢𝔯:**
Can I?


**Jae Kwon:**
Huh. Yeah, please.
Please go ahead.


**𝔟𝔲𝔩𝔩𝔦𝔰𝔥𝔦𝔱𝔱𝔢𝔯:**
I like this conversation a lot. I think I'm going to just throw in a possible solution.
Xbox's done this and also discord does this.
Where it gives everyone their original name, but then there's a string of numbers at the end so you can have your original go to tag within an ecosystem.
But then it has a string of numbers attached to it.
So it it kind of solves both problems. Well, it's steps. It's a big step over the whole impersonation problem, but I feel like that's a.
Like, that's a problem that's just going to exist, period. It wasn't solved in web two. I don't think it's necessarily going to be solved in Web 3.
But I actually have two other things that I have that I wanted to ask.


**Jae Kwon:**
Can I respond to that? First, just wanted to say thank you. I feel like that'll work in a situation like discord where you know, most you might have like 10,000 people.



**𝔟𝔲𝔩𝔩𝔦𝔰𝔥𝔦𝔱𝔱𝔢𝔯:**
no go ahead thank you


**Jae Kwon:**
But but like I don't think it would work.
In something like an open space like Twitter.
Cause, cause and cause every.
Important person people wanna spoof is gonna have.

What, 10,000 look alikes?
Umm.
But yeah, that's that. That was my point.


**𝔟𝔲𝔩𝔩𝔦𝔰𝔥𝔦𝔱𝔱𝔢𝔯:**
OK, well, do you mind if I ask?
two other questions


**Jae Kwon:**
Yes, please. Yeah.


**𝔟𝔲𝔩𝔩𝔦𝔰𝔥𝔦𝔱𝔱𝔢𝔯:**
to two other questions L1 really
To two other Questions, L1’s a really important one and one I just.
more of a it's a it's a news related question.

Like other L1s and and L2s and etcetera that's going on on Cosmos. Like how how important is the hub or can can these parties like I'm I'm sort of anti hub and idealism when I think about Cosmos I'm comparing it directly to Ethereum and Ethereum doesn't have to like.
Not, not not flooding or anything, but they don't have to stop so low and like.
My point of view.
I think everyone here is valuable as a builder, but Jae, you're the creator of it that.
The entire point of why Ethereum has gone so well is because Vitalik somehow hold held onto the like the roller coaster until he still remained at the top. So the vision is clear. But like that didn't that happened through like.
Like there was so many possibilities of that not being true. It's only by pure luck and chance that things have become this way. And when I look at what I know about the cosmos story so far, it's like an uglier version of this, of of a similar story. And from that point of view, I feel like it has the potential to even be just as good, if not better. Because if we could just, if we could just step away from like the hub concept.
And have trust and very like get to do away with trust and start with verification.
Maybe a better ecosystem could be built. Instead of trying to just, you know, gouge the Treasury and give it to cool guys, you tell me what you.
maybe a better ecosystem could be built instead of trying to just you know gouge the treasury and give us a cool guys you tell me what you think



**Jae Kwon:**
But I I think the the way Ethereum went and the way Cosmos went was by design.
By geopolitical actors and it couldn't have gone any other way.
I honestly believe that I think this project has been subverted.
From early days you know and we've we've we're.
from early days you know and we've we've worked
The key people in here are being handled by geopolitical handlers that also handle people and Ethereum and so on.
You know, because the world is actually run.
By.
You know, some other system that wants to stay in the dark.


**𝔟𝔲𝔩𝔩𝔦𝔰𝔥𝔦𝔱𝔱𝔢𝔯:**
I understand that totally. Is there any way that you can then insert that by design by?
Like how, like, I just want to reiterate my question, how important is the ATOM hub to the rest of the cosmos ecosystem powered by Tendermint, which you are a part of? You are. How important is that in that treasury to everything else that is going on?


**Jae Kwon:**

I think it's important that this ecosystem gets a hub that I'm describing that is not created by.
By…Special interests, let's say.


**𝔟𝔲𝔩𝔩𝔦𝔰𝔥𝔦𝔱𝔱𝔢𝔯:**
This would have to be ATOM.



**Jae Kwon:**
OK.
yeah i think it has to be the ATOM from this ecosystem absolutely i think



**𝔟𝔲𝔩𝔩𝔦𝔰𝔥𝔦𝔱𝔱𝔢𝔯:**
Please tell me why?

**Jae Kwon:**
Yeah, I think it has to be the atom from from this ecosystem. Absolutely. I think just about every other. It has to be an atom. It has to be the atom or fork of the atom. OK.
Because.
We all find, you know, I suspect that everything else is is is gained some other way and it’s not gonna have the legitimacy. With all the political infighting that's been going on Cosmos ecosystem, I still believe that the ATOM token is the token from which we should derive the hub.
And whether it's the Cosmos hub itself or or some fork of it.
OK. And I think that's the story from the get go for any hub token.
Alright, it's it's going to be.
It's going to be contentious.
It's going to get attacked. We're going to have to create many forks.
And and embrace this diversity that comes from it.
In order to stay anti-fragile enough against what we're up against.
Um, so, so I'm not going to, not going to change that.
Alright.
So it doesn't matter.
That the Cosmos hub is subverted or that, you know, people are trying to take it places it shouldn't go according to, you know, this particular perspective because and the ATOM Token is the token.
This was the place where we, you know, created.
The tooling for the Cosmos ecosystem we solved proof of stake first.
You know we solved IBC.
And we're going to solve ICS.



And we have a kickass smart contract system. You know, it doesn't matter what happens this, this ecosystem is going to make it out alive. We're going to make it right. And it's just a matter of how we get there. So it doesn't have to be this hub, but some hub needs to.
Provide these services of ICS and, you know, minimal hub for the ecosystem because we're going to need it. We're simply going to need it in the future. There's no way around it.
And we don't, we're also going to need many hubs too. We're going to need a regional hubs. We need hubs with different policies on you know, this or that. We need many hubs and many of them, not all of them are going to be derived from the out of token.


**𝔟𝔲𝔩𝔩𝔦𝔰𝔥𝔦𝔱𝔱𝔢𝔯:**
can i ask you one last question?



**Jae Kwon:**
Sure. Yeah, go ahead.



**𝔟𝔲𝔩𝔩𝔦𝔰𝔥𝔦𝔱𝔱𝔢𝔯:**
Can I ask you one last question? Appreciate you. Your answers have been great. Is there any way that I could grab you for an interview on the history of Cosmos and sometime in the future?


**Jae Kwon:**
we can we can go offline but i you know i don't know who


**𝔟𝔲𝔩𝔩𝔦𝔰𝔥𝔦𝔱𝔱𝔢𝔯:**
Definitely.


**Jae Kwon:**
We can, we can go offline. But I, you know, I don't know who, who are you?



**𝔟𝔲𝔩𝔩𝔦𝔰𝔥𝔦𝔱𝔱𝔢𝔯:**
I don't mind talking to you at all though.
I'm not gonna do it here, but definitely offline.


**Jae Kwon:**
OK. Yeah.
Yeah. Thank you for your questions.
Adding asset Cowboy to a speaker for talk if you want, but also there's someone raised their hand.



**Ghazni:**
Hi, Jae. So my question is regarding ICS and how do we like ensure that the marginal value data, let's say the rank 150 or 160 validator is not like forced into validating a chain. How do we ensure that since they will be validating multiple chains, so they are forced into like they have to validate it because they want to be the cosmos validator. So are we going to ensure that they are actually profitable in validating these chains?




**Jae Kwon:**
Hey, that's a great question. There's a bit of feedback here. OK, we'll solve that.
yeah well so i'm not exactly sure how this is gonna workout be honest but that's also what i've been thinking about on and off

And it should be that way, right? The problem right now the biggest problem I see is that the validator rewards for.
Running ICS.
Needs to be defined so that the the rewards, transaction fees or any rewards for validating that chain should be shared more equally with all the validators.
Perhaps completely equally, because everyone you know, ideally every one of these validators are secure.
Right.
So I I really do think that there needs to be some evening like like equalizing factor when it comes to validator rewards and I think the current reward system is too skewed to be to be.
Umm.
something stable in the long run with ICS i think we with ICS we're gonna need to figure out ways to spread that out more evenly in order for validators to get the



**Ghazni:**
Years to get the, you know. But then this also raises the question.



**Jae Kwon** 
something stable in the long run with ICS i think we with ICS we're gonna need to figure out ways to spread that out more evenly in order for validators to get the you know but then this also raises the question yeah sorry am i interrupting you
Something stable in the long run with ICS. I think we with ICS, we're going to need to figure out ways to spread that out more evenly in order for validators to get the, you know. But then this also raises the question, yeah, sorry, am I interrupting you?



**Ghazni:**
No, no, go ahead.
What is? What is your boundary? Doesn't want to, sorry.



**Jae Kwon:**
What if, you don't want to participate in an ICS system for the hub that where you know maybe in in in five years there might be 100 chains. You know, maybe you don't want to invest in that infrastructure, maybe that's not the business you want to get into.
You know, and it could be the case that the Cosmos hub, most of the validators or the atom holders don't want this to be on that hub.
Right. And and and maybe this will come. This would be an issue primarily coming from the validators. It really depends on how many validators or for top value, there's really want to get into this particular type of business where they have to scale by having you know data center infrastructure. I know that some validators are like simply VC based out of Malta. They they they bought a data Center for this purpose, right. And a lot of values are already validating many chains.
Right.
But anyways, going back to your original question.
It should be profitable and you you should want to.

Participate.



**Ghazni:**
Do you think that even MEV rewards should be equalized? So for scheduler since we are going to distribute MEV based on who is winning the block. So do you think I mean we also needs to be like?
Distributed among equally among validators.



**Jae Kwon:**
Second, well, I'll just, I'll just try to answer that and let me know if I'm answering it. I think that you know.
Perhaps one way to solve this is to say for all the ICC zones.
There's there's a there's a base like almost like a universal basic income for each validator so that they can afford, you know, all the infrastructure and upkeep for that particular zone.
Right.




**Ghazni:**
My question was regarding the centralizing force of MEV. So let's say the top validators, they will gain more from MEV and they will be incentivized to gain and get more power.
So should we like?
Distribute the MEV rewards from scheduler equally among the valid validators should it be distributed with respect to voting power.
because then again if we distribute it equally, then the top validators have an incentive to civil validator set, right?
 

**Jae Kwon:**
I don't know. I think every MEV situation is different. So it would have to look at the particulars of of the of the way their values extracted. I mean, if you're, if you're.
You know, here's an example. OK if you're.
If all the valid, if none of the validators colluding or using some MEV protocol, but they're all individually rearranging their transactions in their blocks like, OK, that seems like a quite unfair way to redistribute MEV. But you know what? What other system are we talking about here?




**Ghazni:**
OK, thanks. One last one, it's not like a question but a general comment. So I see liquids taking similar to like older banking system wherein you deposited gold and you got a note saying from the bank saying that OK, you have deposited gold with us. So I see some similarities with liquids checking as well. You deposit your asset and you get a derivative that OK, we have this asset. So similar to the older banking system where in the.
Invention of nodes like open new opportunities. Similarly liquid stacking is also going to open new opportunity and similarly since the older banking system had some flaws and led to corruption leading to fractional banking. Similarly we also will have something similar on liquid staking right? Because since liquid staking tokens are already issued and if the base currency which is deposited is getting slashed.
So there is a similar situation to fractional banking at least. So at least we have an on chain mechanism where wherein we can see that OK this slashes happened and we can reduce the value of that liquid state token. So should we like.
Ban liquids taking or go too hard on it? Or should we like, promote it because it is going to open new opportunities?



**Jae Kwon:**
Well, I I don't think it opens new opportunities in that regard because you know.
You know, there's there's similarities here for sure. I see the similarities like when you put gold in a particular gold vault.
That gold vault may get slashed or not, you know, and so your paper receipt for that vault may or may not go through. And I get it, but people needed this because there was, you know, this this this horrible slashing system, unnecessary slashing system, so to speak.
Because slashing general is horrible. Exists because it was still better than holding the gold.
And and and and transacting with the gold.
And also it turned out history shows us that it was flawed and ultimately it led through systemic, systemic failure. So we should, you know, if anything it teaches us we have to be careful about how to implement it. But but more so, I guess the point is we don't.
We don't, you know, and even in the Cosmos hub we the the system we're using a delegation and slashing of the, you know, it's, it's not solving the same problem.
You know all the tokens are fungible. You don't need a. You don't need to put them in a vault.
You don't need to give anyone.
In general.
Skin over your tokens. The only thing it's doing here is it's um.
It's it's being used, yeah.
But you know, I I don't think it's solving the same problem and therefore it doesn't quite have the same. Like the analogy is kind of flawed that way. It's like comparing apples to oranges.



**Ghazni:**
OK


**Jae Kwon:**
So, you know, in other words, here's another thing like in, just as an example like.
Yeah. So. So first of all, we we don't even have the same kind of problem in general in this space in crypto, because we don't need to put gold in a vault, right?
umm yeah so so first of all we we don't even have the same kind of problem in general in this space in crypto because we don't need to put gold in a vault right
But also this the problem that we're trying to solve here has limited utility. It can't. The utility here can't be as big.
As the utility of.
Dematerializing gold?
Because the utility here is limited to.
Providing value.
Of providing liquidity in limited cases.
During the three-week Unbonding period, it's just it's like much marginal compared to the original thing, you know?
So I don't think it's gonna open.
That many opportunities and it shouldn't. And if it does, something's wrong and something will fail because of the issues I've mentioned before about the systemic risk of liquid staking.



**Ghazni:**
Yeah. Thank you.


**Jae Kwon:**
Cool analogy though.
Mindbender.


## Side B

**CryptoCowboy:**
Hey, Jae.



**Jae Kwon:**
Hi.



**CryptoCowboy:**
I actually ironically think that the issue with liquid staking the relative analogy would be closer to 2008 financial crisis where you derivatives and4 mortgages on mortgages and that's really where you had a secured mortgage that you were taking equity out of and driving derivative products.
That's why liquid staking shouldn't be in a secure hub. Like to your point and on you the for this that that the original staking is to secure the network. Period. End of story. If we run financial derivative products, they need to be outside of the secure hub.
And have no problem running you know derivatives on on other coins or other products but it should not be in in compromising and again doing paper on paper type of financial products that we've already seen in macro scales completely fold.



**Jae Kwon:**
Yeah. Thank you for that.
So.
it is it is a lot like
Or committing to particular.
I guess structure, I don't know. Some commitment.
And then?
And then the liquid staking tokens are kind of like derivatives of that house.
Based on mortgage and so on. And then if the building burns down then.
Yeah.



**CryptoCowboy:**
That's it. And then you have this this collapse, right? And it it it's literally no, it's a derivative product. That's what liquid's taking is.



**Jae Kwon:**
Uh-huh.



**CryptoCowboy:**
and derivatives are not a problem if done in a correct isolated box, right? They're just a product. But when they're built on top of something that is meant to be a foundation.
and you start and then you do multiple layers of it because that's what ends up happening financial products as you get derivatives on derivatives that's what the collapse is and so when



**Jae Kwon:**
Yeah.



**CryptoCowboy:**
and you start and then you do multiple layers of it because that's what ends up happening financial products as you get derivatives on derivatives that's what the collapse is and so when we saw this
And you start and then you do multiple layers of it because that's what ends up happening, financial products, as you get derivatives on derivatives, that's what the collapse is. And so when we saw this, I was like, we're literally building the same thing from a financial instrument over here. This is a fundamental problem. And to your point, you called it out, which is perfect. That's not what the intent was.
Staking it was not to make a derivative product a financial instrument.
Its purpose was to secure a decentralized network.

it's it's funny i think a lot of people are like well we're not quite sure of the ramifications of liquid staking and and i actually argue i think we know exactly what they are they they there are different term for a very old financial product of derivatives and we've seen how that has worked out and and worked out in a much more stable what we would what we would consider non speculative and stable economy
It's it's funny I think a lot of people are like well we're not quite sure of the ramifications of liquid staking and and I actually argue I think we know exactly what they are they they there are different term for a very old financial product of derivatives and we've seen how that has worked out and and worked out in a much more stable what we would what we would consider a non speculative and stable economy and look what it did.



**Jae Kwon:**
Yeah.
My thesis for the past, for the 08 crisis, which, by the way, ripped through, you know.
of my life in one form



**CryptoCowboy:**
Hmm.



**Jae Kwon:**
Of my life in one form it.
It seemed to almost have been intentionally designed.
Like, you know, it seems like these crises are kind of manufactured, and they come every ten years or so.



**CryptoCowboy:**
Kind of.



**Jae Kwon:**
You know.
You know, OK, alright, I, you know, I I think there's good reason to believe that's what's happening and do you believe do you believe that's true and and do you think?
you know maybe maybe there are elements of that in liquid staking in the crypto in cosmos ecosystem like



**CryptoCowboy:**
Without a doubt.



**Jae Kwon:**
You know, maybe, maybe there are elements of that in liquid staking in the crypto and cosmos ecosystem, like that's why.



**CryptoCowboy:**
What with 100% without a doubt.

**Jae Kwon:**
OK, yeah. So it's not just me. Yeah, really think liquid staking is being pushed systematically by some actors in order to create the conditions for.
Um, for destruction.



**CryptoCowboy:**
Instability, correct.



**Jae Kwon:**
instability



**CryptoCowboy:**
instability correct yep
Yep, Yep.



**Jae Kwon:**
Instability, chaos, so that they can come out.
On top with order.



**CryptoCowboy:**
Yep.



**Jae Kwon:**
Yeah, and it's like this.



**CryptoCowboy:**
And that's why I'm saying like I'm I'm not fundamentally against the instrument of let's say liquid staking or even derivatives just put it in a box right and and have it run so that it doesn't affect the entire let's say ecosystem and or you know interchange the term economy either way.
allow that derivative product to run on its own and not be again upholding an entire economy or ecosystem that could come down but without a doubt O eight was was one i mean just look at the transfer of of wealth what Blackrock did in terms of of buying up and a transfer of private homes into funds like it's pretty clear what ended up happening and the same people that created it were also the same benefit biggest benefactors that isn't coincidence
Allow that derivative product to run on its own and not be again upholding an entire economy or ecosystem that could come down. But without a doubt, O eight was was one. I mean just look at the transfer of of wealth like what BlackRock did in terms of of buying up and a transfer of private homes into funds. Like it's pretty clear what ended up happening. And the same people that created it were also the same benefit biggest benefactors. That isn't coincidence.



**Jae Kwon:**
Yeah.
Yeah.


**CryptoCowboy:**
But I just, I really wanted to honor you. I wanted to give you that analogy and then honor you for holding true and say like look security if we if we are not securing the network.
Then what are we doing?
Right, if we have a network that can just.

Crumble them then why are we, why are we building what we're building? Why are we moving forward these ideologies if if we're creating instability at the same time? So I thank you for pushing back so much on liquid staking towards the hub at least.



**Jae Kwon:**
Thank you.



**MadMan:**
And I'd like to thank you too for you know, for bringing those points up. I I think it was well articulated. I appreciate that.

And and also use it as an as a way to incentivize creation of good tooling that fits specification you know.
Maybe we do want a bit of liquid staking.
Because I can see the utility in that sometimes, you know, like.
As long as there isn't.
As long as there isn't.
Too much emphasis on the secondary derivatives market.
Right. And it's, it's used for its utility which is to you know, to unbond faster with some penalty is how I would call it.
When conditions are OK, right?



**CryptoCowboy:**
Yeah, I think what you have to do. Everything in our world comes with a risk profile.
And and I think as long as you have thought through the risk profile and put a Max, you know what whatever that is and you've written it into the governance that only X percentage of state tokens can be in a secondary derivative or liquid staking market and therefore the caucus clearly shown that.
You can't. You're not creating any sense of a collapse. Absolutely. I I think you can provide freedom to financial instruments that way. And I'm actually, I'm.
An advocate for it, it's just you can't be at the compromise of the entire ecosystem, right. So I think you do one or two things, you allow a certain risk profile portion to be able to put into secondary markets and liquid staking or you move it into an isolated box in itself, run it much more like an.
I don't know. I'm not sure exactly. I've taught my head how you do it on a secondary I I think you probably focus on the risk profile of how much you're going to allow for the original staked amount to be in a liquid staking environment and all that can be managed on chain and your risk profile can be algorithmically managed as well real time.

Um, and so then you have, I guess, some of both worlds. Jae to your point.



**Jae Kwon:**
Yeah, I, I guess, you know, I, I wouldn't mind if the Cosmos hub just banned liquids taken entirely and just said, you know, you can't, you can't speak through ICA, you know



**CryptoCowboy:**
Yeah.



**Jae Kwon:**
Yeah. Yeah because because I honestly think I see the Cosmos hub and say no we want liquid steak and give us liquid staking. You know and and and then and then we go huh. You know we're not doesn't feel secure. We kind of want a minimal hub that doesn't have liquid staking now right. So yeah I do agree with you. You know I do think we need a minimal hub that doesn't compromise. We need to have at least one and and and.
I feel like we should, we should be celebrating this diversity, not not feeling like it's it's a bad thing, you know?



**CryptoCowboy:**
Well, I feel like anyone who's building an app and building value on top of an ecosystem, just like building a house, you want a firm foundation.



**Jae Kwon:**
Hmm.



**CryptoCowboy:**
We all should be concerned about that, that we're building something on, on, on something that isn't firm. And here we are putting so much time and effort into creating value on something that could just collapse. That's not good for anybody. Like like we look at the devastation on any of our collapses that we've seen, right? And so if we can.
Foresee that that's a possibility to mitigate against it, then why wouldn't we be doing that?

Thanks, Jae.



**Jae Kwon:**
Thank you.
Um.
So how do we start? You know, I do think we need to start with.
Several proposals for a Constitution that lays it out and says why.
And Thursday, Adam one. But it's it's, I honestly think the ATOM 1.0 Constitution should be split into two, into one you know?
So we take out the photon token entirely, and then.
Um, take out the photons and then flush it out a little better. And I think we have a good start for a minimal Constitution, and I'm kind of waiting for people to.
Hinting people to fork.
Fork it and and and for us to create.
Many alternatives. One thing I noticed the other day is that if we have ICS.
It it shouldn't be hard to create an application.
That.
Auto stakes.
Atoms just automatically sticks atoms across the board, according to the you know.
The ratios and then forwards all rewards pretty much.
Or or some of the rewards.
You know mine. You know at least all the transaction fees to the validators.
OK, so in other words, if we have ICS, we can.
What I'm saying is the photon that was proposed in Atom one is going to happen automatically because people are going to want to.
People are gonna want to.
Autostake.
Because and it would be easy because someone wrote that application and you'll know it's secured because it's running. You know and and and and there. If you tokenize the auto staked atoms, you have photon, you have a, you have a, you have basically a.
Deflationary token and not exactly like what's in that one, but anyways so it's inevitable that we're gonna have a multi token system.
Anyways, moving on.



**Ian Clausen:**
Hey, Jae, quick, quick question kind of in that line that I'd written down earlier, but.
Does this group have any ideas about how to get like individuals that aren't validators to to be more involved in the voting process instead of just defaulting to whatever the validator has set when when proposals come up?
Because I think that also contributes to the fact that we, you know, was stated earlier around some of the validators being quote UN quote whales within the system. Well, that's just exacerbated by the fact of individuals not participating. But I also know that, you know, we've got to.
Asking so much of an individual to be so involved at different levels can be difficult as well. So just any ideas around how that might happen? And I bring it up because in the context of what you just said, if we are auto staking all of a sudden, if that's happening for me automatically, I'm I feel like I'm probably even less likely to get involved in governance.



**Jae Kwon:**
Hmm.
Yeah, yeah. I mean, OK, let's talk about this. So.
Umm.
From a governance point of view.
I'm going to want I want to delegate to people, not validators. I want to be able to delegate to anyone.
So that when I'm not actively voting because I can't say I know, I know some someone or some Dow has my back and voting and I trust them to vote. Maybe, you know, and maybe there's some penalty for delegating it this way perhaps or whatever. But like you know, so maybe my vote is not 100% but but I fully believe we'll have better signal this way.
So isn't that like kind of like liquid democracy? Except this is obviously not a democracy, it's more of a capitalistic voting system. But it's a liquid voting system. What if we what if we implemented?
And had some experiments like an implementation in GO and GNO and and in CosmWasm.
That and and we try to see what system works for us for liquid delegations.
So, so I can imagine wanting to.
Wanting to auto stake for simplicity's sake because I don't know, say, right?
Um.
But.
Yeah, knowing that, my vote will go towards, you know.
An outcome that I would I would agree with.

**Ian Clausen:**
Yeah, I mean that gets super better because maybe I want to set my governance preferences before I let it auto stake such that maybe I fall in line with a with a validator that's, you know, thinks the way that I think, right?
Umm.
But I think auto thinking is also interesting because it would probably diversify.
Where people stake, right? Like you can algorithmically manage to have the validators more balanced as a set than, you know, folks just picking at the top of the list, or, you know, based on Commission or whatever. You know all the other reasons.
I mean, if we're honest, everybody's looking to make the most money at this point. Probably, you know, like and and less about.
Whatever the validator is said about how they're going to vote.



**Jae Kwon:**
Hmm.
Yeah, yeah. I think we can do a better job. Well, you know, the auto-stake.
Yeah.
That's, you know, it's just a lot of design space here, so it's probably gonna be.
Little tricky.
To get right. But yeah, it'll probably happen anyway, so we should get ahead of it.
And, and I think though that some of this should so the auto staking system does have some power because it can propose an equalizer system for validator payments. But I really do think we should.
We should take that into the Constitution.
You know to say that validators are going to get some minimum pay to cover.
They're their infrastructure expenses.
And and.
And specify what that algorithm is.


**Ian Clausen:**
Yeah. And we've seen that I think in in on other chains, right, where there's caps about how much you can have bonded or staked as a validator, right, which then forces, you know, new folks that are coming to players. I don't know if that is the solution, but something like that could be written into the Constitution.



**Jae Kwon:**
Hmm. Yeah, yeah.
And, you know, I'm sure we'll have. Yeah.
Validators need to be.
independent and if they are affiliated with another validator in some way they have to disclose it so on yeah all that needs to be kind of written
Independent and if they are affiliated with another validator in some way, they have to disclose it. So on. Yeah, all that needs to be kind of written down somewhere.



**Ian Clausen:**
yeah that all
Yeah, that all, yeah.



**Ian Clausen:**
I think that's a whole another ball of wax, that kind of KYC validators at that level, right? Or, you know.
Yeah.



**Jae Kwon:**

I don't know. I think that OK, we're not trying to solve the general KYC problem here. We're just trying to see who the, the, the validators are. I think it's fair to say the validators who are accepting delegations should identify themselves.
And, and I think the Constitution is where we should add clauses like, you know, you have to disclose your affiliations or associations with other validators. So we know you're not like, you know, smurfing us or whatever.

**stakepile:**
Can I jump in here for a quick thought?



**Jae Kwon:**
Yeah, stakepile.



**stakepile:**
Since we're on this topic of you know, governance, what about the kind of structuring it's similar to how you know US congresses were validators would be capped at like a Senate system where you know let's say there are 100 validators each would be capped to like one vote and then the other tier where delegators are like you know the the House of Representatives where their.
Votes are are, you know just yeah, they're not pegged to a certain validator. So like their votes, whoever votes will be counted and you know if 50% voted that's so be it, that's 50% out of 100 or you know if 30% voted you know that's 30% out of 100. You know, total percent that's voted and that's not pegged to a validator vote.



**Jae Kwon:**
Yeah, that's that's a good thought. Just don't have representation altogether.
Right, just direct phoning only.
We'll have to change our quorum quite a bit.



**stakepile:**
right



**Jae Kwon:**
Yeah.
And. And we don't know exactly what that should be.
But.
I think that's a good way, you know, I.
Umm.
I still think.



**CryptoCowboy:**
Jae, this could be a good experiment for another hub.



**Jae Kwon:**
ohh the minimal hub where there's no delegation



**CryptoCowboy:**
Yeah.

**Jae Kwon:**
Have more of an expectation of direct participation, right? The nice thing about having delegations is is I think it might actually represent the token holders better.
if we do it right



**CryptoCowboy:**
Hmm.



**Jae Kwon:**
If we do it right then only having only having direct participation like like.
I do think we can get better signal.
If we can delegate to people we trust to to analyze a proposal.
Then, you know, and if we can do that, if there's anyone we can trust who's gonna do the work anyways, and we were gonna agree with them, it would solve it. It would. It would free up a lot of mental space for all the participants.
Rather, if everyone had to vote individually.
And that was the expectation all the time. It's almost like we're raising, we're raising the the amount of joint.
Focus we have to put into every single proposal.



**CryptoCowboy:**
Yep.
Yeah, I don't know that this is the answer, but it's, you know, just trying to draw correlations here. It's similar to once again U.S. government House and Senate and and I kind of cringe when I even say that because of the bureaucracy, but.
What it allows for do is one side is proposing and the other side is is approving.
And so that's what I meant by a tiered system, if there's something to get it much more efficient on, and maybe this goes into some of the constitutional governance on some more structure on what is proposed. So we don't have such a.
High influx of things that aren't relative. I'm I'm not sure, but if you had some way to make sure that the proposals were elevated and then to your point you're you're not drowning people in.
Votes or things to read through that are of low relevance. You elevate the proposals up to elevate engagement at the same time to make sure the community is getting what's important in front of them and and at that point they know that it's really important for them to vote. Like what is being brought forward is is of substance.



**Jae Kwon:**
Hmm.
Can we can we do that? There's quorums, so adjusting having a dynamic quorum system that ensures that only.
You know.
The right number of proposals come into focus because they passed a quorum and then that's the bar where after everyone should take a look.



**CryptoCowboy:**
Yeah, I, I love that. And especially I think if you could get to a point of where that quorum was.
You know.
I again I'm I'm gonna I'm trying not to to bring in our U.S. government too much but it's kind of something that that a lot of us are are familiar with and and so like if those seats have quorum or voted on by the the Community right they were elected individuals for representation and maybe if you wanted to get into a point where everyone's speaking about terms right and so there's there's terms of that Council.
That they have a a specific lot of time and then people get re, you know termed in.
I think they could be really interesting, but I think that's where you're driving efficiency and proposals, you're driving structure. You're adhering to much more governance, which is only going to, as long as it's done correctly, it's only going to allow for the community to scale much more efficiently together.


**Jae Kwon:**
Yeah.
And yet, if it's going to be on the minimal hub, it has to be some minimal system.



**CryptoCowboy:**
Yeah, totally, yes. Can't get away from that term.



**Jae Kwon:**
Yeah.

**CryptoCowboy:**
I'll think through more of the quorum concept, Jay. I think it's really it, it's strong. You know, we've been thinking through it on our side for a while and and have some some more deeper thoughts around it. But I think I think there's something there. There's a lot of nuance in the design that needs to be thought through and your term of again game theory and subversion always has to be at the forefront when you're designing something like that, but.
I do think that's how you start to take the whole ecosystem to the next.
Level.



**Jae Kwon:**
Hmm.
I imagine.
Imagine.
Ohh yeah we can take a look at historic performance of yeah how many people are voting directly without delegation to get the right figure for the quorum amount.
And then..
As long as, as long as the system is. Yeah, yeah, we could probably solve this in a systematic way. Like there could be a heartbeat. You know, like maybe. And once a year everyone has to vote just yes on this thing, you know, just to get.
Adjust that amount, that quorum amount or something.
Umm.
OK.
But, but I think the common thing here is that, we kind of want to try and experiment where we.
The validated delegations in governance as much.
If at all.
No.

We talked about equalizing validator pay, which we'll need to do for an ICS system.
Different ways to do that.
Um.
Next time we have this call, I think we can have.
More smart contract developers.
On the call and we can focus more on that topic.
I think next week is the holidays, but maybe when we come back from the New Year we can have another call like this.



**MadMan:**
I would love that.



**Jae Kwon:**
Alright.
Right.
Um, so the next call, the decent next Decentralist, round table or town hall, whatever we're calling this.
Will be probably on smart contracts and ICS we can talk about liquid staking too we can have this kind of conversation we'll try to get more developers on the call especially from CosmoWasm and EVMOS so please please invite people to join
And we'll make an announcement about the date sometime in the next few days and schedule it for next year.
Early next year.
Have.
You know.
Happy holidays and Merry Christmas.
And hope you all have a wonderful end of the year and happy New Year.

Thank you all for coming.



**MadMan:**
Thank you.



**Adriana:**
Thank you all and thank you, Jae.



**Jae Kwon:**
Thank you all for conversations. Bye, bye.

----------------------------------------
transcribed by @johnniecosmos
