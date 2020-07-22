# Statistics for Python

To get started thinking about statistics, consider the three famous problems

* Suppose you have a bag filled with colored marbles. You close your eyes and
  reach into it and pull out a handful of marbles, what can you say about what is
  in the bag?

* You arrive in a strange town and you need a taxicab. You look out the window,
  and in the dark, you can just barely make out the number on the roof of one of
  the cabs. In this town, you know they label the cabs sequentially. How many
  cabs does the town have?

* You have already taken the entrance exam twice and you want to know if it's
  worth it to take it a third time in the hopes that your score will improve.
  Because only the last score is reported, you are worried that you may do worse
  the third time. How do you decide whether or not to take the test again?

Statistics provides a structured way to approach each of these problems.  This
is important because it is easy to be fooled by your biases and intuitions.
Unfortunately, the field does not provide a *single* way to do this, which
explains the many library shelves that groan under the weight of statistics
texts. This means that although many statistical quantities are easy to
*compute*, these are not so easy to justify, explain, or even understand.
Fundamentally, when we start with just the data, we lack the underlying
probability density that we discussed in the last chapter. This removes key
structures that we have to compensate for in however we choose to process the
data.  In the following, we consider some of the most powerful statistical
tools in the Python arsenal and suggest ways to think through them
