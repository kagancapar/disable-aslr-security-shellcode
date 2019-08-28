# disable-aslr-security-shellcode

This shellcode is developed to disable ASLR security in linux operating systems.

# about aslr

address space layout randomization (ASLR)

Address space layout randomization (ASLR) is a memory-protection process for operating systems (OSes) that guards against buffer-overflow attacks by randomizing the location where system executables are loaded into memory.

The success of many cyberattacks, particularly zero-day exploits, relies on the hacker's ability to know or guess the position of processes and functions in memory. ASLR is able to put address space targets in unpredictable locations. If an attacker attempts to exploit an incorrect address space location, the target application will crash, stopping the attack and alerting the system.  

ASLR was created by the Pax Project as a Linux patch in 2001 and was integrated into the Windows operating system beginning with Vista in 2007. Prior to ASLR, the memory locations of files and applications were either known or easily determined. 

Adding ASLR to Vista increased the number of possible address space locations to 256, meaning attackers only had a 1 in 256 chance of finding the correct location to execute code. Apple began including ASLR in Mac OS X 10.5 Leopard, and Apple iOS and Google Android both started using ASLR in 2011.

