# Post-Termination Services

**Contributor**: Neel Guha (nguha@stanford.edu)

**Source**: [Atticus Project](https://www.atticusprojectai.org/cuad>)

**License**: [CC By 4.0](https://creativecommons.org/licenses/by/4.0/)

**Task summary**: Does the clause subject a party to obligations after the termination or expiration of a contract, including any post-termination transition, payment, transfer of IP, wind-down, last-buy, or similar commitments?

**Size (samples)**: 816

## Task Description

This is a binary classification task in which the model must determine if a contractual clause falls under the category of "Post-Termination Services".

## Task Construction

This task was constructed from the [CUAD dataset](https://www.atticusprojectai.org/cuad), which annotated clauses in 500 contracts according to 41 types. Positive samples for this task correspond to clauses for which annotators answered the following question in the affirmative:

```text
Does the clause subject a party to obligations after the termination or expiration of a contract, including any post-termination transition, payment, transfer of IP, wind-down, last-buy, or similar commitments?
```

Negative samples are randomly selected from other clauses.

## Column names

- `label`: whether the clause is an instance of the type ("Yes") or not ("No")
- `text`: text of contractual clause