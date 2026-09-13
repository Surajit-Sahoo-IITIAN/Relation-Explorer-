# Relations Explorer

An interactive visualization for **Discrete Mathematics & Graph Theory** that helps students understand the progression from a relation to an equivalence relation, equivalence classes, and partitions.

## What Students Can Explore

The visualization follows the mathematical flow:

\[
\boxed{
\text{Relation}
\rightarrow
\text{Relation Properties}
\rightarrow
\text{Equivalence Relation}
\rightarrow
\text{Equivalence Classes}
\rightarrow
\text{Partition}
}
\]

### 1. Build a Relation

Choose a finite set

\[
A=\{1,2,\ldots,n\}
\]

and construct a relation

\[
R\subseteq A\times A.
\]

Students can click the cells of the relation matrix to include or remove ordered pairs.

The visualization simultaneously displays:

- Relation matrix
- Ordered-pair representation
- Directed graph (digraph)

### 2. Check Properties of the Relation

The relation is automatically checked for:

- **Reflexive**
- **Symmetric**
- **Antisymmetric**
- **Transitive**

When a property is violated, the visualization explains **why**.

For example, for transitivity:

\[
1R2,\qquad 2R3
\]

but

\[
1\not R3,
\]

the visualization identifies this as a violation of transitivity.

### 3. Equivalence Relation

A relation is an equivalence relation precisely when it is:

\[
\boxed{
\text{Reflexive + Symmetric + Transitive}
}
\]

Once these three properties are satisfied, the visualization identifies the relation as an **Equivalence Relation**.

### 4. Equivalence Classes

For an equivalence relation \(R\), the visualization generates the equivalence classes

\[
[a]=\{x\in A:xRa\}.
\]

Students can click an equivalence class to highlight its elements in the digraph.

This helps visualize how an equivalence relation groups elements of a set.

### 5. Partition

The equivalence classes are displayed as the corresponding partition of \(A\).

The visualization checks the three important properties of a partition:

- Every block is non-empty.
- The blocks together cover \(A\).
- Distinct blocks are pairwise disjoint.

Thus students can visually understand the fundamental correspondence

\[
\boxed{
\text{Equivalence Relations}
\Longleftrightarrow
\text{Partitions}
}
\]

## Built-in Examples

The visualization includes several examples:

- Equality relation
- \(\leq\) relation
- \(<\) relation
- Same remainder when divided by 2
- A simple non-transitive relation

These examples allow students to compare different relation properties.

## Interactive Relation Matrix

For a set \(A\), the matrix represents the relation \(R\).

A matrix entry

\[
m_{ij}=1
\]

means

\[
(a_i,a_j)\in R,
\]

while

\[
m_{ij}=0
\]

means

\[
(a_i,a_j)\notin R.
\]

Clicking a matrix cell immediately updates the relation and all corresponding visualizations.

## Set Size

Students can work with sets containing:

\[
2,\ 3,\ 4,\ \text{or }5
\]

elements.

## Scope

This visualization intentionally focuses only on:

\[
\boxed{
\text{Relations}
\rightarrow
\text{Equivalence Relations}
\rightarrow
\text{Equivalence Classes}
\rightarrow
\text{Partitions}
}
\]

**Partial orders, posets, and Hasse diagrams are not included**, as they are covered separately in the course's Boolean-lattice / poset visualization.

## Running Locally

No installation or external libraries are required.

Simply open:

```text
index.html
