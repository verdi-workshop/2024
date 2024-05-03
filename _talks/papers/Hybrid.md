---
name: 'Hybrid Hardware/Software Detection of Multi-Bit Upsets in Memory'
speakers:
  - Robin Thunig
  - Christoph Borchert
  - Urs Kober
  - Horst Schirmeier
room: 'DSN2024'
categories:
  - Short papers
---


Bit flips in main memory can be caused by a multitude of environmental effects, such as heat or radiation, as well as by malicious actors exploiting Rowhammer-style hardware vulnerabilities. The industry-standard countermeasure is SEC-DED ECC memory, which can reliably correct single- and detect double-bit flips in a data word. However, larger multi-bit upsets (MBUs) regularly occur in real-world systems, and – as shown by an analysis in this paper – have a high probability of being miscorrected. Software-implemented hardware fault tolerance (SIHFT) mechanisms can flexibly handle MBUs, but incur significant runtime costs.
In this paper, we propose to combine hardware ECC as a low-cost detector and SIHFT as a handler for miscorrected MBUs that recategorizes them as uncorrectable. A preliminary evaluation on the basis of differential checksums demonstrates a miscorrected-SDC reduction of 98 % at a very moderate execution-time overhead.

