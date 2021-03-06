title: Abstraction
published: 2018-03-13
tag: computing
tag: human factors

A human brain can only keep a few ideas in their head at once.
The numbers I've heard are about 3-5 things, and perhaps a few special people can remember 7 ideas at once.
When faced with even a moderately large problem, the human brain will break down if it tries to deal with all of it in one go.
To solve problems we have to break them into smaller pieces.
That is what it means to "decompose" a problem.

<!-- So far, this might seem extraordinarily basic, but let me ask you a question: -->
Let's say that we've broken a problem into two pieces: A and B.
There are usually lots of ways to decompose problems, and some of them are better than others.
Most decompositions are bad, so we can't rely on luck when we break up a problem.
So, how do you know if this decomposition---into parts A and B---is good or bad?
Think about how you might prove to someone that your choice was a good one.
What characteristics does your decomposition have that make it good?

!!! note "Pause and Ponder"
    Really, take at least thirty seconds and answer the question: **What makes for a good problem decomposition?**
    Write your answer down somewhere, or at least say it aloud so you're commited.
    Only after that, let's see my answer.

For problem decomposition to be effective, you need to be able to think about each part individually---i.e. without any reference to anything about the other parts.
When you work on part A, you shouldn't be thinking[^dontthink] about how B is solved, and when you think about B, you shouldn't be thinking about how A is solved.
This property---being able to think about one part separately from the others---is called "abstraction".
The mark of a good problem decomposition is that it breaks the problem into pieces that are all abstract from each other.

The lines along which you cut the problem into pieces are called "abstraction boundaries".
When those boundaries are violated, the problem gets larger and quickly goes beyond the ability of a human to cope.
To avoid this problem, every piece of the solution should document[^enforce] those abstraction boundaries.
Failure to state these boundaries, or failure to respect them, leads to problems humans cannot solve.
That is what "controlling complexity" is all about.


[^dontthink]: Note that I'm _not_ saying "you shouldn't **have to** think", but that "you **shouldn't** be thinking".
If you're working on part A, the fastest way to solve it is to not get distracted by B.
If you feel you need to break this commandment, your decomposition may not be good; if you're sure the decomposition really is good, then you need to fix your brain.

[^enforce]: and prefereably also enforce