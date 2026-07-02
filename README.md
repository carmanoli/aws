# AWS Learning Labs

Hands-on AWS labs documented as a simple static website.

## View locally

Open `docs/index.html` in a browser. No installation or build process is required.

## Add screenshots

Each lab has its own `images` directory:

```text
docs/labs/lab-09-alb/images/
docs/labs/lab-10-auto-scaling/images/
```

Use descriptive, ordered file names such as `01-create-target-group.png`, then add them to the lab page:

```html
<img src="images/01-create-target-group.png"
     alt="AWS console showing the target group configuration">
```

Always remove account IDs, public IP addresses and other sensitive information from screenshots.

## Publish with GitHub Pages

In the GitHub repository, open **Settings → Pages** and configure:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/docs**

GitHub Pages will publish the HTML files directly.
