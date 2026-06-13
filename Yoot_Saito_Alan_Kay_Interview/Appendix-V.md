# Appendix V: Smalltalk-76 Internal Structures

> Source note: Markdown rendering from the local OCR/plain-text transcription. Bret Victor's HTML edition of the paper is at [The Early History Of Smalltalk](https://worrydream.com/EarlyHistoryOfSmalltalk/), with the scanned original linked from that page.

![Smalltalk-76 internal structures](Appendix-V-Figure-1.png)

This shows how [Smalltalk-76](Technologies.md#smalltalk) was implemented. In the center, between "static" and "dynamic" lies a byte-com-piled method of Class Rectangle. Slightly above it is the source text string written by the programmer. The method tests to see whether a point is contained in the rectangle. In the dynamic part, the program counter is just starting to execute the first less-than. This general scheme goes all the way back to the B5000 and the FLEX machine, but is considerably more refined.
