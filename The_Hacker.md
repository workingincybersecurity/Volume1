# The Hacker

*Both professional and amateur students of computer science and security relish the label “hacker” and grimace at its more commonly understood definition as someone who acts with malicious intent. Stephen Watt has experience operating in both worlds, having gotten his start in the field because of a sense of curiosity, and later serving time for tangentially being a part of a cybercrime scheme.*

My current employer is Farsight Security, Paul Vixie‘s  company. I’ve been here a little more than a year.  We’re a remote company, meaning that we have a headquarters in California, and we try to do a couple of off-sites once or twice a year to have some face time, but essentially everybody works from home from around the U.S., Canada, and overseas. 

**So how did you first get involved in security?**

I was hanging out in IRC  in the late ‘90s. I wasn’t necessarily doing anything with a security bent, although it was technical, in general. I was doing some development and hanging out in some chat rooms, and then read some stories about people who had been in the news for hacking this or that, and saw that they were associated with certain channels in IRC that were casually mentioned in news articles. So, I went into those channels and started hanging out.

Looking back, everybody was a script kiddie, although when you’re starting out, you know, nothing seems really lame, and everything is new and interesting. So that was my first introduction to the scene. IRC was the center of my world, as far as security goes. I was pretty active on there. The entire time I was actually involved in security projects, and it’s kind of where I started and stayed for the most part. I definitely did more of my socialization through IRC than I ever did at conferences or local meetings or things like that. 

**Did you go to school to study this stuff, or are your skills self-taught?**

Definitely self-taught. I actually went to school. I started out in computer science and ended up getting a degree in philosophy, for precisely the reason that I already knew what I was doing, and going through the computer science curriculum was very painful. It was a combination of relearning things that I already knew, and having these other issues that I didn’t know pitched to me as something essential like, “Oh, you have to take this Discrete Mathematics class because if you don’t, you’ll never know how to use data structures or optimize your algorithm.” And I knew full well that I could write good code using an intuitive process. I didn’t need formalized processes; I knew I could play with the code and intuitively rewrite it and benchmark it until it was as fast as possible, and I knew that this approach worked in a real-world environment. 

I also didn’t like that I would get penalized for doing things differently. I lost points on a test once because I didn’t answer a question the way the professor wanted. He said, “Well, technically, that is the right answer, but I was looking for the one that we taught in class.” It was really weird because I actually wrote out the right answer, but it only took a couple of words, and I remember thinking, “Oh this is ambiguous. I’m going to write something that may not be the expected answer, but I’m going to provide my complete rationale.” So this guy looked at it and said, “You’re 100 percent right. You even acknowledged what I was looking for as far as the answer is concerned, but you didn’t put the book answer, so I’m deducting points.” I remember I got a 97 instead of a 100 on that test, and it really pissed me off. 

Another factor would have been going into my first introductory computer programming class, and of course I didn’t have any expectations whatsoever, but realizing that we weren’t going to be using even a really lame beginner’s language. It wasn’t Pascal, it wasn’t BASIC, or JavaScript, it was actually some sort of didactic language that was only taught in the textbook that we had. And it all just seemed very futile, you know, because I did have an interest in learning. I spent a huge part of college obsessively working on my own technical projects, but it just wasn’t a good fit, so I made the switch to philosophy because it seemed like a better use of my time.

**Along those lines, what would you say some of the biggest influences are on you and your thinking about security?  Is there a person or a philosophy or an outlook that helps guide your thinking? Are there sources in other fields that you look to for inspiration or ideas?**

The closest thing I ever had to an ethos, or something like it, would have been—and people are going to get confused now because the name is being used by a new generation for something completely different—but there was something called anti-security or anti-security.is, which was essentially the first sort of cogent, well-articulated manifesto of an anti-disclosure policy. And that resonated with me because right around the very early 2000s, you had this sort of sea change where people started getting into security, either auditing for vulnerabilities or writing exploits and publishing them. A lot of things were becoming weaponized and findable and usable by people that hadn’t earned their dues and really had no business running around with these exploits. So there was a very conscious and calculated effort to try to get people to keep things to themselves. And that aligned with how I intuitively felt, or how I approached the whole industry or craft, which is basically, “Magicians don’t reveal their tricks.”

