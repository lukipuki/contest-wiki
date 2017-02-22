When you walk into a bookstore, you often find books called ''Teach Yourself Java in 7 Days''. The authors try to convince you that programming is easy when it ''really is not''. Peter Norvig wrote an excellent essay on this topic called [Teach Yourself Programming in Ten Years](http://norvig.com/21-days.html) which I highly recommend. See also [a comic by Abstruse Goose](http://abstrusegoose.com/249) on the same topic. I agree with Peter &ndash; it takes a lot of time and effort. However, you should still try to make your training as effective as possible.

There is very little information available about training for programming competitions, so I decided to create a training program, which is probably the first one ever written. It is based on my experience as a competition programmer as well as a semi-professional athlete. Please [let me know](Readme.md#contact) if you have any comments.

## Training program

### Training philosophy
Until the age of 15, I have been competing in orienteering (running with a map in the forest). I was training a lot, running 1700 km a year in the mountains. Then I got health problems and stopped training completely. Suddenly I had a lot of free time which I spent training for math and programming competitions instead. I actually used some of the sport training methods for my programming trainings.

I think sports and programming competitions have a lot in common. Similarly to sports, you will not improve much by only doing one type of training and competing. The training must be '''varied''' and you should focus on your '''weaknesses'''.

Let's take football as an example. Suppose you are an attacker in a football team. Your are very good in scoring goals during the game but penalty kicks are your weakness. You could continue training as before and kick 2&ndash;3 penalty kicks a week when the opportunity arises in a training match or in a league match. But wouldn't it be better if you stayed 15 minutes after each training practicing penalty kicks?

The same goes for problem solving skills. If you rarely solve a geometry problem in a contest but do most of your practice happens in the TopCoder practice rooms, you will not progress, because there are rarely any geometry problems on TopCoder. You need to find another way of training.

Your training should also be varied. I noticed that many universities only train in teams for ACM ICPC. At KTH, we train individually in the spring and in teams in the fall. I think both types of training are important. For example, you might never solve a dynamic programming problem during team training, because your other team mate always solves such problems before you can even read them. In an individual training you will be forced to solve such problems, and thus learn more.

Our training program consists of ''7 training blocks''. Training programs for sports often say that you should do ''this and that'' twice a week for 1 hour, do ''that'' once a week for 30 minutes and so on. It is hard to do the same thing here, because people start at very different levels. Instead, you should evaluate yourself, identify your weaknesses and strengths and choose the right type of training for you. You might know somebody more experienced or you have a coach at the university that might help you find the right type of training.

You should do all the training blocks, but the time spent doing different blocks is going to be different for different people.


### Learning algorithms and data structures

When people try to get better at programming competitions, they first learn algorithms and data structures. Of all the parts of the training programme, this one is the most developed. There are countless books, tutorials and university courses on the topic.

I recommend you to read the book [Introduction to Algorithms by Cormen, Leiserson, Rivest and Stein](http://amzn.com/0262033844). There are also excellent [algorithm tutorials on TopCoder](http://www.topcoder.com/tc?d1=tutorials&d2=alg_index&module=Static). For algorithms classes you should check your university or find some online courses. If you are at KTH, take [Algoritmer, datastrukturer och komplexitet](http://www.csc.kth.se/utbildning/kth/kurser/DD1352/) and [Problemlösning och programmering under press](http://www.csc.kth.se/utbildning/kth/kurser/DD2458/) as soon as possible in your first or second year. Since 2013, the latter is taught by a great programmer [Per Austrin](http://community.topcoder.com/tc?module=MemberProfile&cr=7421158) and some other competition programmers at KTH usually help out.

However, this is only a small part of being a good programmer and in my opinion it is a bit overrated. You can get far without knowing many algorithms and other ''blocks'' of this training program might be more helpful to you.

Let me explain why I think you should not study too much with the help of an analogy. Suppose you decided to pick up mountain biking, but you never rode a bike before. You start browsing the web, watching YouTube videos and you even buy a 150-page book about mountain biking. After 2 months of studying you decide it's time to try it out. You try to remember everything you read and saw in the videos and it's overwhelming. You get mad at yourself, because you fell so many times from the bike even after studying so hard. You might actually give up biking in the end.

Does this sound ridiculous to you? Now substitute ''biking'' above with ''programming''. Of course biking and programming are not the same, but trying to absorb all the information available often does more harm than good. Instead, you should just start solving problems and learn algorithms on the way. You'll also see when and how algorithms are actually used. Humans learn by doing and we need to make mistakes in order to learn something. If you never fail, you never learn. You can read more about [[#Failure|failure]] later in this chapter.

These ideas are quite well supported [by research](http://ideas.time.com/2012/04/25/why-floundering-is-good/). It turns out it's better to start tackling problems on your own before getting some guidance. As an example, in an algorithm class you could be asked to program a shortest path algorithm in an unweighted graph without getting any information on data structures or time complexity. You will probably come up with something resembling breadth-first-search but since you haven't heard about queues and time complexity before, your algorithm might be slower. In the next lecture the teacher will show a solution that involves implementing a queue and he will tell you how to estimate the time complexity of your programs. This method of teaching is more effective than doing it the other way — presenting the current theoretical knowledge first and solving the problem later.


### Improving your problem solving ability

This is the hardest block of our program. Our ultimate goal here is to '''increase your intelligence'''. You might have heard that intelligence is pretty much inherited and cannot be changed, but the truth is that you can [increase it slightly](http://www.ams.org/notices/201103/rtx110300432p.pdf) (and probably also decrease it by being too lazy). Sadly, there is not much information available on this topic.

<!-- TODO: reference about intellingence -->

When you look at [my TopCoder rating graph](http://community.topcoder.com/tc?module=MemberProfile&cr=14769155), you might see that in both year 2006 and year 2007 I made some progress but I did more progress in 2007. Most of 2006 I had rating 1900-2100 while in 2007 I moved to cca 2300. In the first half year of 2006, after not making any progress for a while, I thought I hit my maximum and that 2000-2100 will be my rating forever.

Maybe you think that I just trained more in 2007, but that's not true. In 2007 I started working 2 days a week for a company, I wrote my bachelor's thesis, I was still studying and helping with the Slovak Olympiad, I started playing ultimate frisbee semi-professionally and last but not least, I became also more socially active. I really had much less time for programming trainings.

Instead of increasing the quantity, I increased the quality of the training. I started '''solving harder problems'''. When you solve a lot of easy problems, you might learn to type quickly and not make mistakes, but you don't challenge your brain very much. On the other hand, you should not challenge yourself too much, because it might be frustrating if the problems are too hard. Psychologist call this phenomenon [zone of proximal development](http://en.wikipedia.org/wiki/Zone_of_proximal_development).

I like to think about problem solving using the following ''furniture metaphor''. Imagine you have a house and you bought a huge table that you want to put on the second floor. If the doors and stairways are too small, you will have to disassemble the table and maybe even cut it. After you bring the smaller pieces to the second floor, you assemble it back but this takes a lot of time. Wouldn't it be nicer to have bigger doors and stairways?

When you are solving a problem, you try to fit it in your brain in a similar way as the table in the house. If the problem is too complicated, you might have to dissect it into smaller pieces, solve them first, and then assemble the pieces back together into a full solution. As you increase your intelligence, your brain ''gets bigger'', so you can fit harder and harder problems in your brain without dissecting them.

The remaining question is how to find problems just outside your comfort zone (or in ''Zone of proximal development'' if you like). You might come up with something else but here is roughly what I did. I really like [SPOJ](http://www.spoj.pl/) judge which has lots of beautiful problems. For each problem you can see how many people solved it. In the beginning, I opened problems solved by 150-200 people and did this for a few months. When I felt this was too easy, I did 100-150 for a while and so on. You might also try doing the same on TopCoder. Start first with Division 2 Easy and then move towards Div 1 problems. When you have trouble solving a problem, try asking a more experienced friend, coach or in the forums. There are plenty of online communities where people are happy to help you with solutions.

### Improving your programming skills

After you solve a problem in your head, you need to implement it. In the ideal world, you would write correct code that does not need debugging. You might think this is impossible but if you watch high rated TopCoders, this is exactly what they do. After solving a problem, they write a solution which is often correct after the first compilation. Of course, getting here is not easy and takes time.

Similarly to the previous training block [[#Improving your problem solving ability|Improving your problem solving ability]], you improve your programming skills best on problems that are still in your  ''problem solving comfort zone'' but just outside of your ''programming comfort zone''. These are the problems you are able to solve quickly in your head but implementing them takes you too much time or you make too many mistakes.

When I started practicing for programming competitions, I solved a lot of very easy problems. There was even a week when I only did Div2 Easy problems in the TopCoder arena. Of course, this became boring after a while but in the end the solutions were often correct after the first compilation. After this I moved to Division 2 Medium and so on.

### Coding and debugging on paper

Not many people write code on paper these days, but I think it is a very good type of practice. Since it is very hard to edit code on paper, you have to think harder before you start writing it. When at a computer, you might be tempted to start writing right away, even before making sure your algorithm is correct and you ironed out all the details. You would think that you can change the code quickly on a computer after you discover a bug. However, many times such bugs are so severe that you need to rewrite most of the solution. Coding on paper helps you prevent such situations, because it forces you to think more about all the details. Also, our goal is to learn to write correct programs on the first try without much editing and this is the perfect tool to get there.

This is also a very useful skill in ACM ICPC, because you only have one computer and you should write code on paper as soon as you have a solution in your mind, so that at the computer you don't waste time thinking about some details.

Also try to debug on paper. Print some helpful output from your program execution, print your code and read it while you sit on the bus/train. Debugging on a computer and going through the steps of the algorithm takes a lot of time and many times debugging on paper is faster.

### Competing

Since our goal is to succeed in competitions, you should compete as much as you can. When solving problems at home, you are not under stress and you have more time. In a competition, the time pressure might decrease your problem solving ability. In a perfect world, you would perform even better under pressure than without it.

By competing you learn how to handle such stress and you also learn basic tactics. For example, 1 hour before the end of a 5-hour contest, it's probably a very bad choice to start working on a new problem when you have 3 unfinished problems with a lot of failed submissions.

<!-- Add links about stress and that it is actually good for you. -->

### Improving the quality of your code

After submitting a solution to a judge and getting it accepted, return back to the code and try to make it nicer and shorter. Look at other people's code and try to understand them. Often the best programmers like Petr or tourist have very nice and short solutions and these might help you some other time in the future.

You can also try making your faster after it got accepted. This might often mean making it less readable and longer. Sites like SPOJ have rankings of the fastest solutions, try to get as high as possible. You will learn a lot about the speed of various operations in your programming language.

### Take care of your body

This might be a bit unconventional, but I think ''exercise'' and ''healthy diet'' is important for programmers as well. Brain is a part of the body and we can think of the rest of the body as a ''support'' for the brain. If you don't take care of the support well, then this can affect the brain in a bad way.

<!-- exercise and nutrition -->


## Motivation

Competitions help your programming skills immensely. Some people say that the competition problems don't resemble real world problems very well and that is true most of the time. When working for a company, solving algorithmic problems might be 5&ndash;10% of your work if you are lucky. Very often the problems are not well defined, getting good input data is hard and most solutions are too complicated to implement or too slow to run.

However, it is still a great way to improve as a programmer. In school we all learned math, reading and writing but few of us work as mathematicians, writers or readers (if there is such a job :-). We need these skills in our day-to-day life. Even if you do not end up doing reseach in math, it teaches to think analytically. And perhaps you don't write so much, but writing trains your brain to formulate your thoughts in a more understandable way.

Of course, there are many other skills needed to be a good programmer. You should be able to work in a team, master a version control system etc. But programming competitions can teach you how to break down a problem into small pieces, solve them and then reassemble back. You will produce fewer bugs and you will care more about the time complexity of your programs.

As you can see, there are many objective benefits of programming competitions. However, I probably do them because they are a lot of fun. The learning part is nice, but this reason is usually not enough to force yourself to spend hours every week practicing.

That being said, if you don't find programming competitions fun, go and find something else to spend your time on. I have met some talented programmers that tried competitions and got good at them, but they weren't enjoying it so much. If you enjoy working on an open source project or doing math research, that's not a problem: do that instead!

However, if your choice is between competitions and playing video games, browsing Reddit or Facebook, you should seriously think about motivating yourself more. Try the following mental exercise: imagine yourself in ten years. Do you think that person would say "I wish I played more video games, spend more time on Reddit and Facebook and did less programming when I was at the university"? I am not saying you should not do these things at all, for example Reddit has been very helpful in doing article research for writing this guide. Just do all of them in moderation.

### Failure
Failure is great, it shows you what you did wrong. Also, our brains work in such a way that we learn the most by making mistakes. The following quote is from [Why Floundering Is Good](http://ideas.time.com/2012/04/25/why-floundering-is-good/):
<blockquote>
Call it the ''learning paradox'': the more you struggle and even fail while you’re trying to master new information, the better you’re likely to recall and apply that information later.
</blockquote>

Since failure is so crucial in the learning process, you need to be able to deal with it. Such quality is called self-compassion in English. The following quote about self-compassion is from [To Succeed, Forget Self-Esteem](http://blogs.hbr.org/cs/2012/09/to_succeed_forget_self-esteem.html).
<blockquote>
Self-compassion is a willingness to look at your own mistakes and shortcomings with kindness and understanding — it's embracing the fact that to err is indeed human. When you are self-compassionate in the face of difficulty, you neither judge yourself harshly, nor feel the need to defensively focus on all your awesome qualities to protect your ego.<br/>
... <br />
Here's an unavoidable truth: You are going to screw up. Everyone — including very successful people — makes boatloads of mistakes. The key to success is, as everyone knows, to learn from those mistakes and keep moving forward. But not everyone knows how. Self-compassion is the how you've been looking for. So please, give yourself a break.
</blockquote>

I couldn't say it better. Go ahead and read [the whole article](http://blogs.hbr.org/cs/2012/09/to_succeed_forget_self-esteem.html).
