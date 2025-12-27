# 付録D (Appendix D)

## Symbol Index

**Mathematical Notation Used in BCCR**

---

### Primary Symbols

| Symbol | Name | Definition | First Appears |
|--------|------|------------|---------------|
| Φ | Constraint Field | Relational structure imposed by stable object | Ch. 2.0 |
| B | Admissibility Boundary | Surface defining permitted resolutions | Ch. 3.0 |
| B(t) | Dynamic Boundary | Time-varying admissibility surface | Ch. 4.0 |
| R_B | Resolution Operator | Maps Φ to Ψ given B | Ch. 3.0 |
| Ψ | Resolved Appearance | Output of R_B[Φ]; what is seen | Ch. 3.0 |
| ε_critical | Critical Threshold | Maximum |∇B| for identity preservation | Ch. 4.0 |

---

### Derived Symbols

| Symbol | Meaning |
|--------|---------|
| R_B[Φ] | Resolution of Φ through B |
| R_B₁[Φ] | Resolution through first boundary (e.g., air) |
| R_B₂[Φ] | Resolution through second boundary (e.g., water) |
| R_B(t)[Φ] | Resolution through time-varying boundary |
| R_B^sphere[Φ] | Resolution through spherical boundary |
| δB(t) | Perturbation of boundary from mean |
| B₀ | Mean boundary level |
| ∇B | Gradient of boundary (steepness) |
| |∇B| | Magnitude of boundary gradient |

---

### Classical Optics Symbols (For Reference)

| Symbol | Meaning |
|--------|---------|
| n₁, n₂ | Refractive indices |
| θ₁, θ₂ | Angles of incidence/refraction |
| E | Electromagnetic field |
| r_s, r_p | Fresnel reflection coefficients |

---

### Operators

| Notation | Meaning |
|----------|---------|
| R_B : Φ → Ψ | R_B maps constraint field to appearance |
| Topology(·) | Topological invariants of argument |
| ≅ | Topologically equivalent |
| ∘ | Composition of boundaries |

---

### Conventions

| Convention | Meaning |
|------------|---------|
| Subscript | Specifies which boundary |
| (t) | Time dependence |
| ^sphere | Spherical geometry |
| [ ] | Operator acting on argument |
| → | Maps to / produces |

---

### Key Equations

**Resolution Equation**
```
Ψ = R_B[Φ]
```

**Reflection as Two Resolutions**
```
Object     = R_B₁[Φ]
Reflection = R_B₂[Φ]
```

**Dynamic Resolution**
```
Ψ(t) = R_B(t)[Φ]
```

**Topological Preservation**
```
Topology(R_B[Φ]) ≅ Topology(Φ)    when |∇B| < ε_critical
```

**Boundary Decomposition**
```
B(t) = B₀ + δB(t)
```

**Stability Condition**
```
|δB(t)| < ε_critical → identity preserved
```

---

### Glyphs

| Glyph | Formula |
|-------|---------|
| Φ ⟂ Φ′ yet ∇Φ conserved | Different resolutions share invariant structure |

---

**「記号は道具。意味は構造から。」**
*Symbols are tools. Meaning comes from structure.*

---

[← Back to README](../README.md)

