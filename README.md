# URL Shortener via GitHub Pages

A simple and customizable URL shortener that uses **GitHub Pages** and **query string redirection**. Users can fork the repository, deploy it via GitHub Actions, and instantly create their own redirect service like `<username>.github.io/links?id=your_key`.

---

## 🚀 Features

- **No Server Needed**: Fully static site using GitHub Pages and client-side redirection.
- **Instant Deployment**: Just fork and let GitHub Actions handle the deployment.
- **Custom Short Links**: Redirect based on `?id=` query parameters.
- **Editable JSON**: Add or change redirect targets via a simple `links.json` file.

---

## 🌐 Live Usage Example

Once deployed to GitHub Pages, users can visit:

```
https://<your-username>.github.io/links?id=url1
https://<your-username>.github.io/links?id=url2
```

This will redirect to the corresponding URLs defined in your `links.json` file.

---

## 🚀 Getting Started

### Step 1: Fork This Repository

Click the **Fork** button in the top right to create your own copy of this repo.

### Step 2: Enable GitHub Pages

GitHub Actions is already set up. Just wait for the deployment or enable Pages manually from the repo settings:

- Go to **Settings > Pages**
- Set source to `gh-pages` branch and `/root`

### Step 3: Add Your Redirect Links

Edit the `links.json` file with your custom links. The format should be:

```json
{
  "url1": "https://example.com/page1"
  "url2": "https://example.com/page2"
}
```

### Step 4: Access Your Links

Visit:  
```
https://<your-username>.github.io/links?id=url1
```

This will redirect to `https://example.com/page1`.

---

## 🛠 Technologies Used

- HTML
- JavaScript
- GitHub Pages
- GitHub Actions

---

## 🙌 Credits

* **Built with ❤️ by [MdMobid](https://github.com/MdMobid)**

---
