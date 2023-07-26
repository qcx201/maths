
# Abstract Algebra


**Definition.**
Let $G$ be a set and let $\star$ be an operation on $G$.

1. The ordered pair $(G, \star)$ is a **group** if the following axioms are satisfied:

    i. The operation $\star$ is *associative*:   
    $
    \quad
    \forall a, b, c \in G, \quad
    (a \star b) \star c = a \star (b \star c)
    $.

    ii. $G$ has an *identity* element:       
    $
    \quad
    \exists e \in G, \quad
    e \star a = a \star e = a.
    $
        
    iii. Each element of $G$ has an *inverse*:   
    $
    \quad
    \forall a \in G, \quad
    \exists a^{-1} \in G, \quad
    a \star a^{-1} = a^{-1} \star a = e.
    $

2. A group $(G, \star)$ is **abelian** (or **commuatative**) if   
    $
    \quad
    \forall a, b \in G, \quad
    a \star b = b \star a.
    $

For elements $a, b \in G$ of a group $G$ under an operation $\star$, we may write $a \star b$ with the short-hand $a b$.

**Propositions.** Let $G$ be a group.

1. There is a unique identity $e \in G$.


    *Proof.*
    Let $e, e' \in G$ both be identity elements. Then $e e' = e = e'$ by definition of the identity.
    
    $\square$


2. Each $a \in G$ has an unique inverse $a^{-1} \in G$.

    *Proof.*
    Let $b, c \in G$ both be inverses of $a \in G$, and let $e \in G$ be the identity. Then $a b = e$ and $c a = e$, and
    $$
    c
    = c e
    = c (a a^{-1})
    = c (a b)
    = (c a) b
    = e b
    =
    b.
    $$
    $\square$

3. For each $a \in G, \quad (a^{-1})^{-1} = a$.

    *Proof.*
    We have that
    $$
    a
    = a e
    = a (a^{-1} (a^{-1})^{-1})
    = (a a^{-1}) (a^{-1})^{-1}
    = e (a^{-1})^{-1}
    = (a^{-1})^{-1}
    $$
    $\square$

4. For each $a, b \in G, \quad (a b)^{-1} = b^{-1} a^{-1}$

    *Proof.*
    We have that
    $$
    a^{-1}
    = a^{-1} e
    = a^{-1} ((a b)(a b)^{-1})
    = (a^{-1} (a b))(a b)^{-1}
    = ((a^{-1} a) b)(a b)^{-1}
    = (e b)(a b)^{-1}
    = b (a b)^{-1}.
    $$
    Thus
    $$
    b^{-1} a^{-1}
    = b^{-1} (b (a b)^{-1})
    = (b^{-1} b) (a b)^{-1}
    = e (a b)^{-1}
    = (a b)^{-1}.
    $$
    $\square$