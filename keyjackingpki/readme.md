# Abstract
In theory, PKI can provide a flexible and strong way to authenticate users in distributed information systems. In practice, much is being invested in realizing this vision via tools such as client-side SSL and browser-based keystores. Exploring this vision, we demonstrate that browsers will use personal certificates to authenticate requests that the person neither knew of nor approved (in some scenarios, direct migration from password-based systems to clientside SSL makes things worse). We also demonstrate the easy permeability of these keystores, including new attacks on medium and high-security IE/XP keys. We suggest some short-term countermeasures. However, against this background, it is not clear that the current client-side infrastructure can achieve the PKI vision. A fundamental rethinking of the trust, usage, and storage model might result in more effective tools for building a PKI.

# Citation
- J. Marchesini, S.W. Smith, M. Zhao.  
  "Keyjacking: Risks of the Current Client-side Infrastructure."  
  2nd Annual PKI Resarch Workshop. NIST. April 2003.  

# Downloads
- [PDF](keyjacking.pdf)
- [Preliminary tech report](tr2003-443.pdf)
