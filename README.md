# Build a Harness — The Blueprint

Static single page. Condenses two articles on building a coding-agent harness
into a build plan that a coding agent can work through directly.

English version of [harness-bauen](https://harness-bauen.vercel.app/).

Sources:
- https://ampcode.com/notes/how-to-build-an-agent (Thorsten Ball)
- https://www.mihaileric.com/The-Emperor-Has-No-Clothes/ (Mihail Eric)

## View locally

    npx serve .

## Deploy to Vercel

    npx vercel --prod

No build configuration needed: `index.html` sits in the root and Vercel serves it as a static page.
