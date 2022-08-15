![line](https://github.com/fwd/status/raw/master/dist/banner.png)

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

<h1 align="center" style="font-size: 30px">Easy Status Page</h1>
<h3 align="center" style="font-size: 30px">Hosted on Github</h3>

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

## ❯ 1. Clone

```bash
git clone git@github.com:fwd/status.git && cd status
```

## ❯ 2. Configure

Open ```config.json``` in any editor, and serve ```/index.html``` with a server. 

- **NPM**: ```npm start```
- **PHP**: ```php -S localhost:8080```

**Editable:**
- [config.json](/config.json) - Configure Servers.
- [favicon.png](/favicon.png) - Customize Favicon.

**Optional:**
- [index.html](/index.html) - Most things are configured via JSON file.
- [/dist](/dist) - Status CSS & JS Files.

## ❯ 3. Deploy

Remove the .git folder, and add your own.

```bash
rm -rf .git
git init
git add . && git commit -m "Look Ma! I'm on Github."
git branch -M "master"
git remote add origin git@github.com:NAME/REPO.git
git push -u origin "master"
```

## ❯ 4. Free Website Hosting

- Github repo must be public
- Go to [Settings Page](/../../settings/pages)
- Source → "Master" → "/Root"
- Save

Your public URL: https://NAME.github.io/REPO

#### Optional: Custom Domain:

- Go to [Settings Page](/../../settings/pages)
- "Custom domain" → "Add Domain"
- Save

##### Domain DNS Settings

- Create **A** record that points to: **185.199.108.153**
- If using Cloudflare, make sure to disable proxy.

Official Docs: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## ❯ ✅ Done 

You now have free, reliable hosting for your docs. Nice. 

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

#### Update Template

```
npm run update
```

## ❯ Contributing

Give a ⭐️ if this project helped you!

Contributions, issues and feature requests are welcome at [issues page](https://github.com/fwd/status/issues).

## ❯ License

MIT License

Copyright © [@nano2dev](https://twitter.com/nano2dev).

## ❯ Stargazers

[![Stargazers over time](https://starchart.cc/fwd/status.svg)](https://github.com/fwd/status)