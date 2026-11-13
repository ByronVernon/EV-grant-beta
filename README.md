# EV grant beta

A prototype of an EV grant application journey, built with the [GOV.UK Prototype Kit](https://prototype-kit.service.gov.uk/). It uses fake data only.

## Setup

You need the current LTS version of [Node.js](https://nodejs.org/).

```
nvm use
npm install
npm run dev
```

Open http://localhost:3000.

## Where things are

| Path | What it is |
| --- | --- |
| `app/views/apply/` | The journey pages |
| `app/views/_templates/` | Starter pages to copy: question, check answers, confirmation |
| `docs/` | [Components](docs/COMPONENTS.md), [contributing](docs/CONTRIBUTING.md), [page map](docs/PAGE-MAP.md) |

## Making a change

1. Branch from `main`: `git switch -c feature/short-description`
2. Make your change and check it with `npm run dev`.
3. Push and open a pull request. Fill in the template.
4. Get one approval, then squash merge.

`main` is protected, so you can't push to it directly. See [CONTRIBUTING](docs/CONTRIBUTING.md).
