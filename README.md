
# Next.js + Shopify 

The ultimate starter for headless Shopify stores. 



## Goals and Features

- Ultra high performance
- SEO optimized
- Themable
- Personalizable (internationalization, a/b testing, etc)
- Builder.io Visual CMS integrated


## Getting Started

**Pre-requisites**

This guide will assume that you have the following software installed:

- nodejs (>=12.0.0)
- npm


**Introduction**

This starter kit is everything you need to get your own self hosted
Next.js project powered by Builder.io for content and Shopify as an
e-commerce back office.

After following this guide you will have

- A Next.js app, ready to deploy to a hosting provider of your choice
- Pulling live collection and product information from Shopify
- Powered by the Builder.io visual CMS



Then in the `API Credentials` tab, click `install`:

And copy the generated access token.



Fill in the required keys and press "Connect your Shopify Custom App"!

### 6. Configure the project to talk to Shopify

Open up [.env.development](./.env.development) and [.env.production](./.env.production) again,
but this time set the other two Shopify keys.

```diff
BUILDER_PUBLIC_KEY=012345abcdef0123456789abcdef0123
+ SHOPIFY_STOREFRONT_API_TOKEN=c11b4053408085753bd76a45806f80dd
- SHOPIFY_STOREFRONT_API_TOKEN=
+ SHOPIFY_STORE_DOMAIN=dylanbuilder.myshopify.com
- SHOPIFY_STORE_DOMAIN=
```

### 7. Up and Running!

The hard part is over, all you have to do is start up the project now.

```bash
npm install
npm run dev
```

This will start a server at `http://localhost:3000`.



