# Shamir's Secret Sharing Algorithm (Simplified Version)

This project implements a simplified version of **Shamir's Secret Sharing Algorithm** using JavaScript. The algorithm takes encoded roots of a polynomial and solves for the constant term using Lagrange interpolation.

## Features
- Read test cases from a JSON file.
- Decode y-values that are encoded in different bases.
- Calculate the constant term `c` using Lagrange interpolation.

## Getting Started

### Prerequisites

Make sure you have **Node.js** installed on your system. You can check if Node.js is installed by running:

```bash
node -v
