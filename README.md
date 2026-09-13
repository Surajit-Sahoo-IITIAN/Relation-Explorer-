# Relations Explorer

An interactive visualization for **Discrete Mathematics & Graph Theory** that helps students understand the progression from a relation to an equivalence relation, equivalence classes, and partitions.

## What Students Can Explore

The visualization follows the mathematical flow:

**Relation → Relation Properties → Equivalence Relation → Equivalence Classes → Partition**

---

## 1. Build a Relation

Choose a finite set:

**A = {1, 2, ..., n}**

and construct a relation:

**R ⊆ A × A**

Students can click the cells of the relation matrix to include or remove ordered pairs.

The visualization simultaneously displays:

- Relation matrix
- Ordered-pair representation
- Directed graph (digraph)

---

## 2. Check Properties of the Relation

The relation is automatically checked for:

- **Reflexive**
- **Symmetric**
- **Antisymmetric**
- **Transitive**

When a property is violated, the visualization explains **why**.

For example, for transitivity:

**1 R 2** and **2 R 3**

but

**1 ↛ 3**

the visualization identifies this as a violation of transitivity.

---

## 3. Equivalence Relation

A relation is an **equivalence relation** precisely when it is:

**Reflexive + Symmetric + Transitive**

Once these three properties are satisfied, the visualization identifies the relation as an **Equivalence Relation**.

---

## 4. Equivalence Classes

For an equivalence relation R, the visualization generates the equivalence classes:

**[a] = {x ∈ A : x R a}**

Students can click an equivalence class to highlight its elements in the digraph.

This helps visualize how an equivalence relation groups elements of a set.

---

## 5. Partition

The equivalence classes are displayed as the corresponding partition of A.

The visualization checks the three important properties of a partition:

- Every block is non-empty.
- The blocks together cover A.
- Distinct blocks are pairwise disjoint.

Thus students can visually understand the fundamental correspondence:

**Equivalence Relations ⇔ Partitions**

---

## Built-in Examples

The visualization includes several example relations:

- **Equality relation**
- **≤ relation**
- **< relation**
- **Same remainder when divided by 2**
- **A simple non-transitive relation**

These examples allow students to compare different relation properties.

---

## Interactive Relation Matrix

For a set A, the matrix represents the relation R.

A matrix entry:

**mᵢⱼ = 1**

means:

**(aᵢ, aⱼ) ∈ R**

while:

**mᵢⱼ = 0**

means:

**(aᵢ, aⱼ) ∉ R**

Clicking a matrix cell immediately updates:

- The relation
- The ordered pairs
- The digraph
- The property checks
- The equivalence classes
- The partition

---

## Set Size

Students can work with sets containing:

**2, 3, 4, or 5 elements**

---

## Scope

This visualization intentionally focuses only on:

**Relations → Equivalence Relations → Equivalence Classes → Partitions**

**Partial orders, posets, and Hasse diagrams are not included**, as they are covered separately in the course's Boolean-lattice / poset visualization.

---

## Running Locally

No installation or external libraries are required.

Simply open:

```text
index.html
