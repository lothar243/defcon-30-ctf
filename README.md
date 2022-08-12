# Capture The Flag // Voting Village // Def Con 30

Welcome to the github.com/ory CTF at DEF CON 30! Explore a vulnerable, open-source digital election system and capture the flag to win a surprise!

Head over to the [remote challenge](https://defcon.getory.io/) to get started:

```
https://defcon.getory.io/
```

## Targets

This challenge runs five services. They mock a basic election system used by **authenticated** users (election workers) to submit their voting districts results. This is not a service for voters. However, everyone can sign up and see the already submitted results.

The services are all open source:

- [Ory Oathkeeper](https://github.com/ory/oathkeeper): reverse proxy for all other services
- [Ory Kratos](https://github.com/ory/kratos): authentication and session management
- [Ory Keto](https://github.com/ory/keto): authorization and access control
- Backend (this repo): the actual election system backend
- Postgres: the database

The target of this CTF is the **backend** service. Vulnerabilities found in the open source **Ory Oathkeeper**, **Ory Kratos**, and **Ory Keto** projects can be reported through our [bug bounty program](https://hackerone.com/ory_corp) and give you bounties between 100$ (low) and 3,000$ (critical). On top, we will add another 100$ for any submission done during DEF CON 30 after you talked to us personally at the Voting Machine village.

## Out of Scope

We kindly ask you **not to do** denial of service or brute-force attacks against our remote services. Doing so will ruin the fun for everyone.

For more details head over to the [extended README](README.extended.md).
