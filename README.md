*This is work in progress. Expect nothing.*

![Acygtus](https://github.com/BPSB/Acygtus/blob/main/Deliverables/self-rendered.png?raw=true)

[Download link](https://github.com/BPSB/Acygtus/blob/main/Deliverables/Acygtus-Regular.otf?raw=true)

### Why and what?

Specific DNA sequences and similar are usually displayed like this ([nucleic-acid notation](https://en.wikipedia.org/wiki/Nucleic_acid_notation)):

> GCGGTCATTCACAAATGCTCGCCTTGCTCTCTTATTCTAAGCGTATTTCG

Reading this sucks for the same reason that reading anything in all-caps sucks:
There are no ascenders, descenders, or other structure for your eye to orient itself.
[Several suggestions](https://en.wikipedia.org/wiki/Nucleic_acid_notation#Alternative_visually_enhanced_notations) for different notations have been made, but none of these has taken hold, probably because there is a considerable adaptation effort:
People would have to learn completely new symbols before they can read anything.

Acygtus is a font that attempts to address this problem by introducing a vertical structure:

* _A_ and _G_ have ascenders (and no descenders)
* _C, T,_ and _U_ have descenders (and no ascenders)
* Letters for degenerate bases _(B, D, H, K, M, N, R, S, V, W,_ and _Y)_ have neither ascenders nor descenders.

Since Acygtus is still based on regular capital letters, there is no adaptation threshold:
Everybody can instantly read it.

### Design principles

* Opposing bases _(G_ vs. _C_ and _A_ vs. _T/U)_ differ in having ascenders/descenders.
* _C_ and _G_ are also clearly distinguishable beyond vertical offset.
* Monospace to enable alignment of different sequences.
* Metrics are based on [Deja Vu Sans Mono](https://en.wikipedia.org/wiki/DejaVu_fonts). Thus Acygtus should directly harmonise with that typeface and similar ones.
* Letters for degenerate bases are designed to avoid visual similarities, e.g., _V_ vs. _W_ and _D_ vs. _B_ vs. _R._

### Why not use colour?

Another approach to this issue is using different colours for the different bases.
While this is all nice and proper, colour cannot be used for other illustrative purposses anymore.
If colour is not needed to denote something else, both approaches can be combined as well.
