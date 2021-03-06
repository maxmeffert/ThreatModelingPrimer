---
marp: true
theme: minimal
paginate: true
header: 'Thread Modeling - A Primer'
footer: 'Maximilian Meffert (c) 2020'
---

# Threat Modeling
## A Primer

---

### Disclaimer

**This presentation describes a simplified version of _Threat Modeling_.**

---

### References

* [OWASP Threat Modeling Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Threat_Modeling_Cheat_Sheet.html)
* [OWASP Attack Surface Analysis Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Attack_Surface_Analysis_Cheat_Sheet.html)
* [Wikipedia Information Security](https://en.wikipedia.org/wiki/Information_security)
* [Wikipedia STRIDE](https://en.wikipedia.org/wiki/STRIDE_%28security%29)
* [MSDN STRIDE](https://docs.microsoft.com/en-us/previous-versions/commerce-server/ee823878(v=cs.20)?redirectedfrom=MSDN)

---

### (Information) Assets
Entites of (financial) value.

---

<style scoped>
li {
    margin: 3px
}
</style>

### Information Security

The _CIA Triad_ of primary security goals*.

* __Confidentiality__
An Information must not be available or be disclosed to unauthorized individuals, entities or processes.
* __Integrity__
Accuracy and completeness of an information must be assured over its lifetime.
* __Availability__
An Information must be avaiblabe when needed.

_*FYI: The terms security attributes/properties/aspects/criteria may also be used._

---

<style scoped>
li {
    margin: 3px
}
</style>

### More Information Security

Secondary/derived security goals:

* __Authenticity__
Correctness/Trustworthiness can be verified*.
* __Non Repudiation__
Operations cannot be denied by any party.
* __Accountability__
Operators can be clearly identified.
* __Anonymity__
Operators cannot be identified.

_*FYI: The term **Verification** implies provability, this demands more than just a simple review which would be just **Validation**._ Thus,  colloquial 

---

### Even More Informatin Security

GDPR (DSGVO) security goals:

* __Resilience__
Robustness against surveillance and sabotage.

More or less a combination of all other security goals because... EU lawyers, i guess...

---

### STRIDE

A model of threats developed by Praerit Garg and Loren Kohnfelder* at Microsoft.

|| Threat | Security Goal | 
|:-|:-|:-|
| __S__ | Spoofing Identities | Authenticity |
| __T__ | Tampering with Data | Integrity |
| __R__ | Repudiation | Non-Repudiation|
| __I__ | Information Disclosure | Confidiality |
| __D__ | Dinial of Service | Availability |
| __E__ | Elevation of Privilege | Confidiality, Integrity, Availability |

_*FYI: Loren Kohnfelder is more or less the father of PKIs and X.509 certificates._

---
### STRIDE Threats

|| Threat | Short Definition | 
|:-|:-|:-|
| __S__ | Spoofing Identities | Successfully identify with another identity. |
| __T__ | Tampering with Data | Intentional modification of data. |
| __R__ | Repudiation | Sucessfully deny performing an action.|
| __I__ | Information Disclosure | Disclosure of information to unauthorized parties. |
| __D__ | Dinial of Service | Prevent legitimate use of a service/resource. |
| __E__ | Elevation of Privilege | Gain elevated access to otherwise protected resources. |

---

### Spoofing Identities

> Successfully identify with another identity.

#### Example

TODO

---

### Tampering with Data

> Intentional modification of data.

#### Example

TODO

---

### Repudiation

> Sucessfully deny performing an action.

#### Example

TODO

---

### Information Disclosure

> Disclosure of information to unauthorized parties.

#### Example

TODO

---

### Dinial of Service

> Prevent legitimate use of a service/resource.

#### Example

TODO

---

### Elevation of Privilege

> Gain elevated access to otherwise protected resources.

#### Example

TODO

---

### Example

---

# Thanks!