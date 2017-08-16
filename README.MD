# Regular Expression Exercise
## Look up a website that has regex rules.
### Here's a regex cheat sheet http://www.rexegg.com/regex-quickstart.html

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions

## Part 1

### Exercise 1

Enter a regexp that matches all the items in the first set (positive examples) but none of those in the second (negative examples).

** Positive**

* pit
* spot
* spate
* slap two
* respite

**Negative**

* pt
* Pot
* peat
* part

### Exercise 2

Enter a regexp that matches all the items in the first set (positive examples) but none of those in the second (negative examples).

**Positive**

* rap them
* tapeth
* apth
* wrap/try
* sap tray
* 87ap9th
* apothecary

**Negative**

* aleht
* happy them
* tarpth
* Apt
* peth
* tarreth
* ddapdg
* apples
* shape the


### Exercise 3

Enter a regexp that matches all the items in the first set (positive examples) but none of those in the second (negative examples).

**Positive**

* affgfking
* rafgkahe
* bafghk
* baffgkit
* affgfking
* rafgkahe
* bafghk
* baffg kit

**Negative**

* fgok
* a fgk
* affgm
* afffhk
* fgok
* afg.K
* aff gm
* afffhgk


### Exercise 4

Enter a regexp that matches all the items in the first set (positive examples) but none of those in the second (negative examples).

**Positive**
assumes word senses. Within
does the clustering. In the
but when? It was hard to tell
he arrive." After she had
mess! He did not let it
it wasn't hers!' She replied
always thought so.) Then

**Negative**
in the U.S.A., people often
John?", he often thought, but
weighed 17.5 grams
well ... they'd better not
A.I. has long been a very
like that", he thought
but W. G. Grace never had much


## Part 2
### Which of the following matches regexp /^a(ab)*a$/

1.      abababa
2.      aaba
3.      aabbaa
4.      aba
5.      aabababa

### Which of the following matches regexp /^ab+c?/

1.      abc
2.      ac
3.      abbb
4.      bbc

### Which of the following matches regexp /^a.[bc]+/

1.      abc
2.      abbbbbbbb
3.      azc
4.      abcbcbcbc
5.      ac
6.      asccbbbbcbcccc

### Which of the following matches regexp /^abc|xyz$/

1.      abc
2.      xyz
3.      abc|xyz

### Which of the following matches regexp /^[a-z]+[\.\?!]$/

1.      battle!
2.      Hot
3.      green
4.      swamping.
5.      jump up.
6.      undulate?
7.      is.?

### Which of the following matches regexp /^[a-zA-Z]*[^,]=$/

1.      Butt=
2.      BotHEr,=
3.      Ample
4.      FIdDlE7h=
5.      Brittle =
6.      Other.=

### Which of the following matches regexp /^[a-z][\.\?!]\s+[A-Z]$/

1.      A. B
2.      c! d
3.      e f
4.      g.   H
5.      i?  J
6.      k L

### Which of the following matches regexp /^(very )+(fat )?(tall|ugly) man$/

1.      very fat man
2.      fat tall man
3.      very very fat ugly man
4.      very very very tall man

### Which of the following matches regexp /^<[^>]+>$/

1.      <an xml tag>
2.      <opentag> <closetag>
3.      </closetag>
4.      <>
5.      <with attribute=”77”>
