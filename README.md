# Welcome to dbtonic

dbtonic is a dbt linter designed from the ground up for use with dbt. 

## Why dbtonic
The term `dbtonic` is used sporadically in the dbt community to describe dbt code that satisfies our best practices. Some of these practices are defined in the dbt Labs LINK HERE while others are a bit more ephemeral. We figured that codifying these into a linter would help ensure that every dbt project can benefit from the collective experience of the community.

The inspiration for this project came from INSERT NAME's original post around the `ruff` python linter. He stated:
> Ruff is based on two core hypothesis:
> - Python tooling could be rewritten in more performant langauges
> - An integrated toolchain can tap into efficiencies that aren't available to a disparate set of tools

It got me thinking about what a similar implementation for dbt would look like. I decided to start from the `dbt_project_evaluator` dbt package that some of my amazing colleagues worked on and see what it would look like if we converted it to Rust. 

## Why use dbtonic

If you're finding this repo before I post about it publically, I'd recommend you turn around and cast this from your mind. I am not a professional programmer and this repo probably has bugs galore! 

If I've announced it publically then the above statement is still true but I've decided that I have enough confidence in its use for experimental use. The actual reason is easy - it's fast! dbt developers deserve great experiences that aren't constrained by the limitations of languages we're most familiar with. We should have access to tools that operate just like any other programming language. 

dbtonic's long term vision is to provide a dbt-first linting experience. **However**, I have a day job at dbt Labs that does not include this area so lets just say development is sporadic!
