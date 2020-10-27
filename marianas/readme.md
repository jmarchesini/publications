# Abstract
We are currently developing Marianas, a survivable peer-to-peer network of commercial off-the-shelf computing nodes, each endowed with a secure coprocessor, that collectively implements a distributed trusted third party. Marianas is particularly focused on providing a trust backbone for critical infrastructure applications, which may include electrical power systems, air traffic control systems, internet routing infrastructure, as well as commercial electronic commerce interactions. It provides a means of protecting the most sensitive elements of infrastructure control from insider attack, and provides means of authenticating the results of a remotely executed computation, even if one cannot trust the host responsible for the computation.

Every Marianas node has a secure coprocessor. Commercially available today, this device contains specialized hardware to accelerate cryptographic operations, and specialized memory that is zeroed out in the event the device is physically tampered with. Inside of this protected memory is the private portion of a cryptographic key-pair, enabling the device (through cryptographic signature done within this proected space) to serve as a trusted third party---even if its own host is hostile to it.

However, using a trusted third party in critical infrastructure raises fundamental challenges:

- How do we build a trusted third party, in a heterogeneous network owned and operated by heterogeneous parties?
- How do we build a trusted third party that can survive the attacks that it is intended to defend against?
- How do we ensure that applications running on the secure coprocessor cannot themselves corrupt it---even if multiple applications share the device simultaneously?
- How can we convincingly establish that our system---or any similar system---works as intended?

The presentation will introduce the key notions behind Marianas, explore some of the issue enumerated above, and discuss results from our preliminary implementation of Marianas.

# Downloads
- [Presentation](p2p.ppt)
