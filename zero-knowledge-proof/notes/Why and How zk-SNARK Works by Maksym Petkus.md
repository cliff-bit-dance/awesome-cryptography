<script src="//yihui.org/js/math-code.js" defer></script>
<!-- Just one possible MathJax CDN below. You may use others. -->
<script defer
  src="//mathjax.rstudio.com/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

## Introduction

A protocol should satisfy three properties:
• Completeness — if the statement is true then a prover can convince a verifier
• Soundness — a cheating prover can not convince a verifier of a false statement
• Zero-knowledge — the interaction only reveals if a statement is true and nothing else

The zk-SNARK term itself was introduced in [Bit+11](#References), building on [Gro10] with following Pinocchio protocol [Gen+12] [Par+13] making it applicable for general computing.

Hi `$z = x + y$`.


## References
- [Bit+11] Nir Bitansky, Ran Canetti, Alessandro Chiesa, and Eran Tromer. From Extractable Collision Resistance to Succinct Non-Interactive Arguments of Knowledge, and Back Again. Cryptology ePrint Archive, Report 2011/443. https://eprint.iacr.org/ 2011/443. 2011.
- [Gro10] Jens Groth. “Short pairing-based non-interactive zero-knowledge arguments”. In:
International Conference on the Theory and Application of Cryptology and Infor-
mation Security. Springer. 2010, pp. 321–340.
- [Gen+12] Rosario Gennaro, Craig Gentry, Bryan Parno, and Mariana Raykova. Quadratic Span Programs and Succinct NIZKs without PCPs. Cryptology ePrint Archive, Re- port 2012/215. https://eprint.iacr.org/2012/215. 2012.
- [Par+13] Scott Pike. Evaluating Polynomial Functions. 2013. url: http://www.mesacc.edu/ ~scotz47781/mat120/notes/polynomials/evaluating/evaluating.html (visited on 2018-05-01).