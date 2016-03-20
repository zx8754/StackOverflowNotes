# StackOverflowNotes

### Comments

* How to make a great R reproducible example  
`[How to make a great R reproducible example?](http://stackoverflow.com/questions/5963269)`

* How to create a Minimal, Complete, and Verifiable example  
`[How to create a Minimal, Complete, and Verifiable example](http://stackoverflow.com/help/mcve)`

* What does it mean when an answer is "accepted"?  
`[What does it mean when an answer is "accepted"?](
http://stackoverflow.com/help/accepted-answer)`

* How should I deal with “package 'xxx' is not available (for R version x.y.z)” warning?   
`[How should I deal with “package 'xxx' is not available (for R version x.y.z)” warning?](http://stackoverflow.com/questions/25721884)`

* How to join (merge) data frames (inner, outer, left, right)?  
`[How to join (merge) data frames (inner, outer, left, right)?](http://stackoverflow.com/questions/1299871)`

* R Grouping functions:   
`[R Grouping functions: sapply vs. lapply vs. apply. vs. tapply vs. by vs. aggregate](http://stackoverflow.com/questions/3505701)`, `[Aggregate multiple variables simultaneously](http://stackoverflow.com/questions/9723208)`, `[How to sum a variable by group?](http://stackoverflow.com/q/1660124)`

* roll join with start/end window  
`[roll join with start/end window](http://stackoverflow.com/questions/24480031)`

* Reshape:  
`[Reshape data from long to wide format](http://stackoverflow.com/questions/5890584)`   
`[Reshape data from wide to long format](http://stackoverflow.com/questions/1181060)`

* New user  
`Welcome to StackOverflow! Please read the info about [how to ask a good question](http://stackoverflow.com/help/how-to-ask) and how to give a [reproducible example](http://stackoverflow.com/questions/5963269). This will make it much easier for others to help you.`

### Comment formatting   
http://stackoverflow.com/editing-help#comment-formatting

### SE Extensions
* [SE-AutoReview Comments](https://github.com/Benjol/SE-AutoReviewComments)

### Functions
Author: [ananda-mahto](http://stackoverflow.com/users/1270695/ananda-mahto)

```R
# Author: ananda-mahto
# http://chat.stackoverflow.com/transcript/message/11673110#11673110
snarkments <- function(choice = "Reproduce and be merry") {
  A <- c("Reproduce and be merry" = "Please provide a [minimal reproducible example](stackoverflow.com/questions/5963269/…), and please show us what you have tried",
         "lmgtfy" = "I suppose you have [searched](meta.stackoverflow.com/help/how-to-ask) for your problem on SO?",
         "catkiller!" = "Die!!! Die!!! Die!!!")
  unname(A[choice])
}
```
Usage:

```R
snarkments()
# [1] "Please provide a [minimal reproducible example](stackoverflow.com/questions/5963269/…), and please show us what you have tried"
snarkments("lmgtfy")
# [1] "I suppose you have [searched](meta.stackoverflow.com/help/how-to-ask) for your problem on SO?"
snarkments("catkiller!")
# [1] "Die!!! Die!!! Die!!!"
```

