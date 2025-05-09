sopify hydrogen setup

Step 1: Create a new Hydrogen storefront


npm create @shopify/hydrogen@latest

or

  npm create @shopify/hydrogen@latest -- --quickstart


Step 2: Run the dev server

                                                                             │
│  Storefront setup complete!                                                  │
│                                                                              │
│    Shopify:   Mock.shop                                                      │
│    Language:  JavaScript                                                     │
│    Routes:                                                                   │
│      • Home (/ & /:catchAll)                                                 │
│      • Page (/pages/:handle)                                                 │
│      • Cart (/cart/* & /discount/*)                                          │
│      • Products (/products/:handle)                                          │
│      • Collections (/collections/*)                                          │
│      • Policies (/policies & /policies/:handle)                              │
│      • Blogs (/blogs/*)                                                      │
│      • Account (/account/*)                                                  │
│      • Search (/search)                                                      │
│      • Robots (/robots.txt)                                                  │
│      • Sitemap (/sitemap.xml & /sitemap/:type/:page.xml)                     │
│                                                                              │
│  Next steps                                                                  │
│                                                                              │
│    • Run `cd hydrogen-quickstart && npm run dev` 






Step 3: Link your Hydrogen project to Shopify


npx shopify hydrogen link


website --- https://shopify.dev/docs/api/shopify-cli#installation

Step 4: npm install -g @shopify/cli@latest



  ERROR  SelectPrompt requires at least one choice


solve

shopify logout
shopify login



npx shopify hydrogen env pull




npx shopify hydrogen deploy



