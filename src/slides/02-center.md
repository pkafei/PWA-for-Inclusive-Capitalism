Not Everyone has Access to Fast and Reliable Internet

![Next Gov Internet Connectivity](./internet-connectivity.png)

---

Speed === Money


---


Slow Connections Economically Leave Communities Behind

![](./market.jpg)

---

Slow websites act as a barrier to economic prosperity

---

PWA solves for speed and wonky internet connection

---

![](./gatsby-pwa.png)


---

Gatsby Plugins helps create a PWA for <i>you</i>

---
```
$ npm install --save gatsby-plugin-manifest

```

&

```
$ npm install --save gatsby-plugin-offline

```

---
_gatsby-config.js_
```javascript
module.exports = {
  plugins: [
    {
      resolve: `gatsby-plugin-manifest`,
      options: {
        name: siteConfig.name,
        short_name: siteConfig.shortName,
        start_url: siteConfig.prefix,
        background_color: `#ffffff`,
        theme_color: `#663399`,
        display: `minimal-ui`,
        icon: `content/assets/gatsby-icon.png`,
        crossOrigin: `use-credentials`,
      },
    },
    `gatsby-plugin-offline`,
  ],
}
```
---

### Results

---

<div align="center">
  <a href="https://youtu.be/YVQNNvQbGSQ "><img src="https://res.cloudinary.com/blockchain-side-hustle/image/upload/c_scale,h_508/v1575619418/Screen_Shot_2019-12-06_at_8.57.34_AM_ghny0q.png" alt="Oaxaca Shop"></a>
</div>

