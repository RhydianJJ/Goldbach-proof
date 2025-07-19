# The Goldbach Test — A Constructive Proof of Goldbach’s Conjecture

This repository contains a constructive, elementary proof of the binary Goldbach Conjecture, developed by *Rhydian Jenkins* in July 2025.

The method uses:
- A symmetric shell framework centered at \( n \),
- A modular sieve to define a survivor set \( S_n \),
- Dusart’s 1999 prime bounds to guarantee a prime in \( (n, n + n / (25 \log^2 n)) \),
- A contradiction-based argument that ensures both \( n - r \) and \( n + r \) are prime for at least one radius \( r \in S_n \).

## Contents
- goldbach_proof.pdf — Full LaTeX paper with definitions, theorems, and constructive proof
- goldbach_test.py — Python implementation that verifies the result at extreme scale

## Timestamp
This repository was created on *[insert today's date]* as a public record of authorship and priority.

## Author
*Rhydian Jenkins*  
United Kingdom  
(optional: contact, link to GitHub profile or personal site)
