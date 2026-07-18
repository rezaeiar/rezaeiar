<!-- ========================================================= -->
<!--                  /profile/README.md                       -->
<!-- ========================================================= -->

<div align="center">

# /workspace

```txt
root
├── engineer/
│   ├── focus      → UI Engineering
│   ├── stack      → React · Next.js · TypeScript
│   ├── principle  → Simplicity scales
│   ├── specialty  → Design Systems & Frontend Architecture
│   └── status     → shipping
└── README.md
```

</div>

---

<table>
<tr>

<td width="64%">

## build.config.ts

```ts
export default {
  role: "Frontend Engineer",

  currentlyBuilding: [
    "Scalable React Applications",
    "Design Systems",
    "Feature-based Architectures"
  ],

  engineering: {
    ui: true,
    performance: true,
    accessibility: true,
    maintainability: true,
    developerExperience: true
  },

  philosophy: [
    "Readable > Clever",
    "Composition > Configuration",
    "Consistency > Complexity"
  ]
}
```

</td>

<td width="36%">

```yaml
runtime:
  framework:
    - React
    - Next.js

language:
  - TypeScript

styling:
  - Tailwind CSS

data:
  - TanStack Query

tables:
  - TanStack Table

architecture:
  - Feature Based
  - Clean Code

design:
  - UI Engineering
```

</td>

</tr>
</table>

---

## architecture.graph

```text
                 Product
                    │
          ┌─────────┴─────────┐
          │                   │
      User Experience     Business Logic
          │                   │
          └─────────┬─────────┘
                    │
            Design System
                    │
       Components • Tokens • Patterns
                    │
          React + TypeScript
                    │
           Fast • Accessible • Maintainable
```

---

<details open>

<summary><strong>workspace/tree</strong></summary>

```text
.
├── app/
├── features/
│   ├── authentication/
│   ├── dashboard/
│   ├── forms/
│   ├── users/
│   └── ...
├── shared/
│   ├── components/
│   ├── hooks/
│   ├── lib/
│   ├── providers/
│   └── utils/
├── services/
├── types/
├── constants/
└── assets/
```

</details>

---

## engineering.surface

| Interface | Approach |
|-----------|----------|
| Component Design | Composition-first |
| State Management | Keep it local until it hurts |
| Styling | Utility-first with reusable primitives |
| Performance | Render less · Load less · Ship less |
| APIs | Typed from request to UI |
| Accessibility | Included from the first commit |
| Collaboration | Predictable code over clever code |

---

## package.json

```json
{
  "name": "frontend-engineer",
  "version": "continuous",
  "private": true,

  "dependencies": {
    "react": "stable",
    "next": "stable",
    "typescript": "strict",
    "tailwindcss": "latest",
    "@tanstack/react-query": "latest",
    "@tanstack/react-table": "latest"
  },

  "scripts": {
    "design": "system",
    "build": "quality",
    "refactor": "often",
    "deploy": "confidently"
  }
}
```

---

## quality.checklist

| |
|:--|
| ✓ Consistent UI Architecture |
| ✓ Reusable Components |
| ✓ Strong Type Safety |
| ✓ Responsive by Default |
| ✓ Clean Folder Structure |
| ✓ Maintainable Codebase |
| ✓ Performance Conscious |
| ✓ Pixel-level Attention |

---

## commit.log

```text
feat(ui): build interfaces that scale
refactor: reduce complexity before adding features
perf: remove unnecessary renders
style: keep every interaction intentional
docs: make code explain itself
```

---

<div align="center">

```text
Design with intention.
Engineer for scale.
Ship with confidence.
```

</div>
