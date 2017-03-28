# Description

*Note: this description is under discussion, to be finalized shortly after IETC 98 in Chicago*

The IP Stack Evolution program covers various topics in the evolution of
IPv4 and IPv6, the transport protocols running over IP, and the overall
protocol stack architecture. The program addresses challenges that
affect the stack in some way and where the IETF community requires
architectural guidance, responding to community requests as well as
actively monitoring work within IETF WGs which touch on relevant topics.
Where a working group relevant to a particular aspect of IP stack
evolution exists, the program will facilitate cross-group and cross-area
coordination. The program also produces documents on the IAB stream
providing general guidance on and covering architectural aspects of
stack evolution.

The diversity of "endpoints" in the Internet -- applications,
transport-layer ports, hosts, gateways and tunnel ends -- is far greater
than that the IP protocol stack was originally intended to serve. This
has impacts on protocol design, because former assumptions about the
properties of these endpoints may no longer hold. The program is currently
focusing on the stress this places on the architecture.

The program has focused for the past few years on the problem of
ossification in the IP protocol stack, specifically at the transport
layer. Since the founding of this program, there is significant new work
in the IETF's transport area addressing this issue; the program's
members participate in work in the IETF, and monitor it on behalf of the
IAB, with an eye toward architectural oversight. The program also
provides a point of contact on architectural issues arising from
interaction between these new transport protocols and the rising
diversity of link layers deployed in the Internet.

## Current Active work

*Note: this list is under discussion, to be finalized at the Montreal retreat at the latest*

- Discussion of principles for making new protocols within the IP stack
  deployable, following in part on RFC 5218 “What Makes for a Successful
  Protocol”. This has resulted in 
  [draft-iab-protocol-transitions](https://datatracker.ietf.org/doc/draft-iab-protocol-transitions/), 
  now awaiting publication.
- Discussion of principles for the use of encapsulation at various layers
  within the protocol stack. UDP-based encapsulations are not only useful for
  evolution above the IP layer, but in many tunneling contexts as well. The
  probable commonalities among all these applications of encapsulation might be
  useful in simplifying their implementation, deployment, and use.
- Architectural guidance on the interoperability of protocol stacks for use in
  constrained devices, focusing on issues related to mutually incompatible
  interactions among application, transport, network, and link layer protocols.

## Past Workshops, BoFs, etc.

The Program has organized several workshops, Birds of a Feather sessions, and proposed Research Groups on topics related to its areas of work:

- The IAB workshop on [Stack Evolution in a Middlebox Internet (SEMI)](https://www.iab.org/activities/workshops/semi/) in Zurich,
  January 2015. Read the Workshop Report, [RFC 7663](https://tools.ietf.org/html/rfc7663)
- The [Substrate Protocol for User Datagrams (SPUD) BoF](https://datatracker.ietf.org/wg/spud/about/) 
  at IETF 92 in Dallas, March 2015; which in turn led to the 
  [Path Layer UDP Substrater (PLUS) BoF](https://datatracker.ietf.org/wg/plus/about/) at
  IETF 96 in Berlin, July 2016.
- The [Managing Radio Networks in an Encrypted World (MaRNEW) Workshop](https://www.iab.org/activities/workshops/marnew/) 
  in Atlanta, September 2015, together with GSMA; which in turn led to the 
  [Alternatives to Content Classification for Operator Resource Deployment (ACCORD) BoF](https://datatracker.ietf.org/wg/accord/about/) 
  at IETF 95 in Buenos Aires, April 2016.
- The Measurement and Analysis for Protocols (MAP) Research Group has
  been meeting since IETF 93 in Prague (until IETF 94 in Yokohama as “How
  Ossified is the Protocol Stack?” (HOPS) proposed RG). Discussion is at
  <[maprg@irtf.org](mailto:maprg@irtf.org)>.

# Documents Published

- Technical Considerations for Internet Service Blocking and Filtering ([RFC 7754](https://tools.ietf.org/html/rfc7754))

This program has itself evolved from the IP Evolution Program, which looked at general architectural issues in the evolution of IPv4 and IPv6 and the overall protocol stack architecture, and produced the following documents:

- IAB Thoughts on IPv6 Network Address Translation ([RFC 5902](https://tools.ietf.org/html/rfc5902))
- Evolution of the IP Model ([RFC 6250](https://tools.ietf.org/html/rfc6250))
- Smart Objects Workshop Report ([RFC 6574](https://tools.ietf.org/html/rfc6574))
- Architectural Considerations of IP Anycast ([RFC 7094](https://tools.ietf.org/html/rfc7094))
- Report from the IAB Workshop on Internet Technology Adoption and Transition (ITAT) ([RFC 7305](https://tools.ietf.org/html/rfc7305))
