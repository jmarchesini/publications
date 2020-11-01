# Abstract
In 1976, Whitfield Diffie and Martin Hellman demonstrated how public key cryptography could enable secure information exchange between parties that do not share secrets. In order for public key cryptography to work in modern distributed environments, we need an infrastructure for finding and trusting other parties' public keys, i.e., a Public Key Infrastructure (PKI). While PKI applications differ in how they use keys, all applications share one assumption: users have keypairs.

This thesis begins by examining the security aspects of some of the standard keystores and their interaction with the Operating System. We establish that desktop keystores are not safe places to store private keys, and our experiments demonstrate the permeability of such keystores. Additionally, desktop keystores are immobile, difficult to use, and make it hard or impossible for relying parties to make reasonable trust judgments. We show that these problems stem from the fact that the Trusted Computing Base (TCB) of modern desktops is too large and ill-defined, which leaves standard desktops unusable as PKI clients.

Since we would like to use desktops as PKI clients and cannot realistically expect to redesign the entire desktop, this thesis presents a system that works within the confines of modern desktops to shrink the TCB needed for PKI applications. Our system is called Secure Hardware Enhanced MyProxy (SHEMP), and combines a number of techniques and technologies to shrink the TCB in space and allow the TCB's size to vary over time. In addition, the SHEMP system addresses the problems of immobility and usability, and allows relying parties to make reasonable trust judgments. Using analysis, experiments, and formal methods, we conclude that SHEMP makes standard desktops suitable for use as PKI clients.

The contributions of this thesis include the discovery of novel techniques used to identify weaknesses in modern desktops; a prototype, analysis, and correctness proof of a system which makes desktops usable as PKI clients (SHEMP); a novel approach for reasoning about TCBs; and a formal framework for proving properties of PKI systems such as SHEMP.

# Committee members:

- [Sean Smith (Advisor, CS Dept., Dartmouth College)](https://www.cs.dartmouth.edu/~sws/)
- [Hany Farid (EECS Dept., UC Berkeley)](https://farid.berkeley.edu/)
- [Doug McIlroy (CS Dept., Dartmouth College)](https://www.cs.dartmouth.edu/~doug/)
- [Leendert van Doorn (Microsoft)](https://www.paramecium.org:4443/~leendert/index.html)

# Downloads
- [PDF](thesis.pdf)
- [Summary tech report](tr2005-532-shemp.pdf)
- [Proposal tech report](tr2004-525.pdf)

# Code
- [Complete tarball](shemp.tar.gz)
- [Repository](shemp_repository.tar.gz)
- [Client](shemp_shutil.tar.gz)
