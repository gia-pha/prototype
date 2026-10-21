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

## History

This repo was extracted with full git history from the
[`gia-pha/full`](https://github.com/gia-pha/full) monorepo (folder `proto`,
later renamed `prototype`), as part of the split into one repo per service
described in `docs/microservices-deployment-plan.md` there. `gia-pha/full` now
references this repo as a git submodule for local development.

## License

MIT — see [LICENSE](LICENSE).
