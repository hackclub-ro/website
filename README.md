<p align="center"><img width="200px" height="200px" alt="Hackathons icon" src="https://hackclub.com/icon/icon-masked.png"></a>
<h1 align="center"><a href="https://hackathons.hackclub.com">Hack Club Hackathons</a></h1>
<p align="center"><i>A curated list of hackathons organized by high schoolers for high schoolers.</i></p>

### Introduction

Hackathons are awesome—but it’s hard to find a high quality directory of events for high schoolers. That’s where this project comes in.

**Goal:** create the best curated directory of hackathons for high school students. Because quite frankly hackathons shouldn't only be for university students.

### A word of warning…

To ensure that the directory remains as high quality as possible, we have strict guidelines for listing hackathons.

For the time being, primarily for ease of development, requests for listing new events happens through [this form](https://dash.hackathons.hackclub.com/hackathons/submissions/new).

Please do not open an issue or submit a pull request to add your event—the form is the easiest and fastest way for us to review submissions.

### Development environment setup

The stack: [Next.js](https://nextjs.org) & [Theme UI](https://theme-ui.com) with [Hack Club Theme](https://theme.hackclub.com).

Stuff you need installed ahead of time:

- Git
- Yarn
- An operating system (we hope)

Clone it!

    $ git clone https://github.com/hackclub/hackathons.git

Go into the directory!

    $ cd hackathons

Install dependencies!

    $ yarn

Run it!

    $ yarn dev

### Build and deploy

Deployment is managed using [Vercel](https://vercel.com). Install the Vercel CLI, and to force a production deploy, run:

    $ vercel --prod

### Hackathon Data

This front-end site is powered by the
[Hackathons Backend](https://github.com/hackclub/hackathons-backend).

The backend contains all the hackathon data and exposes it via a REST API
which is consumed by this app.

### License

This project is licensed under the MIT license. Please see [`LICENSE.md`](LICENSE.md) for the full text.
