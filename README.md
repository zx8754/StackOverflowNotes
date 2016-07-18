# StackOverflowNotes

### Comments

* How to make a great R reproducible example  
`[How to make a great R reproducible example?](http://stackoverflow.com/questions/5963269)`

* How to create a Minimal, Complete, and Verifiable example  
`[How to create a Minimal, Complete, and Verifiable example](http://stackoverflow.com/help/mcve)`

* What does it mean when an answer is "accepted"?  
`[What does it mean when an answer is "accepted"?](http://stackoverflow.com/help/accepted-answer)`

* How should I deal with “package 'xxx' is not available (for R version x.y.z)” warning?   
`[How should I deal with “package 'xxx' is not available (for R version x.y.z)” warning?](http://stackoverflow.com/questions/25721884)`

* Error: could not find function … in R   
`[Error: could not find function … in R](http://stackoverflow.com/questions/7027288)`

* Joins:  
 - `[How to join (merge) data frames (inner, outer, left, right)?](http://stackoverflow.com/questions/1299871)`
 - `[roll join with start/end window](http://stackoverflow.com/questions/24480031)`

* Grouping functions:   
 - `[apply family, by, aggregate](http://stackoverflow.com/questions/3505701)`
 - `[Group by X, Y, Z FUN()](http://stackoverflow.com/questions/9723208)`
 - `[Group by sum](http://stackoverflow.com/questions/1660124)`
 - `[Group by paste](http://stackoverflow.com/questions/15933958)`
 - `[Group by X FUN_1() FUN_2() FUN_N()](http://stackoverflow.com/questions/12064202)`
 - `[Group by fill/collapse NAs](http://stackoverflow.com/questions/28509462)`

* Reshape:  
 - `[Reshape data from long to wide format](http://stackoverflow.com/questions/5890584)`   
 - `[Reshape data from wide to long format](http://stackoverflow.com/questions/1181060)`

* Floating points:   
 - `[Why are these numbers not equal?](http://stackoverflow.com/questions/9508518)`

* Dates:  
 - `[Date difference in weeks, months, quarters, and years](http://stackoverflow.com/questions/14454476)`

* New user  
 - `Welcome to StackOverflow! Please read the info about [how to ask a good question](http://stackoverflow.com/help/how-to-ask) and how to give a [reproducible example](http://stackoverflow.com/questions/5963269). This will make it much easier for others to help you.`

* Duplicate FAQ   
 - Please read the **FAQ** `[How should duplicate questions be handled?](http://meta.stackexchange.com/q/10841/)`: "It's a duplicate. What do I do?; If you have the privilege to vote to close, click the "close" button under the question, select “duplicate of...”, and paste a link to the duplicate question."; "Should I answer it?; **No**, not if you think it's a duplicate.".
 - Please also read `[The Wikipedia of Long Tail Programming Questions](https://blog.stackoverflow.com/2011/01/the-wikipedia-of-long-tail-programming-questions/)`. "When you see a question that seems like it might reflect a common problem, don't just answer it to get a few points. That doesn't make the Internet any better. Instead, help us build up a library of canonical questions and answers that are more generic versions of the same question". Also, "**Don't answer questions that have already been answered elsewhere.** Yeah, you might earn a couple of points of reputation, but, because you are duplicating content, **you are actually making the internet worse**".

### Comment formatting   
http://stackoverflow.com/editing-help#comment-formatting

### SE Extensions
* [SE-AutoReview Comments](https://github.com/Benjol/SE-AutoReviewComments)

### Functions

```R
# Author: http://stackoverflow.com/users/1270695/ananda-mahto
# http://chat.stackoverflow.com/transcript/message/11673110#11673110
snarkments <- function(choice = "Reproduce and be merry") {
  A <- c("Reproduce and be merry" = "Please provide a [minimal reproducible example](http://stackoverflow.com/q/5963269/1270695), and please show us what you have tried",
         "lmgtfy" = "I suppose you have [searched](http://stackoverflow.com/help/how-to-ask) for your problem on SO?",
         "catkiller!" = "Die!!! Die!!! Die!!!")
  unname(A[choice])
}
```
Usage:

```R
snarkments()
# [1] "Please provide a [minimal reproducible example](http://stackoverflow.com/q/5963269/1270695), and please show us what you have tried"
snarkments("lmgtfy")
# [1] "I suppose you have [searched](http://stackoverflow.com/help/how-to-ask) for your problem on SO?"
snarkments("catkiller!")
# [1] "Die!!! Die!!! Die!!!"
```

