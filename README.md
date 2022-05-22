# Deploy OG Image Generator to Layer0

A serverless service that generates dynamic Open Graph images that you can use for generating awesome previews.

## Demo

https://layer0-docs-og-image-default.layer0.link/api?title=Layer0

## Try It Now

[![Deploy with Layer0](https://docs.layer0.co/button.svg)](https://app.layer0.co/deploy?repo=https://github.com/layer0-docs/og-image)

## Getting Started

### Clone This Repo

Use `git clone https://github.com/layer0-docs/og-image.git` to get the files within this repository onto your local machine.

### Install dependencies

On the command line, in the project root directory, run the following command:

```bash
npm install
```

### Run the Next.js app locally on Layer0

Run the Next.js app with the command:

```bash
npm run layer0:dev
```

Load the site: http://127.0.0.1:3000

### Testing production build locally with Layer0

You can do a production build of your app and test it locally using:

```bash
layer0 build && layer0 run --production
```

Setting --production runs your app exactly as it will be uploaded to the Layer0 cloud using serverless-offline.

## Deploying to Layer0

Deploying requires an account on Layer0. [Sign up here for free](https://app.layer0.co/signup). Once you have an account, you can deploy to Layer0 by running the following in the root folder of your project:

```bash
layer0 deploy
```

See [deploying](https://docs.layer0.co/guides/deploying) for more information.

## Author

- Rishi Raj Jain ([@rishi*raj_jain*](https://twitter.com/rishi_raj_jain_)) - [Layer0](https://layer0.co)
