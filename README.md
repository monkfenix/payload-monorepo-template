# A template for a Payload Monorepo design

Monorepo template for starting a long term evolving Payload project
Most credit goes to the Payload team authoring [this](https://payloadcms.com/blog/typescript-jest-vscode-debugger-tutorial) which guided setting up the repo and initial types.

## Motivation

The goal here is to get an "evolutionary" project template design. Using a Yarn monorepo with just one sample project may seem like overkill, but the idea here is to evolve the monorepo over time so that the folder with ts-payload serves as a "copy template" which can be reused multiple times for multiple "apps" and eventually thru code review and refactoring, draw out the common bits amongst projects to the monorepo structure to allow independent development, while still maintaining their reference context over time by the other app folders or projects that utilise them.
