# Onelink

Onelink is an experimental link-in-bio tool, where the data lives in the URL. 

![Screenshot2023-01-30 at 00 40 04@2x](https://user-images.githubusercontent.com/15716057/215350057-5fbf81f5-5f33-4cbe-98ba-0ced8b3c09c8.jpg)

> **Note**

https://onelink-nu.vercel.app/1?data=eyJuIjoiS2FyaW0gRWxoYXdhcnkgIiwiZCI6IkkgYW0gRWd5cHRpYW4gbGF3eWVyIGFuZCBvcGVyYXRpb24gc3VjY2VzcyBNYW5hZ2VyIEZvciBkaWZmZXJlbnQgc29sYXIgJiBSb29maW5nIENvbXBhbmllcyBpbiBVU0EiLCJpIjoiaHR0cHM6Ly93d3cuZmFjZWJvb2suY29tL3Bob3RvLz9mYmlkPTEwMTYwODIxNzc5MDE1OTM1JnNldD1hLjQ2MTAwOTc4NTkzNCIsImYiOiJodHRwczovL3d3dy5mYWNlYm9vay5jb20va2FyaW0uZWxoYXdhcnkuOSIsInQiOiIiLCJpZyI6Imh0dHBzOi8vd3d3Lmluc3RhZ3JhbS5jb20vZWxoYXdhcnlrYXJpbS8/aGw9YXIiLCJnaCI6Imh0dHBzOi8vZ2l0aHViLmNvbS9rYXJpbWVsaGF3YXJ5ODkvb25lbGluayIsInRnIjoiaHR0cHM6Ly93ZWIudGVsZWdyYW0ub3JnL2EvIiwibCI6Imh0dHBzOi8vd3d3LmxpbmtlZGluLmNvbS9pbi9rYXJpbS1lbGhhd2FyeS0zOTMzNTgxMDA/bGlwaT11cm4lM0FsaSUzQXBhZ2UlM0FkX2ZsYWdzaGlwM19wcm9maWxlX3ZpZXdfYmFzZV9jb250YWN0X2RldGFpbHMlM0JPTFNFZUhlbFMxdXFsbkhsdDZLajlRJTNEJTNEIiwiZSI6IkthcmltZWxoYXdhcnk4OUBnbWFpbC5jb20iLCJ3IjoiKzIwMTAwMDg2NzY5NyIsInkiOiJodHRwczovL3d3dy55b3V0dWJlLmNvbS9jaGFubmVsL1VDdFpSczU3aUJrYzYtZTdwajcwa0xpZyIsImxzIjpbeyJpIjoiIiwibCI6IiIsInUiOiJodHRwczovL2thcmltZWxoYXdhcnk4OS53aXhzaXRlLmNvbS9lbGhhd2FyeS1icm90aGVycy0xIn0seyJpIjoiIiwibCI6IiIsInUiOiJodHRwczovL3dvcmRwcmVzcy5jb20vaG9tZS9lbGhhd2FyeWJyb3RoZXJzLndvcmRwcmVzcy5jb20ifV19
Here's a demo page
https://onelink-nu.vercel.app/1?

The data is converted to a base 64 string which we onelink uses as a query parameter. I have tried to reduce the json keys to be as small as possible

Roadmap.
1. Templates - make different templates, the `/1` after the host is basically a template here.
2. Refactor code - a lot of repeated boilerplate code is added here - refactor it properly.

## Setup locally

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Checkout the [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.
