# Unimodality of Forest Independence Polynomials

Computational verification materials for the arXiv manuscript by **Tong Zhang and Wei Li**.

Start with the [versioned verification guide](companion/2026-09-27/README.md).
It contains exact certificate checkers, fixed input data, a complete reproduction
record, the detailed proof reference, and SHA-256 checksums.

The mathematical arguments reduce the theorem to completely specified discrete
and continuous proof obligations. The entry point verifies their certificates;
it does not test the theorem by enumerating forests. The written reductions
remain part of the proof, which has not been formalized in a proof assistant.

## Reproduce

Clone or download this repository, enter `companion/2026-09-27/`, and run:

```sh
python -S anc/proof_reproduce.py --work /path/to/empty-work
```

Use a new or empty work directory outside `anc/`, and keep Python assertions
enabled. The recorded complete run used Python 3.12.14. The versioned guide
explains all output fields, fixed inputs and authenticated diagnostic omissions.

## Version

The fixed companion version is **2026-09-27**. Cite the exact Git commit snapshot
used with the manuscript. The 60-page detailed reference preserves the fuller
certificate exposition; its section and equation numbering belongs to that
reference version.

Corresponding author: Wei Li, liw@nwpu.edu.cn.  
Tong Zhang: TongZhang@nwpu.edu.cn.

School of Mathematics and Statistics, Northwestern Polytechnical University,
Xi’an, Shaanxi, 710129, P. R. China.
