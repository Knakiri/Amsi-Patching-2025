## AMSI Patching (2025) - Proof of Concept

Old patch bytes that contained 0xC3 were getting flagged by AV/EDR,
so we had to work around that and use new patch bytes to bypass detection.

This is a proof-of-concept showing how to patch AmsiScanBuffer in memory 
with updated shellcode that avoids signature-based detection.

The patch includes both x64 and x86 versions.

### Disclaimer

This project is for **educational and research purposes only**.  
I do **not condone or support** any malicious use of this code.  
I am **not responsible** for any damage or misuse caused by this proof-of-concept.
