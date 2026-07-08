# python-app

Documentation for the **python-app** service.

## API endpoints

This application exposes two endpoints:

| Endpoint | Description |
|----------|-------------|
| `GET /api/v1/details` | Returns the current time, hostname, and a status message |
| `GET /api/v1/healthz` | Health check; returns `{"status": "up"}` when the app is running |

### Example URLs

- `https://python-app.text.com/api/v1/details`
- `https://python-app.text.com/api/v1/healthz`

## How to access the app

Open the health endpoint in your browser or with `curl`:

```bash
curl https://python-app.text.com/api/v1/healthz
```

For full details (time, hostname, message):

```bash
curl https://python-app.text.com/api/v1/details
```
