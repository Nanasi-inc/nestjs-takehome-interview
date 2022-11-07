# NestJs Take Home Interview

<br/>

![Nanasi Logo](https://res.cloudinary.com/www-nanasi-co/image/upload/v1639128056/dashboard/center_piece_qhiuq1.svg)

<br/>

## Objective

Your goal is to build a FAQ REST API that could be potentially used to power a Quora-like website where people can add, read, delete and update questions and answers.

##### Expected Functionality

- List all questions posted using LIFO (latest questions appearing first) approach.
- List all answers for a given question.
- Update question details
- Update answer details
- Delete a question, which should effectively delete all its answers.
- Delete an answer to a given question

##### Additional Expectations

- The application structure should follow [Domain-driven Design principles](https://en.wikipedia.org/wiki/Domain-driven_design).
- The exposed API should follow RESTful APIs design.
- API Payload validation.
- You should provide a link to the publicly available repository whenever you send the submission email. We will also evaluate the provided codebase as part of your submission.
- This assignment should be completed **no more than 72 hours after receiving it**.

##### Bonus Points

- Dockerize your API and deploy it to any cloud provider(AWS, GCP, Azure, Heroku, [RailwayApp](https://railway.app/))

#### Technologies We Expect You To Incorporate

- Use [Postgres](https://hub.docker.com/_/postgres) as the DB of choice. We recommend using [Prisma ORM](https://www.prisma.io/docs/concepts/overview/what-is-prisma) for easy integration.

## Setup Instructions

1. Fork this repo as a starting template. We have included all necessary packages required to complete this assessment.
2. Install the packages by running
   ```
   $ pnpm install
   ```
3. Start the development server
   ```
   $ pnpm run start:dev
   ```
4. Start hacking away!

## Submission

After you have pushed your code, you should submit the assignment by replying to the email you've received with:

- The link to your own repository's main branch on Github.
