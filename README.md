# Reproduction Steps

1. pnpm i
2. pnpm dev
3. navigate to http://localhost:3000/notapage
4. observe the error page
5. click on back to home

It should then not navigate to the home page. and instead show a console error stating

```
Uncaught (in promise) H3Error: You are using a defineOgImage() function in a client-only context. You must call this function within your root component setup, see https://github.com/nuxt-modules/og-image/pull/293.
```
