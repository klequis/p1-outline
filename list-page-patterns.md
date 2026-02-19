# List Page Patterns

## 1. TanStack Router

**Scenario A: Dynamic Routes**
```
src/
└── routes/
    ├── __root.tsx
    ├── index.tsx
    └── products/
        ├── index.tsx
        └── $productId.tsx
```

**Scenario B: Static Blog**
```
src/
└── routes/
    ├── __root.tsx
    ├── index.tsx
    └── blog/
        ├── index.tsx
        ├── my-first-post.tsx
        ├── another-post.tsx
        └── third-post.tsx
```

---

## 2. Next.js App Router

**Scenario A: Dynamic Routes**
```
app/
├── layout.tsx
├── page.tsx
└── products/
    ├── page.tsx
    └── [id]/
        └── page.tsx
```

**Scenario B: Static Blog**
```
app/
├── layout.tsx
├── page.tsx
└── blog/auto
    ├── page.tsx
    ├── my-first-post/
    │   └── page.tsx
    ├── another-post/
    │   └── page.tsx
    └── third-post/
        └── page.tsx
```

---

## 3. Solid Router

**Scenario A: Dynamic Routes**
```
src/
└── routes/>
    ├── index.tsx
    └── products/
        ├── index.tsx
        └── [id].tsx
```

**Scenario B: Static Blog**
```
src/
└── routes/
    ├── index.tsx
    └── blog/
        ├── index.tsx
        ├── my-first-post.tsx
        ├── another-post.tsx
        └── third-post.tsx
```
