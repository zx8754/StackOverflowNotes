# StackOverflowNotes

### Comments
 - `[How to make a great R reproducible example?](http://stackoverflow.com/questions/5963269)`
 - For questions that are not `[on-topic](http://stackoverflow.com/help/on-topic)`, you might want to try in the `[R-Public chatroom](http://chat.stackoverflow.com/rooms/25312/r-public)`.
 - `[How to make a Shiny app reproducible example?](https://stackoverflow.com/questions/48343080)`
 - `[How to create a Minimal, Complete, and Verifiable example](http://stackoverflow.com/help/mcve)`
 - `[What does it mean when an answer is "accepted"?](http://stackoverflow.com/help/accepted-answer)`
 - Welcome to StackOverflow! Please read the info about `[how to ask a good question](http://stackoverflow.com/help/how-to-ask)` and how to give a `[reproducible example](http://stackoverflow.com/questions/5963269)`. This will make it much easier for others to help you. - [Jaap](http://stackoverflow.com/users/2204410)
 - Not An Answer - This does not provide an answer to the question. To critique or request clarification from an author, leave a comment below their post - you can always comment on your own posts, and once you `[earn](http://meta.stackexchange.com/q/146472/228487) sufficient [reputation](http://stackoverflow.com/help/whats-reputation)` you will be able to `[comment](http://stackoverflow.com/help/privileges/comment)` on any post. If you have a related but different question, `[ask a new question](http://stackoverflow.com/questions/ask)` referencing this one if it will help provide context. – [BhargavRao](http://stackoverflow.com/users/4099593)
 - Duplicate FAQ: Please read the **FAQ** `[How should duplicate questions be handled?](http://meta.stackexchange.com/q/10841/)`: "It's a duplicate. What do I do?; If you have the privilege to vote to close, click the "close" button under the question, select “duplicate of...”, and paste a link to the duplicate question."; "Should I answer it?; **No**, not if you think it's a duplicate.".
 - Duplicate FAQ: Please also read `[The Wikipedia of Long Tail Programming Questions](https://blog.stackoverflow.com/2011/01/the-wikipedia-of-long-tail-programming-questions/)`. "When you see a question that seems like it might reflect a common problem, don't just answer it to get a few points. That doesn't make the Internet any better. Instead, help us build up a library of canonical questions and answers that are more generic versions of the same question". Also, "**Don't answer questions that have already been answered elsewhere.** Yeah, you might earn a couple of points of reputation, but, because you are duplicating content, **you are actually making the internet worse**".
 - StackOverflow is not a code review service. There is codereview.stackexchange.com for that. If you want to get help - please provide a `**minimal**` reproducible example, your desired output and show what you've tired. Try reducing this to a specific problem as much a possible. See `[here](http://stackoverflow.com/questions/5963269)`. - [David Arenburg](http://stackoverflow.com/users/3001626)
 - Answers (even correct ones) are not useful if they contribute to the demise of the site, `[we need to downvote the answers to bad questions](http://meta.stackoverflow.com/a/252531)` - [George Cummins](http://meta.stackoverflow.com/users/749181/george-cummins)
 - While the sentiment is appreciated, StackOverflow deprecates `[using comments to say "thank you"](http://meta.stackoverflow.com/q/258004)`; if this answer was useful you can upvote it (if you have sufficient reputation), and in any case if it answers your question satisfactorily you are encouraged to click the check-mark to accept it. - [Ben Bolker](http://stackoverflow.com/users/190277/ben-bolker)
### Package issues
 - `[How should I deal with “package 'xxx' is not available (for R version x.y.z)” warning?](http://stackoverflow.com/questions/25721884)`

### Error
 - `[Error: could not find function … in R](http://stackoverflow.com/questions/7027288)`
 - `[Syntax errors: mismatch {, if else, etc.](https://stackoverflow.com/questions/25889234)`

### Joins:  
 - `[How to join (merge) data frames (inner, outer, left, right)?](http://stackoverflow.com/questions/1299871)`
 - `[roll join with start/end window](http://stackoverflow.com/questions/24480031)`

### Grouping functions:   
 - `[apply family, by, aggregate](http://stackoverflow.com/questions/3505701)`
 - `[Group by sum](http://stackoverflow.com/questions/1660124)`
 - `[Group by paste](http://stackoverflow.com/questions/15933958)`
 - `[Group by X, Y, Z FUN()](http://stackoverflow.com/questions/9723208)`
 - `[Group by X FUN_1() FUN_2() FUN_N()](http://stackoverflow.com/questions/12064202)`
 - `[Group by fill/collapse NAs](http://stackoverflow.com/questions/28509462)`
 - `[Group by fill NAs](https://stackoverflow.com/questions/23340150)`
 - `[Group by count](http://stackoverflow.com/questions/9809166)`
 - `[Group by distinct count](https://stackoverflow.com/questions/12840294)`
 - `[Group by top_n](http://stackoverflow.com/questions/27766054)`

### %functions%
 - `[What do the %op% operators in mean in R? for example “%in%”](https://stackoverflow.com/q/12730629)`
 
### Reshape:  
 - `[Reshape data from long to wide format](http://stackoverflow.com/questions/5890584)`   
 - `[Reshape data from wide to long format](http://stackoverflow.com/questions/2185252)`

### Sort/Order
 - `[Sort a dataframe by column(s)?](http://stackoverflow.com/questions/1296646)`   

### Floating points:   
 - `[Why are these numbers not equal?](http://stackoverflow.com/questions/9508518)`
 - `[Round up from 0.5](https://stackoverflow.com/questions/12688717/)`

### Dates:  
 - `[Date difference in weeks, months, quarters, and years](http://stackoverflow.com/questions/14454476)`

### Regex:
 - `[Learning Regular Expressions](http://stackoverflow.com/questions/4736)`

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

### r-public Canonicals 
- More resources at [r-public HammeR](https://github.com/r-public/HammeR/blob/master/Canonicals.md)

