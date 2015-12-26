# gitbook-plugin-woopra

Basic Woopra analytics for your [GitBook](https://www.gitbook.com)

Install with npm:

```
npm install gitbook-plugin-woopra
```

Enable in `book.json`:

```
{
    "plugins": ["woopra"]
}
```
Configure your book domain and idle timeout in `book.json`:

```
{
    "plugins": ["woopra"],
    "pluginsConfig": {
        "woopra": {
            "domain": "example.com",
            "idle_timeout": 1800000
        }
    }
}
```

More coming soon, PRs welcome, YMMV, HAND.

