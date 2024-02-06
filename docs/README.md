![Clearfly_Logo_Primary_FC_230x50](https://github.com/clearfly/peering.as27400.net/assets/241394/d75fa833-5853-4f23-9250-d24376f2add3)

# Clearfly Communications (AS27400) Peering Policy

Clearfly Communications (Clearfly) has an open peering policy and evaluates all potential peers on a case-by-case basis.
- Under no circumstances will Clearfly peer with an existing transit customer.
- Peers are expected to filter their sessions to reject unauthorized BGP announcements.
- Peers are expected to aggregate routes as much as possible. Clearfly will not accept any announcement longer than /24.
- Peers must not utilize any form of default route or gateway of last resort that is directed at Clearfly.
- If possible, Clearfly prefers to implement MD5 authentication on BGP peering sessions.
- If possible, Clearfly typically prefers to utilize routes learned via a route server in lieu of establishing direct peering sessions.
- Clearfly reserves the right to suspend peering for an indefinite period of time should any abuse originate from a peer. This includes, but is not limited to:
  - Exceeding configured maximum route filters
  - Any form of DoS attack
  - Unsolicited bulk email (spam)
  - Default route directed at Clearfly Communications
- Clearfly reserves the right to suspend peering due to service-affecting instability of peer devices or routes

---

### Peering & Contact Information

ASN: 27400 <br />
Peering Email: [netops@clearfly.net](mailto:netops@clearfly.net) </br>
PeeringDB Record: [https://www.peeringdb.com/asn/27400](https://www.peeringdb.com/asn/27400)
