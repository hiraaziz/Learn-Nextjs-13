## Learn-Nextjs

#Building blocks of website?

- How user will interact UI.
- Routing
- Data Fetching
- Rendering (Static and Dynamic Content)
- Integration (Third party API)
- Infrastructure (How application deploy, Where Host and run)
- Performance (How optimized application)
- Scalability
- Developer experience
  We will Reactjs for UI and for other features Next js will be used eg routing, data fetching etc

## Server Side rendering and its limitation?

- In server all the data fetches for the page.
- HTML page rendered on server.
- TTFB (Time ti Firest Byte) - HTML, CSS(rendered page), Javascript send to the client.
- FCP (First Contentful Page) - A rendered page will be displayed without interactivity.
- TTI (Time to Interactive) - React hydrates the user interface to make it interactive.
  Limitations: Server can render HTML only when all the data gets fetched. Client can hydrate UI only when all the code of components downloaded.

## Streaming and Suspense?

Streaming allows you to break down the page's HTML into smaller chunks and progressively send those chunks from the server to the client. By using Suspense, you get the benefits of:

- Streaming Server Rendering - Progressively rendering HTML from the server to the client.
- Selective Hydration - React prioritizes what components to make interactive first based on user interaction.

## What is code Splitting and pre fetching?

It splits the code automatically and loads the page which is requested not all pages will load. But in pre fetching ,in production build of Nextjs, whenever Link component appears in browser viewport It will prerender pages that are linked.

## How does Image Component does in Nextjs?

Next js optimizes image on server whenever they are requested and image loads as they are scrolled into viewpoint. It is also called lazy loading.
