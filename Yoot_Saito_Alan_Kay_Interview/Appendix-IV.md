# Appendix IV: Event Driven Loop Example

> Source note: Readable Markdown rendering from the local OCR/plain-text transcription. OCR spellings are mostly preserved; formatting has been added for GitHub readability. Brett Victor's HTML edition of the paper is at [The Early History Of Smalltalk](https://worrydream.com/EarlyHistoryOfSmalltalk/), with the scanned original linked from that page.


First we make a class for events:

```text
to event I mycode
(ISNEW » ('mycode <- array 3.
mycode (2] <- ' done.)
anewcode » (mycode [1) <- :.)
ais
»
(ISIT eval)
mycode eval)
```

Each event stores away code to be executed later. The `done` will eventually cause an exit from the driving loop in the `until` structure, defined next:

```text
to until tempatom statement
(repeat ('tempatom <-:. "this loop picks up all the event identifiers (unevaled) "
tempatom <- event. "an indirect store to whatever was in the message" nor » (again) done)
(ado » ('statement ‹- :))
"the loop body to be evaled"
(acase » (repeat ('tempatom <- :. "pick up an event-case label"
(tempatom eval is event »
(a:. tempatom eval newcode :.) "pick up the corresponding code"
done) ))
repeat (statement eval)) "execute body until an event is encountered and run"
"the event will then force exit from the until loop"
```

This kind of playing around was part of the general euphoria that came with having a really extensible language.

It is like the festooning of type faces that happens when many fonts are suddenly available. We had both, and our early experimentation sometimes got pretty baroque.

Eventually we calmed down and started to focus on fewer, simpler structures of higher power.
