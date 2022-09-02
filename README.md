# My links (linktree clone)

[Demo](https://raulmar.me)

## Features
- One-file configuration
- Svelte
- Tailwind
- Github action to deploy


<img style="width: 50%;" src="https://raulmarfiles.blob.core.windows.net/my-links/my-links-ss.png">

## Getting started

Run the following command on your local environment:

```
git clone --depth=1 https://github.com/raulmar0/my-links.git my-project-name
cd my-project-name
npm install
```

First of all, use this line in `vite.config.js` if using Github pages with a custom domain
```
base: '/my-links/'
```


Then, you can run locally in development mode with live reload:

```
npm run dev
```

## Customization

You can easily configure My Links. Please change the following file:

- Site title `./index.html`
- Favicon `./public` and `./index.html`
- Main config file `./src/utils/AppConfig.js`
  - Social media links and image


## Deploy to production

In order to deploy your static site run:

```
$ npm run build
```

The generated HTML and CSS files are minified (built-in feature from Next js). It will also removed unused CSS from [Tailwind CSS](https://tailwindcss.com).

Now, your blog is ready to be deployed. All generated files are located at `dist` folder, which you can deploy with any hosting service.

Verified hosting services with a free tier
- Github pages (check `./.github/workflows/pages.yml` file)
- Azure app services
- Digital Ocean Web Apps