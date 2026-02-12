## You will need
- /cars project
- /b2-pages (manuscript)
- and to go through the manuscript to assign new routes to each example according to the /cars project

| chapter | old | new |
|---------|-----|-----|
| 4 Setting-up Routing | `(home).jsx` | `(home).jsx` |
| 4 Setting-up Routing | `routes/[...notfound].tsx` | `routes/[...notfound].tsx` |
| 5 Static Routes | `/routes/contacts.tsx` | `about.tsx` |
| 5 Static Routes | `products/index.tsx` | `products/(products).tsx` |
| 5 Static Routes | `/products/categories` | folder |
| 5 Static Routes | `/categories/keyboards.tsx` | |
| 5 Static Routes | `/categories/mice.tsx` | |
| 7 Dynamic Routes | `routes/users` | |
| 7 Dynamic Routes | `routes/users/[id].tsx` | |
| 7 Dynamic Routes | `routes/contacts.tsx` | |
| 7 Dynamic Routes | `routes/contacts` | |
| 7 Dynamic Routes | `routes/contacts/[[id]].tsx` | |
| 7 Dynamic Routes | `routes/division`. | |
| 7 Dynamic Routes | `routes/division/[divisionId]`. | |
| 7 Dynamic Routes | `routes/division/[divisionID]/[departmentId].tsx`: | |
| 7 Dynamic Routes | `routes/teams`. | |
| 7 Dynamic Routes | `[[team]]`. | |
| 7 Dynamic Routes | `[[player]].tsx`: | |
| 7 Dynamic Routes | `products/[...notfound].tsx` | |
| 7 Dynamic Routes | `routes/(company)` | |
| 7 Dynamic Routes | `(company)/products.tsx` | |
| 7 Dynamic Routes | `/products/categories.tsx` | |
| 7 Dynamic Routes | `(company)/products(list).tsx` | |
| 8 Redirecting | `products/[...notfound].tsx` | |
| 9 Route Groups | `routes/(company)` | |
| 10 Layouts | `(company)/products.tsx` | |
| 10 Layouts | `/products/categories.tsx` | |
| 10 Layouts | `(company)/products(list).tsx` | |