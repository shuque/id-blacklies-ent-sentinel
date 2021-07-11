# id-blacklies-ent-sentinel
Empty Non-Terminal Sentinel RR Type for Black Lies

The Black Lies method of providing compact DNSSEC denial of existence
proofs has some operational implications. Depending on the specific
implementation, it may provide no way to reliably distinguish Empty
Non-Terminal names from names that actually do not exist. This draft
describes the use of a synthetic DNS resource record type to act as an
explicit signal for Empty Non-Terminal names and which is conveyed in
an NSEC type bitmap.

Rendered versions of the current document can be found at the following links:

* [HTML] (https://www.huque.com/ietf/blacklies-ent/draft-huque-dnsop-blacklies-ent.html)
* [TEXT] (https://www.huque.com/ietf/blacklies-ent/draft-huque-dnsop-blacklies-ent.txt)
