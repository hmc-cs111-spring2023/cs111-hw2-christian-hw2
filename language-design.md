_Fill in each this file with your responses, placing each response after its
corresponding question._

---

**Question**

Pick three quotes from the readings about language design. Good candidates
are:

- Something you agreed with / resonates with your own experience
- Something you disagree with
- Something that is interesting, a new idea or perspective you'd like to remember
- Something you didn't understand

For each quote, describe what it was about the quote that led you pick it.

**Response**

1. "I should not design a small language, and I should not design a large one. I need to design a language that can grow. I need to plan ways in which it might grow—but I need, too, to leave some choices so that other persons can make those choices at a later time" [Steele, 1998].

   I found this perspective interesting, as it related to some of the in-class discussions we have had about addressing the needs of users and languages. We need to leave room for the users, even though an implementer may be inclined to prioritize the functionality they desire, they should prioritize their language being broadly usable over something strictly holding true to their original image.

2. "They created a “placebo language” called Randomo, whose syntax was randomly generated, to use in trials alongside Quorum and Perl. Novice programmers were able to write sample programs more accurately in Quorum versus Perl" [Pavlus, 2012].
   
   I found this result to be very surprising because I would have expected an intentionally designed programming language to better suit the needs of its users than a "placebo language" with randomly generated syntax. I wonder how this was generated because many programming languages hold similar characterisitcs so if Randomo did not highly vary from the languages it was modeled after, then this result would make much more sense to me.

3. "When in doubt, leave it out" [Bloch, 2006].

    This is a perspective I would have initially disagreed with before reading this piece, because as an API user, I have often found myself frustrated with the lack of an existing piece of functionality. However, now having read through this, I better understand that brevity is valuable in API creation in order to ensure that it can serve its purpose and broadly help as many users as possible without adding unnecessary functionality that some users may be upset if you later remove.

---

**Question**

How would you know a well-designed language? What are the symptoms? How would
you know a poorly designed language? What are the symptoms?

**Response**

I would know a language is well-designed if it is "humanely designed", following the description of Pavlus, meaning that it is sufficiently readable such that a novice programmer could look at it and interpret what it does. Additionally, it should have good documentation so that people can learn about it without having to manually deconstruct code or having to use the language, as detailed in Bloch's piece. 

A poorly designed language is one that is challenging to learn, both in that it is difficult to read and that it does not have an accessible set of documentation for those seeking to improve their understanding, contrary to the desired principles above from Pavlus and Bloch's works.

---

**Question**

How might the themes of _Growing a Language_ relate to ideas from the Fowler reading?

**Response**

The themes of _Growing a Language_ relate to ideas from the Fowler reading in that _Growing a Language_ seeks to make programming languages be more like natural language, as he pushes for that and urges readers to use natural language more similarly to how programming languages are used. Fowler also makes some suggestions to make DSLs more readable, though he states "Don't try to make the DSL read like natural language". This is interesting because they both recognize that there is issues with the design of programming languages, and yet there is some conflict on the boundaries between natural language and programming languages.

---

**Question**

In what way is an API a language?

**Response**

An API is a language because they must be implemented, have users, a set of documentation (a method of learning), and it follows a structured syntax which allows users to manipulate/communicate information. Particularly it must follow many of the same design principles of languages, like Steele describes, it follows on the structure of smaller bits of language, such as syllables, being used to form more complex pieces with some meaning, which in relation to a language would represent the words. Also, there is an expectation that others should be able to read what you have written in both.

---

**Question**

What does the post on grayscale tell us about the process of API design?

**Response**

The post on grayscale explains the process on considering how readable an API's methods are, because as it describes, each of the design options proposed offer their own set of drawbacks related to the readability of the call. I found this very interesting and relatable because we are initially taught that naming conventions should be clear, but in the case of APIs which should be minimal, or in large projects where many methods are similar, it is often difficult to determine how our decision may be interepreted by future users of our code. These decisions are reflected in the experiences of users in the form of developers using the API, as is demonstrated in the following quote from a guide for the programming language R: "R is a shockingly dreadful language for an exceptionally useful data analysis environment. The more you learn about the R language, the worse it will feel" [Smith, 2016]. 

---

**Question**

The Pavlus article mentions the researchers' comments that people preferred
"natural-language replacements for some of the more abstruse syntax". In other
words, people found it easier to work with code that looks more like a human language (e.g.,
English). Consider the following quote by William R. Cook, one of the creators
of AppleScript:

> The experiment in designing a language that resembled natural languages (English
> and Japanese) was not successful. It was assumed that scripts should be
> presented in “natural language” so that average people could read and write
> them. … In the end the syntactic variations and flexibility did more to confuse
> programmers than to help them out. It is not clear whether it is easier for
> novice users to work with a scripting language that resembles natural language,
> with all its special cases and idiosyncrasies. The main problem is that
> AppleScript only appears to be a natural language: in fact, it is an artificial
> language, like any other programming language. … even small changes to the
> script may introduce subtle syntactic errors that baffle users. It is easy to
> read AppleScript, but quite hard to write it.
> [[Cook 2007, page 1-20]](https://dl.acm.org/citation.cfm?doid=1238844.1238845)

Are these two experiences of natural languages at odds with one another? Would
you choose to include natural language in the design of a DSL? If so, how might
you do so? If not, why not?

**Response**

It does seem as if these two experiences are at odds with each other because Pavlus proposes that researchers found people preferred the natural-language syntax while Cook presents that in their experiment, this further confused programmers instead of resolving their issues with the language. I would only choose to include a small quantity of natural language when designing a DSL, such as for keywords, because this is common practice in programming languages and I would not propose a change to the structure programmers are used to unless I had evidence demonstrating that the programmers would prefer a change be made and that the decision I make would be more widely accepted, such as by user experiences and surverys. This follows in the work of Bloch who proposes that we should not make changes to APIs removing functionality users have grown accustomed to. I extend this to programming languages as a whole because it does seem like most programmers like to have a general set of functionality which is common across most general purpose programming languages.

---
