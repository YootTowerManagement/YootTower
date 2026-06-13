# Appendix III: Acknowledgments

> Source note: Readable Markdown rendering from the local OCR/plain-text transcription. OCR spellings are mostly preserved; formatting has been added for GitHub readability. Bret Victor's HTML edition of the paper is at [The Early History Of Smalltalk](https://worrydream.com/EarlyHistoryOfSmalltalk/), with the scanned original linked from that page.


## Early Participants

### 1971

- [Chris Jeffers](People.md#chris-jeffers-xerox-parc)
- + ?

### 1972

- Chris Jeffers
- John Shoch
- Steve Purcell
- Bob Shur
- Bonny Tennenbaum
- [Barbara Deutsch](People.md#barbara-deutsch-xerox-parc)

## 1973 Acknowledgments Document

A document written by me shortly after [Smalltalk-72](Technologies.md#smalltalk) started working.

- **Latest revision:** March 23, 1973

Much of the philosophy on which our work is based was inspired by the ideas of [Seymour Papert](People.md#seymour-papert-mit-university-of-geneva-university-of-paris-national-physical-laboratory) and his group at MIT.

The Dynabook (ka 71) is a godchild of [Wes Clark](People.md#wesley-a-clark-uc-berkeley-linc-mit-mit-lincoln-laboratory-washington-university-clark-rockoff-and-associates)'s LINC (cl 1962) and a lineal descendent of the FLEX machine (ka 67, 68, 69).

The "interim Dynabook" (known as the ALTO (Th 71, Mc 71) is the beautiful creation of [Chuck Thacker](People.md#chuck-thacker-uc-berkeley-xerox-parc-dec-microsoft) and Ed McCreight of the Computer Science Lab. at PARC.

SMALLTALK is basically a synthesis of well-known ideas for programming languages and machines which have appeared in the last 15 years.

The [Burroughs B5000](Technologies.md#b5000) (ba 61) (B60) had many design ideas well in advance of its time (and still not generally appreciated): compact "addressless code; a uniform semantics for names (the PRT), automatic coprocesses, "capability" protection (also by the PRT and Descriptors_, virtual segmented memory, the ability to call a subroutine from "either side" of the assignment arrow, etc.

The notions of code as a data structure; intensional properties of names (property lists of attribute-value pairs on atoms); evaluation with respect to arbitrary environments; etc., are found in LISP, probably the greatest single design for a programming language yet to appear. SMALLTALK is definitely "LISPlike".

The SIMULAs ('65 and '67) combined Conway's notions of software coroutines (1963-hardware version had appeared in the B5000 3 years earlier), [ALGOL](Technologies.md#algol)-60, and Hoare's ideas about record classes (ca. 1964) into an epistemology that allowed a class to have any number of parallel instantiations (or activation records) containing local state including a separate program counter. Most of the operations for a SIMULA '67 class are held intrinsically as procedures local to the class definition.

The FLEX machine and its language ('67-69) took the SIMULA ideas (discarding most of the ALGOLishness), moved "type" from a variable onto the objects (ala [B5000](Technologies.md#b5000) and EULER), formed a total identification between "coprocesses" and "data", consolidating notions such as arrays, files, lists, "subroutine" files (ala SDS-940) etc., into one idea. The "user as a process" also appeared here. A start was made to allow processes to determine their own input syntax, an idea held by many (notably Irons, Leavenworth, etc.).

The Control Definition Language of Dave Fisher (1970) provided many ideas, solutions and approaches to the notion of control. It, with [FLEX](Technologies.md#flex-machine), is the major source for the semantics of SMALLTALK. It is a "soulmate" to FLEX; independently worrying about many of the same problems and very frequently arriving at cleaner, neater ways to do things. Many of Dave's ideas are used including the provision for many orthogonal paths to external environments, and that control is basically a matter of organizing these environments. SMALLTALK removes Fisher's need for a compiler to provide a mapping between nice syntax and semantics and offers other improvements over his schemes such as total local control of the format of an instance, etc.

An extemporaneous talk by R.S. Barton at Alta ski lodge (1968) about computers as communications devices and how everything one does can easily be portrayed as sending messages to and fro, was the real genesis of the current version of SMALLTALK.

The fact that kids were to be the users, and the simplicity and ease of use of the already existing LOGO, whose own parents were LISP and [JOSS](Technologies.md#joss) (which set a standard for the esthetics for interaction that has not yet been surpassed), provided lots of motivation to have programs and transactions appear as simple as possible-i.e. moving from left to right, procedures gather their own messages, etc. It is no accident that simple SMALLTALK programs look a bit like LOGO!

Problems discovered years ago in "lefthand calls" prompted SMALLTALK to make "store" intensional-i.e. `a ‹- b`, means "call 'a' with a message consisting of the token '<-' and symbol 'b'. If anyone can make the right decision for what this means, it must be the object bound to 'a'. The early fall of 1972 saw an evaluator for SMALLTALK, and the idea that '+', '-', etc., should also be intensional. This led to an entire philosophy of use (unlike SIMULA '67) to put EVERYTHING in class definitions including the so-called "infix operators". This message idea allows messages to have a wide range of form since all messages can be received incrementally.

"Control of control" allows control structures to be defined, The language SMALLTALK itself thus avoids "primitives" such as "loop...pool", synchronous and asynchronous "ports", interrupts, backtracking, parallel eval and return, etc. All of these can be easily simulated when needed.

These are the main influences on our language. There were many other minor and negative influences from other existing languages and ideas too numerous to mention except briefly in the references.

This particular version of SMALLTALK was designed through the summer and early fall of 1972 and was aided by discussions with [Steve Purcell](People.md#steve-purcell-xerox-parc), Dan Ingalls, Henry Fuchs, Ted Kaehler, and John Shoch. From the preceding acknowledgments it can be seen as a consolidation of good ideas into one simple idea:

> Make the PARTS (object, subroutines, I/O, etc.) have the same properties and power as the WHOLE (such as a computer).

This is the basic principle of recursive design, SMALLTALK recurs on the notion of "computer" rather than of "subroutine."

A talk on SMALLTALK was given at the AI lab at [MIT](Institutions.md#mit-massachusetts-institute-of-technology) (Nov 1972) which discussed the process structure and the new, intentional way to look at properties, messages, and "infix operators". This led to the just published formal "actors model of computation" of Hewitt, et al. (1973).

## Project Credits

[Dan Ingalls](People.md#dan-ingalls-harvard-stanford-university-xerox-parc-apple-inc-interval-research-corporation) of our group at PARC, the implementor of SMALLTALK, has revealed many design flaws through his several, excellent quick "throw away" implementation of the language. SMALLTALK could not have existed without his help, virtuosity, and good cheer.

- The original design of the "painting editor" was by [Alan Kay](People.md#alan-kay-university-of-colorado-at-boulder-university-of-utah-xerox-parc-atari-apple-viewpoints-research-institute). It was implemented and tremendously improved by Steve Purcell.
- The "Animator" was designed and implemented by [Bob Shur](People.md#bob-shur-xerox-parc) and Steve Purcell.
- Line graphics and the hand-character recognizer were done by [John Shoch](People.md#john-shoch-stanford-university-xerox-parc).
- "Music:" was designed and implemented by Alan Kay.
- The design and implementation of the font editor was by [Ben Laws](People.md#ben-laws-xerox-parc) (POLOS).

We would like to thank CSL and POLOS in general for a great deal of all kinds of help.

## Groups And Participants

### Learning Research Group

Alan Kay, Head; [Adele Goldberg](People.md#adele-goldberg-university-of-michigan-university-of-chicago-stanford-university-xerox-parc-acm); Dan Ingalls; Chris Jeffers; Ted Kaehler; Diana Merry; Dave Robson; John Shoch; Dick Shoup; Steve Weyer.

### Students

Barbara Deutsch; Tom Horsley; Steve Purcell; [Steve Saunders](People.md#steve-saunders-xerox-parc-hewlett-packard-atari-interval-research-corporation-apple-inc); Bob Shur; David C. Smith; Radia Perlman.

### Child Interns

Dennis Burke (age 12); Marian Goldeen (age 13); Susan Hammet (age 12); Bruce Horn (age 15); Lisa Jack (age 12); [Kathy Mansfield](People.md#kathy-mansfield-xerox-parc) (age 12); Steve Putz (age 15).

### Visitors

Ron Baecker; Eric Martin; [Bonnie Tenenbaum](People.md#bonnie-tenenbaum-stanford-university-xerox-parc).

### Help From Other Groups At PARC

[Patrick Baudelaire](People.md#patrick-baudelaire-university-of-utah-xerox-parc); Dave Boggs; Bill Bowman; Larry Clark; Jim Cucinitti; Peter Deutsch; Bill English; Bob Flegal; Ralph Kimball; Butler Lampson; Bob Metcalfe; Mike Overton; Alvy Ray Smith; Bob Sproull; Larry Tesler; Chuck Thacker; Truett Thach.
