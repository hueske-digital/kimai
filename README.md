```
https://timetracking.yourdomain.de {

    # import logging
    import cloudflare
    import tls
    import compression
    import header

    handle @cloudflare {
        reverse_proxy kimai-app-1:8001
    }
    respond 403
}
```
