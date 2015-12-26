# gitbook-plugin-woopra

Basic Woopra tracking for GitBooks

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