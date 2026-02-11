
- # 4
    - ## 4.1 Install #Solid-Router
        - `(home).jsx`
        - `routes/[...notfound].tsx`

    - ## 4.2 The Router Component

    - ## 4.3 Adding a Root Layout

    - ## 4.4 The FileRoutes Component

    - ## 4.5 Adding the Root Route

    - ## 4.6 Renaming Index

    - ## 4.7 Adding a Catch-all Route

- # 5
    - ## 5.1 A Filename as a Route Segment
        - `/routes/contacts.tsx`

    - ## 5.2 A Directory as a Route Segment
        - `products/index.tsx`

    - ## 5.3 Multiple Routes in a Single Directory
        - `/products/categories`
        - `/categories/mice.tsx`
        - `/categories/keyboards.tsx`
- # 6 - Navigation
- # 7 - Dynamic Routes
    - ## 7.1 Required Parameters
        - `routes/users`
        - `routes/users/[id].tsx`
    - ## 7.2 Accessing Parameters
    - ## 7.3 Optional Parameters
        - `routes/contacts.tsx`
        - `routes/contacts`
        - `routes/contacts/[[id]].tsx`
    - ## 7.4 Multiple Required Parameters
        - `routes/division`.
        - `routes/division/[divisionId]`.
        -  `routes/division/[divisionID]/[departmentId].tsx`:
    - ## 7.5 Multiple Optional Parameters
        - `routes/teams`.
        - `[[team]]`.
        - `[[player]].tsx`
    - ## 7.6 Mixing Required and Optional Parameters
    - ## 7.7 Catch-all Routes are Dynamic
- # 8 Redirecting
    - `products/[...notfound].tsx`
- # 9 Route Groups
    - `routes/(company)`
- # 10 Layotus
    - `(company)/products.tsx`
    - `/products/categories.tsx`
    - `(company)/products(list).tsx`