# Description of Files

This repository contains Eugene files specifying designs for the repressilator (Elowitz and Leibler), recombinase state machines (RSMs) (Roquet et al.) , and dual-feedback oscillator (Stricker et al.). In particular, one design is specified for the repressilator, eight designs are specified for 2 input, 5 state RSMs, three designs are specified for 3 input, 16 state RSMs, and six designs are specified for the dual-feedback oscillator. The vector backbone and input plasmids of the RSMs are not included. The RSM designs are unique, non-permuted variants, while the oscillator designs vary the order of the same three transcriptional units with alternating orientations.

# Issues with Eugene

1. The product function cannot be applied to composite devices (that is, devices containing other devices).

2. A DnaComponent of type CDS (Sequence Ontology term SO:0000316) is exported by default whenever a part with a type unknown to Eugene is encountered. A more appropriate type would be engineered region (SO:0000804).

# References

Michael B. Elowitz and Stanislas Leibler, ``A synthetic oscillatory network of transcriptional regulators,'' in Letters to Nature, vol. 403, pp. 335-338, 2000.

Nathaniel Roquet, Ava P. Soleimany, Alyssa C. Ferris, Scott Aaronson, and Timothy K. Lu, ``Synthetic recombinase-based state machines in living cells,'' in Science, vol. 353, 2016.

Jesse Stricker, Scott Cookson, Matthew R. Bennett, William H. Mather, Lev S. Tsimring, and Jeff Hasty, ``A fast, robust and tunable synthetic gene oscillator,'' in Nature, vol. 456, 2008.