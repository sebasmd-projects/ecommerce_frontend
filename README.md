# Ecommerce Frontend

## Prerequisitos

1. node >= 20.10

## Requerimientos

```cmd
cd proyect_folder
npm i
```

## Instalación

### Descargar el repositorio desde github

```github
https://github.com/sebasmd-projects/
```

```cmd
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

## Descripción del proyecto

```plaintext
|   .eslintrc.json
|   .gitignore
|   front.txt
|   i18nConfig.js
|   middleware.js
|   next-env.d.ts
|   next.config.mjs
|   package-lock.json
|   package.json
|   postcss.config.js
|   README.md
|   tailwind.config.ts
|   tree.txt
|   tsconfig.json
|
+---public
|       favicon.ico
|       next.svg
|       vercel.svg
|
\---src
    +---app
    |   +---css
    |   |       globals.css
    |   |
    |   +---providers
    |   |       reactQuery.js
    |   |
    |   \---[locale]
    |       |   layout.tsx
    |       |
    |       \---(pages)
    |           +---(home)
    |           |   |   layout.tsx
    |           |   |   page.tsx
    |           |   |
    |           |   \---cart
    |           |           layout.tsx
    |           |           page.tsx
    |           |
    |           +---account
    |           |   |   layout.tsx
    |           |   |
    |           |   +---(user_account)
    |           |   |       page.tsx
    |           |   |
    |           |   +---login
    |           |   |       page.tsx
    |           |   |
    |           |   +---notifications
    |           |   |       page.tsx
    |           |   |
    |           |   \---register
    |           |           page.tsx
    |           |
    |           +---admin
    |           |   |   layout.tsx
    |           |   |   page.tsx
    |           |   |
    |           |   +---(ecommerce)
    |           |   |   |   layout.tsx
    |           |   |   |
    |           |   |   +---billings
    |           |   |   |       page.tsx
    |           |   |   |
    |           |   |   +---checkouts
    |           |   |   |       page.tsx
    |           |   |   |
    |           |   |   +---discounts
    |           |   |   |       page.tsx
    |           |   |   |
    |           |   |   +---inventories
    |           |   |   |       page.tsx
    |           |   |   |
    |           |   |   +---orders
    |           |   |   |       page.tsx
    |           |   |   |
    |           |   |   +---payments
    |           |   |   |       page.tsx
    |           |   |   |
    |           |   |   +---products
    |           |   |   |   |   layout.tsx
    |           |   |   |   |   page.tsx
    |           |   |   |   |
    |           |   |   |   +---comments
    |           |   |   |   |       page.tsx
    |           |   |   |   |
    |           |   |   |   +---ratings
    |           |   |   |   |       page.tsx
    |           |   |   |   |
    |           |   |   |   \---reviews
    |           |   |   |           page.tsx
    |           |   |   |
    |           |   |   \---shippings
    |           |   |           page.tsx
    |           |   |
    |           |   +---analytics
    |           |   |       page.tsx
    |           |   |
    |           |   +---location
    |           |   |       page.tsx
    |           |   |
    |           |   \---reports
    |           |           page.tsx
    |           |
    |           \---support
    |                   layout.tsx
    |                   page.tsx
    |
    +---requests
    |   +---common
    |   |       analytics.ts
    |   |       locations.ts
    |   |       notifications.ts
    |   |       reports.ts
    |   |       supports.ts
    |   |
    |   \---shopping
    |           billings.ts
    |           carts.ts
    |           checkouts.ts
    |           comments.ts
    |           discounts.ts
    |           inventories.ts
    |           orders.ts
    |           payments.ts
    |           products.ts
    |           ratings.ts
    |           reviews.ts
    |           shippings.ts
    |
    \---utils
            constants.js
```

## Versiones

- 0.0.X: Se incrementa cuando se realizan correcciones de errores o pequeñas mejoras que no afectan la compatibilidad con versiones anteriores.
- 0.X.0: Se incrementa cuando se añade una nueva carácteristica o un cambio significativo.
- X.0.0: Se incrementa cuando hay una versión estable del proyecto.

### v0.0.1

- .gitignore
- Estructura inicial del proyecto
- Internacionalización
