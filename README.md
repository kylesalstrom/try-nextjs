This is a starter template [Current Location In Next.js Tutorial](https://nextjs.org/learn/basics/api-routes).



Preview Mode
Static Generation is useful when your pages fetch data from a headless CMS. However, it’s not ideal when you’re writing a draft on your headless CMS and want to preview the draft immediately on your page. You’d want Next.js to render these pages at request time instead of build time and fetch the draft content instead of the published content. You’d want Next.js to bypass Static Generation only for this specific case.

Next.js has a feature called Preview Mode to solve the problem above, and it utilizes [API Routes](https://nextjs.org/learn/basics/api-routes/api-routes-details). To learn more about it take a look at our [Preview Mode](https://nextjs.org/docs/advanced-features/preview-mode) documentation.