# Goldbach √E Prime Prediction

This project presents a minimal JavaScript-based implementation of a novel predictive method for finding Goldbach pairs (p, q) such that p + q = E, where E is an even number. The algorithm focuses on the square root of E (√E) to narrow down candidate primes efficiently, enabling factorization of even numbers far beyond traditional JavaScript limits.

The current implementation runs directly from `index.html` without external JavaScript files, and has been successfully tested up to 10¹⁵–10¹⁸ on modern browsers.

## How It Works

- You enter a large even number E.
- The algorithm predicts likely primes (p, q) around √E using mathematical guidance.
- It outputs a valid Goldbach decomposition: p + q = E, with both p and q primes.

## Creator

This method and implementation were developed by **Bahbouhi Bouchaib**, an independent researcher based in Nantes, France.

## Live Demo

[Click here to try the live version](https://bouchaib542.github.io/Goldbach-Sqrt-Prediction/)

## License

MIT
