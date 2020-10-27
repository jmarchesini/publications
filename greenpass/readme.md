# Abstract

In Dartmouth's "Greenpass" project, we're building an experimental system to explore two levels of authorization issues in the emerging information infrastructure. On a practical level, we want to enable only authorized users to access an internal wireless network while also permitting appropriate users to delegate internal access to external guests, and doing this all with standard client software. On a deeper level, PKI needs to be part of this emerging information infrastructure since sharing secrets is not workable. However, the traditional approach to PKI---with a centralized hierarchy based on global names and heavy-weight X.509 certificates---has often proved cumbersome. On this level, we want to explore alternative PKI structures that might overcome these barriers.

By using SPKI/SDSI delegation on top of X.509 certificates within EAP-TLS authentication, we provide a flexible, decentralized solution to guest access that reflects real-world authorization flow, without requiring guests to download nonstandard client software. Within the "living laboratory" of Dartmouth's wireless network, this project lets us solve real problem with wireless networking, while also experimenting with trust flows and testing the limits of current tools.

# Citation

- N. Goffee, S. Kim, S.W. Smith, P. Taylor, M. Zhao, J. Marchesini.  
  "Greenpass: Decentralized, PKI-based Authorization for Wireless LANs."  
  3rd Annual PKI Research and Development Workshop.  
  NIST. April 2004.  

# Downloads

- [PDF](gks04.pdf)
- [Preliminary tech report](greenpass.pdf)
