## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

CSS Styling
- For conditional css styling use "clsx" module this allow you to add className based on conditions.

Routing
- For Routing add page.tsx inside you folder as next js uses file system routing.
- E.g /dashboard => create a folder Dashboard and then create a file page.tsx & /dashboard/customers Same for customer but it is nested routing so create a folder inside dashboard after that same as previous one.

Navigation
- For sharing the navigation across all the pages layout files should be created. 
- create a layout file wherever we create a page.tsx as layout receives a page.tsx as a children to render.
- **When navigate to any page and only page components update while the layout won't re-render this is called partial rendering.

Navigation betwn pages
- Code Splitting: This makes the page become isolated and if any of a page throws an error still the application won't stop and work well.
- Whenever <Link> Component appears in the browserm nextjs start prefetches the code in background before user click, and when it clicked the page load instantly without any delay. 




