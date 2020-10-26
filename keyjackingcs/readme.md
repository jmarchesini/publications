# Abstract

In theory, PKI can provide a flexible and strong way to authenticate users in distributed information systems. In practice, much is being invested in realizing this vision via client-side SSL and various client keystores. However, whether this works depends on whether what the machines do with the private keys matches what the humans think they do: whether a server operator can conclude from an SSL request authenticated with a user's private key that the user was aware of and approved that request. Exploring this vision, we demonstrate via a series of experiments that this assumption does not hold with standard desktop tools, even if the browser user does all the right things. A fundamental rethinking of the trust, usage, and storage model might result in more effective tools for achieving the PKI vision.

# Citation
- J. Marchesini, S.W. Smith, M. Zhao.  
  "Keyjacking: The Surprising Insecurity of Client-side SSL"  
  Computers and Security.  
  Volume 24, Issue 2, March 2005.  

# Downloads
- [PDF](msz05.pdf)
- [Preliminary tech report](tr2004-489.pdf)
