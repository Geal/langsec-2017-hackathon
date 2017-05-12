% Langsec Workshop 2017: Rust and nom Hackathon
% Pierre Chifflier - Geoffroy Couprie
% 2017/05/25

# Who

* Security and QA at Clever Cloud
* Freelance consultant, security and architecture
* <span class="twitter">@gcouprie</span>
* geoffroy.couprie@clever-cloud.com

<aside class="notes">
rust main language for nearly a year now

we're pushing some Rust in production now
ssh jail, proxy, git subsystems
</details>

# Plan

- study a format
- write a nom parser for the header
- write parsers for the other parts
- fuzz it
- make something useful with the data?

# Prerequisites

- installing Rust with rustup
- work in a Docker image?


# Introduction to Rust

- syntax for functions, etc
- creating a project, adding a dependency


# template project to download

scaffolding to start testing a parser:

- file included with `inculde_bytes!`
- unit tests

# create the first struct

- test with the file beginning
- compare with existing parsers

# add a new struct

- extend the first parser

# test with another file

# integrate fuzzing

# make an API over the parser
