# Abstract

In Public Key Infrastructure (PKI), the simple, monopolistic organizational model of certificate issuing entities works fine until we consider real-world issues. Then, issues such as scalability and mutually suspicious organizations create the need for a multiplicity of certificate issuing entities, which introduces the problem of how to organize them to balance resilience to compromise against efficiency of path discovery. Many solutions involve organizing the infrastructure to follow a natural organizational hierarchy, but in some cases, such a natural organizational hierarchy may not exist.

However, systems research has given us secure coprocessing for securely carrying out computations among multiple trust domains. Cryptography has produced a number of methods for distributing cryptographic computations, such as secret splitting and threshold cryptography. Last, distributed computing has given us peer-to-peer networking, for creating self-organizing distributed systems.

In this paper, we use these latter tools to address the former problem by overlaying a virtual hierarchy on a mesh architecture of peer certificate issuing entities, and achieving both resilience and efficiency.

# Citation
- J. Marchesini, S.W. Smith.  
  "Virtual Hierarchies: An Architecture for Building and Maintaining Efficient and Resilient Trust Chains."  
  Proceedings of the 7th Nordic Workshop on Secure IT Systems (NORDSEC 2002).  
  Karlstad University Studies. November 2002  

# Downloads
- [PDF](VirtualHierarchies.pdf)
- [Preliminary tech report](tr2002-416.pdf)
- [Presentation](vhire.pdf)
