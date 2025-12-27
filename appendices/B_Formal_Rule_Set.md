# 付録B (Appendix B)

## Formal Rule Set of BCCR

**Boundary-Conditioned Constraint Resolution**

---

**「規則は命令ではない。存在の条件だ。」**
*Rules are not commands. They are conditions of existence.*

---

This appendix states the formal rules governing boundary-conditioned constraint resolution. These are **necessary and jointly sufficient** for the framework to apply.

---

## B.1 Rule 1 — Constraint Primacy

> **The constraint field Φ exists independent of any particular resolution.**

```
Φ is imposed by the object.
Φ is not created by observation.
Φ is not transmitted to boundaries.
Φ pervades the relevant domain.
```

---

## B.2 Rule 2 — Boundary Dependence

> **Appearance requires boundary conditions.**

```
No B → no Ψ
The same Φ can yield different Ψ under different B.

R_B₁[Φ] ≠ R_B₂[Φ]  in general
```

---

## B.3 Rule 3 — Resolution Locality

> **R_B is computed at the boundary, not transmitted to it.**

```
R_B[Φ](x) depends only on:
  - Φ in neighborhood of x
  - B at x

No global information transport required.
```

---

## B.4 Rule 4 — No Storage

> **The boundary B holds no state.**

```
B(t) contains no memory of Φ
B(t) contains no memory of Ψ(t-dt)

Each Ψ(t) = R_B(t)[Φ] is computed fresh.
```

---

## B.5 Rule 5 — Topological Preservation

> **R_B preserves topological invariants of Φ when B is smooth.**

```
If B is continuous and |∇B| < ∞:
  Topology(Ψ) ≅ Topology(Φ)

Preserved: adjacency, continuity, ordering
Not preserved: exact geometry
```

---

## B.6 Rule 6 — Threshold Collapse

> **Identity fails discontinuously when boundary perturbation exceeds critical threshold.**

```
∃ ε_critical such that:

|δB| < ε_critical → identity preserved
|δB| > ε_critical → identity lost

The transition is sharp, not gradual.
```

---

## B.7 Rule 7 — Inversion Emergence

> **Reflection symmetry arises from boundary geometry, not from Φ.**

```
Vertical inversion: property of B (normal to surface)
Spherical inversion: property of B (curved geometry)

Φ contains structure.
B determines how it presents.
```

---

## B.8 Rule 8 — Classical Reduction

> **Classical optics emerges when B is static, planar, isotropic, and homogeneous.**

```
Under these conditions:

R_B → geometric optics (ray tracing)
R_B → wave optics (interference)
Snell's Law emerges
Fresnel equations emerge

Classical optics is a special case.
```

---

## B.9 Rule 9 — Curvature Generalization

> **The framework extends to arbitrary smooth boundaries.**

```
B = any smooth surface

Provided:
  - B is differentiable
  - |∇B| is bounded
  - B is continuous

Then R_B[Φ] exists and preserves topology.

This includes: mirrors, water, lensballs, 
              droplets, curved glass, etc.
```

---

## B.10 Rule 10 — No Representation

> **At no point is Φ encoded, stored, or represented in B.**

```
B is a boundary condition, not a medium.
B does not "contain" the image.
B does not "hold" information about Φ.

The reflection is solved, not stored.
```

---

## Summary: The Minimal Conditions

A system exhibits boundary-conditioned constraint resolution **iff**:

1. A constraint field Φ exists
2. An admissibility boundary B exists
3. Appearance Ψ = R_B[Φ]
4. Topology of Φ is preserved in Ψ (below threshold)
5. No storage occurs in B

**All five are required.**

---

## Failure Conditions

BCCR does **not** apply if:

| Condition | Result |
|-----------|--------|
| Φ does not exist | No structure to resolve |
| B is undefined | No resolution possible |
| B is discontinuous | Topology not preserved |
| |∇B| → ∞ | Resolution fails |
| Storage required | Not BCCR (different mechanism) |

---

**「規則を守れば、反射が解ける。」**
*Follow the rules, and reflection is solved.*

---

[← Back to README](../README.md)

