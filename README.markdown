# ![Arlin by Michi](design/brand/arlin_logo_color.png)

[![Join the chat at https://gitter.im/gunadarma-academy/asde-michi](https://badges.gitter.im/gunadarma-academy/asde-michi.svg)](https://gitter.im/gunadarma-academy/asde-michi?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

> Centralized Q&A for city traffic and trip discussion

Arlin (Arah lalu lintas) is a community-driven transportation helper for anyone in the city. The contents will be user generated as the visitors/users discuss something. We provide a platform where user can ask a specific transporation-related question with rating system for each answers. It's like a Stack Exchange equivalent for asking road direction. We expect to complete v1 of the MVP in 4-5 weeks.

The main users mostly are citizens who commute with public/private transporation daily. We need this app because majority of traffic and roads condition in some cities can sometime be an overwhelming experience. Google Maps can sure be a good companion yet in contrary, the chaotic transportation layout is destroying the premises, rendering Google Maps useless, if not efficient. While there are lots of experienced people ready to help at all times, there is virtually not a single medium to connect both parties.

The main project management tools we use are GitHub Issues + Milestones with [ZenHub](https://zenhub.io). Please install ZenHub extension first to see our Kanban board and Burndown chart.

**Original ideas are [written here](docs/IDEAS.markdown).**

## Team Member

| Name                  | Email                 | GitHub |
|-----------------------|-----------------------|--------|
| Ekky Bayu Pramana     | ekkypramana@gmail.com | [@ekkyvalent](https://github.com/ekkyvalent)
| Muhammad Haidar Hanif | me@mhaidarhanif.com   | [@mhaidarh](https://github.com/mhaidarh)
| Muhammad Patria       | muhpatr@gmail.com     | [@muhpatr](https://github.com/muhpatr)
| Ruth Theodora Lubis   | rutheodora@gmail.com  | [@rutheodora](https://github.com/rutheodora)

**See the detailed [Roles and Responsibilities here](docs/ROLES.markdown).**

--------------------------------------------------

## How to use this repo

This repo is using `git submodules` for `app`, `slide`, and `web`. You are recommended to clone this repo with `git clone --recursive`. Or if you want, or have regular clone already, or is experiencing a slow connection; please sync, init, and update the submodules like the following. Please keep in mind that you should not modify or work in the synced submodules, but work in each single repo itself.

```
git submodule sync
git submodule init
git submodule update --recursive
```

### Only for maintainers

To update all submodules recursively, use `git submodule update --remote --recursive` and then commit your update.

--------------------------------------------------

## Extensive Product Documentation

See the [Product document](docs/product.markdown).
In the first time, we're presenting the ideas with [our `slide` here](https://github.com/gunadarma-academy/asde-michi-slide).

## Project Management Documentation

See the [Project Management document](docs/project-management.markdown).
We're mainly using [GitHub Issues](https://github.com/gunadarma-academy/asde-michi/issues) and [integrate it to Waffle.io board](https://waffle.io/gunadarma-academy/asde-michi) to track our work progress.

## User Documentation

See the [User Documentation here](docs/user-documentation.markdown).

## Technical Documentation

See the [Technical Documentation here](docs/technical-documentation.markdown).
We're separating the `web` mockup and `app` repo for better development control. [See the web mockup here](https://github.com/gunadarma-academy/asde-michi-web) or [see the application repo here](https://github.com/gunadarma-academy/asde-michi-app).

## General Notes

See the [General Notes here](docs/NOTES.markdown).
By the way, this project or product is originally created for [Advanced Software Development and Engineering (ASDE) course](https://github.com/gunadarma-academy/ASDE). You can expect to see all progress on this project's [GitHub repo](https://github.com/gunadarma-academy/asde-michi), as well as its [issues](https://github.com/gunadarma-academy/asde-michi/issues) and [milestones](https://github.com/gunadarma-academy/asde-michi/milestones).