Are there things that influence me outside of the realm of security? It would be extremely hard for me to think of anything that’s influenced me in terms of security that came from outside that world. I’ve always kept a Chinese wall between my digital life and my personal life, especially as it applies to computer security. I just never thought to really go to an external source because it was a lifestyle that I lived. 

There were some books, like Masters of Deception  or Underground,  that were good reference points for finding out about people, but I guess if I were as active in the scene now as I was back in the day, I would probably be a little more vested in the community. But that didn’t really exist then the way it does now. You were on a private IRC server, or an IRC server encrypted communications channel. You figured stuff out on your own, or with a very small set of people. 

I think ten years ago today, it’s almost the way science was after the Victorian era. It was the last sort of plausible juncture in human understanding where you could be somewhat of an expert on multiple areas in science or diverse academic topics. There’s so much specialization now. People spend months writing some obscure breakout for a virtual box. 

Like I said, it would have been a lot more rare back then to stumble across something that was published that was surprising or insightful. I didn’t really keep an ear out for that sort of thing. When you did hear about something, that was because something was leaked, and then there was sort of, like, a scramble to figure out what it was, and use it before it made its way to the masses. 

But times have changed. I mean, I never really published anything, neither vulnerabilities or source code. I had a very low profile in terms of my technical output. It’s served me pretty well for the time period when I was active. I don’t know how viable that would be today. Security was mostly just sort of “keep your ears open, and do work on your own.” 

[...]

**In your own words, you are “an alumnus of the criminal justice system.” When I think about cybercrime and the legal system, there are a couple of things that keep coming to the fore. The first is that the Computer Fraud and Abuse Act  is a pretty blunt instrument. It’s been around for a long time, and it hasn’t really kept up with the time. That second thing is that blunt instrument is being used by someone who is trying to make a career. A cybercrime conviction to a prosecutor is a real feather in their cap, which at least to an outsider can make their efforts seem a little overzealous. Looking at your case, looking at Aaron Swartz —**

Same prosecutor you know, right?

**Right. And if you were to translate a lot of cybercrimes into analog crimes, they would never follow the same course of action.**

How do you mean?

**Someone changes a letter in a URL, and suddenly data that was ostensibly “private” is now viewable by anyone who knows to change that letter. If you were to translate those actions into meatspace, that’s basically trespass. The perpetrator of such a crime wouldn’t be facing years and years and years in prison for that sort of thing, but because it’s “cyber,” it’s a different story. As someone who has his firsthand knowledge of how the system works, what are some ways that we might revise or refine jurisprudence to make things a little more appropriate for the information age?**

I actually want to take a little bit of exception to the idea that digital crimes occupy this special case. I don’t necessarily think that the repercussions of these crimes are anything exorbitant or disproportionate to sentences that are handed down. I think that the one thing that differentiates cybercrimes from others is the media aspect. Consider a comparable crime, something low-key, that nobody really cares about but that might normally carry a sentence of a couple of years. Chances are, the public isn’t necessarily going to be transfixed by that. One thing prosecutors seem to like is the media limelight, and so when the stakes are high, and when there is a certain level of institutional reputation at play, these fights sort of become magnified. I don’t think that computer crimes are really too much of an outlier. I mean, especially when you consider people who go to jail for drugs, who weren’t even distributing. That seems to be an even more sort of immoral use of governmental authority. 

[...]

---

To read the full interview, and learn more about the working lives of a range of security practitioners, order *[Working in Cybersecurity](https://www.amazon.com/Working-Cybersecurity-C-suite-everywhere-between/dp/1725877759)* at Amazon.com.
