# Prototype

Static HTML/JavaScript prototype for the Gia Phả (family tree) application.
It is used to explore UI and product ideas ahead of the production frontend.

## Run

With Docker:

```bash
docker build -t giapha-prototype .
docker run -p 8082:80 giapha-prototype
```

Then open http://localhost:8082.

Or via the umbrella repo's `docker-compose.yml` (`prototype` service, port 8082).

## License

MIT — see [LICENSE](LICENSE).
