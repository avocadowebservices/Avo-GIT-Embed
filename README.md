# AvoGitEmbed

Embed any public GitHub repository directly into your WordPress page or post — complete with repo metadata, latest release info, and rendered `README.md`.

Created by [Joseph Brzezowski](https://avocadoweb.net) at AvocadoWeb Services LLC.

---

## 🔧 Features

- 📦 Embed repository title, description, stars, forks, and last updated date
- 📝 Display and render GitHub `README.md` using Markdown
- 🏷️ Show GitHub badges in a clean, single-row layout
- 🚀 Optionally show the latest release tag and publish date
- 🎨 Includes external CSS for seamless theme integration
- ⚡ Lightweight, cached output with WordPress transients

---

## 🪄 Usage

Use the shortcode in any page or post:

```
[avogitembed user="github_username" repo="repository_name"]
```

### Optional Attributes:

| Attribute      | Default | Description |
|----------------|---------|-------------|
| `user`         | *none*  | GitHub username (required) |
| `repo`         | *none*  | GitHub repository name (required) |
| `show_release` | `no`    | Show latest GitHub release (`yes` or `no`) |

**Example:**

```
[avogitembed user="avocadowebservices" repo="send-it-form" show_release="yes"]
```

---

## 🎨 Styling

The plugin includes a dedicated stylesheet (`assets/avogitembed.css`) that ensures clean layout and responsiveness. You can override or extend it from your theme if needed.

---

## 🚀 Roadmap

- [ ] Gutenberg block version
- [ ] Toggle to collapse/expand README
- [ ] Support for showing contributors, issues, or pull requests
- [ ] GitHub token support for private repos or higher quota

---

## 🛡 License

Licensed under [GPLv3](https://www.gnu.org/licenses/gpl-3.0.html)

---

Made with ❤️ by [AvocadoWeb Services LLC](https://avocadoweb.net)
