### Admin Manual for Definitely Typed

Welcome! This is a resource for the person who is on call for DefinitelyTyped. 

When on-call your goal is to try keep on top of the many open PRs for DefinitelyTyped, they are catagorized into 
different sections inside the [Projects board](https://github.com/DefinitelyTyped/DefinitelyTyped/projects/4) on this repo.

You should scan from left to right through the boards, and ideally try to start at the latest PR and work your way 
through to the newest.

There is a tool: [`focus-dt`](https://github.com/DefinitelyTyped/focus-dt) which can help with this.

### Useful Repos and Links

The process of handling PRs:

- [DT projects](https://github.com/DefinitelyTyped/DefinitelyTyped/projects/4) - an automated board saying where open PRs live
- [dt-merge-bot](https://github.com/RyanCavanaugh/dt-mergebot/) - the bot which sets the labels on PRs, and update's project status
- [dt-merge-bot graphql](https://github.com/RyanCavanaugh/dt-mergebot/tree/use-graphql) - the WIP v2 of the bot to automate the labels/projects
- [focus-dt](https://github.com/DefinitelyTyped/focus-dt) - a tool which controls chrome to load up the next PR to review, so you can focus
- [dtslint](https://github.com/microsoft/dtslint) - the CLI tool used to validate PRs on DefinitelyTyped

The process of deploying changes:

- [types-publisher](https://github.com/microsoft/types-publisher) - when a PR is merged, types-publisher moves the contents to NPM/GitHub Package Repository
- [CI](https://dev.azure.com/definitelytyped/DefinitelyTyped/_build) - the build pipelines on Azure which does most of the work

Recommendations we make:

- [dts-gen](https://github.com/Microsoft/dts-gen) - a tool for creating a DT folder automatically
