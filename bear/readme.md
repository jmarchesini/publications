# Abstract
Over the last few years, our group has been working on applications of secure coprocessors---but has been frustrated by the limited computational environment and high expense of such devices. Over the last few years, the TCPA (now TCG) has produced a specification for a trusted platform module (TPM)---a small hardware addition intended to improve the overall security of a larger machine (and tied up with a still-murky vision of Windows-based trusted computing). Some commodity desktops now come up with these TPMs.

Consequently, we began an experiment to see if (in the absence of a Non-Disclosure Agreement) we could use this hardware to transform a desktop Linux machine into a virtual secure coprocessor: more powerful but less secure than higher-end devices. This experiment has several purposes: to provide a new platform for secure coprocessor applications, to see how well the TCPA/TCG approach works, and (by working in open source) to provide a platform for the broader community to experiment with alternative architectures in the contentious area of trusted computing.

This paper reports what we have learned so far: the approach is feasible, but effective deployment requires a more thorough look at OS security.

# Citation
- John Marchesini, Sean W. Smith, Omen Wild, Rich MacDonald.  
  "Experimenting with TCPA/TCG Hardware, Or: How I Learned to Stop Worrying and Love The Bear"  
  Technical Report TR2003-476, Department of Computer Science, Dartmouth College.  
  December 2003.  

# Downloads
- [PDF](tr2003-476.pdf)
- [Preliminary tech report](tr2003-471.pdf)

# Code
- [Sourceforge page](http://enforcer.sourceforge.net)
