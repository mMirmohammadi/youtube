# YouTube Clone — Computer Networks Project

> A from-scratch YouTube-like video sharing platform with user authentication, video upload/streaming, comments, likes, proxy server, and DDoS simulation — built entirely with raw Python sockets.

## Features

- **User accounts** — registration, login, session management (all from scratch, no frameworks)
- **Video management** — upload, stream, browse, and delete videos
- **Social features** — comments, likes/dislikes on videos
- **Proxy server** — reverse proxy with account forwarding
- **Conversations & tickets** — user-to-admin messaging
- **DDoS simulation** — attack script for testing server resilience
- **Terms of service** page

## Tech Stack

- Python (raw sockets, no Flask/Django)
- Custom HTTP server implementation
- HTML/CSS templates with custom template rendering
- SQLite-style database layer

## Running

```bash
python main.py
```

Then visit `http://localhost:8080`.

*Computer Networks Course — Final Project, Summer 2022*
