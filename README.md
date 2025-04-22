# Omelets Need Onions

## E-graphs Modulo Theories via Bottom Up E-Matching

Submission for egraphs 2025 <https://pldi25.sigplan.org/home/egraphs-2025>. Submissions are not anonymous.

pdf <https://github.com/philzook58/emt-egraphs2025/blob/main/toy.pdf>

arxiv <https://arxiv.org/abs/2504.14340>

    E-graphs are a data structure for generic equational reasoning and optimization over ground terms. One of
     the benefits of e-graph rewriting is that it can declaratively handle useful but difficult to orient identities like 
     associativity and commutativity (AC) in a generic way. However, using these generic mechanisms
      is more computationally expensive than bespoke routines. There exist specialized efficient
       algorithms and data structures for terms containing sets, multisets, linear expressions, polynomials, and binders.
        A natural question arises: How can one combine the generic capabilities of e-graph rewriting with these specialized theories?
        This talk discusses a pragmatic approach to e-graphs modulo theories (EMT) using two key ideas: bottom up e-matching and semantic e-ids.
