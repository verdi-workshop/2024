---
name: 'Open Compliance in Multiparty Sessions'
speakers:
  - Franco Barbanera
  - Mariangiola Dezani-Ciancaglini
  - Ugo De'Liguoro
categories:
  - Types & Choreographies
links:
  - name: https://link.springer.com/chapter/10.1007/978-3-031-20872-0_13
    absolute_url: https://link.springer.com/chapter/10.1007/978-3-031-20872-0_13
    icon: newspaper
---

**Presenter**: Franco Barbanera  
**Session Chair**: Emílio Tuosto

Multiparty sessions are a foundational model for distributed entities interacting through message passing. Communication is disciplined by global types, which ensures lock-freedom for participants following the described protocols. A key issue is the composition of well-typed sessions, that we face via the participants-as-interfaces approach. We study session composition when a client-system is connected with compliant server systems, where compliance is naturally biased towards the client. We prove that, if the sessions are well-typed and the compliance relation can be proved, then a unique session can be constructed by transforming the interface participants of the client and the servers into gateways (forwarders). Such a session has a global type that can be derived from the global types of the composing sessions and the proof of compliance among the client and the servers. We consider the present study as a further step toward a theory of Open MultiParty Session Types.
