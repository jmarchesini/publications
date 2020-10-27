# Abstract

While PKI applications differ in how they use keys, all applications share one assumption: users have keypairs. In previous work, we established that desktop keystores are not safe places to store private keys, because the TCB is too large. These keystores are also immobile, difficult to use, and make it impossible for relying parties to make reasonable trust judgments. Since we would like to use desktops as PKI clients and cannot realistically expect to redesign the entire desktop, this paper presents a system that works within the confines of modern desktops to shrink the TCB needed for PKI applications. Our system (called Secure Hardware Enhanced MyProxy (SHEMP)) shrinks the TCB in space and allows the TCB's size to vary over time and over various application sensitivity levels, thus making desktops usable for PKI.

# Citation
- J. Marchesini, S.W. Smith.  
  "SHEMP: Secure Hardware Enhanced MyProxy"  
  3rd Annual Conference on Privacy, Security, and Trust.  
  October 2005.  

# Downloads
- [PDF](pst2.pdf)
- [Preliminary tech report](tr2005-532.pdf)
- [Related Dissertation](../shemp/readme.md)

# Code
- [https://github.com/jmarchesini/shemp]
