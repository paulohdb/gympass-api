# GymPass Style API

This is a repository of a Gympass API, using NodeJs to build a RESTful API. 

Technologies used in this project are:
- Typescript (Programming Language)
- Fastify (Server Instance Framework)
- Zod (Validate Variables)
- BiomeJs (Formatter)
- Prisma (ORM)
- Docker
- Vitest (Unit Test)
- JWT (Authentication)

As the project grows, I'll update the readme file with more technologies and functionalities explained step-by-step.

## FRs (Functional Requirements)

- [ ] It can be possible to register
- [ ] It can be possible to authenticate
- [ ] It can be possible to obtain a profile from a logged user
- [ ] It can be possible to obtain the number of check-in from a logged user
- [ ] It can be possible for user to obtain his own history of check-in
- [ ] It can be possible for user to search nearby gyms
- [ ] It can be possible for user to search gyms by the name
- [ ] It can be possible for user to do check-in in a gym
- [ ] It can be possible validate the check-in from a user
- [ ] It can be possible to register a gym

## RB (Rule of Business)

- [ ] The user cannot register with doubled e-mail
- [ ] The user cannot double checkin in the same day
- [ ] The user cannot check in if it isn`t close to the gym
- [ ] The check in can only be validate in 20 minutes after created
- [ ] The check in can only be validate by admin
- [ ] The gym can only be register by admin

## NFRs (Non-Functional Requirements)

- [ ] The user's password needs to be crypto
- [ ] The data needs to persist in a PostgreSQL DB
- [ ] All the lists of data needs to be paged with 20 items per page
- [ ] The user must be identified by a JWT (JSON Web Token)