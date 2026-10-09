### hey, I'm Abishek

Backend engineer, about 2.5 years in fintech. Mostly .NET and SQL at work, on mortgage investor reporting, where a wrong number turns into someone else's month-end problem.

Outside work I build things people actually use.

**[laptop-service-management](https://github.com/pxndavinci/laptop-service-management)**

My uncle runs a laptop service shop, so I built the app it runs on. React + TypeScript on the front, Express + Postgres behind it. I wrote the OpenAPI contract before any of the code.

It's in production. The part I like most is the boring part: a release watcher that only deploys between 11pm and 7am. It takes a `pg_dump` first and rolls itself back if the health check fails.

**[joatverse](https://github.com/joatverse)**

Where the bigger build lives. A personal site with a Go backend that will run on k3s across my own machines. The end goal is an AI agent on my own GPU serving stack.

Honestly it's mostly scaffolding right now. Signed commits and SOPS-encrypted secrets went in before there was much code to protect, which is probably backwards :)

Learning Go and Kubernetes at the moment, vLLM next.

[LinkedIn](https://www.linkedin.com/in/abisheknallathambi)
