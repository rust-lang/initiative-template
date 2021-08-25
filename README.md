# {{INITIATIVE_NAME}} initiative
<!--
 This is the template for creating an initiative in rust-lang. Be sure to go
 through all sections marked with `**FIX ME**`, and make sure that the text is
 correct, and feel free to replace/remove any part that's not relevant to
 your group.

 All of the text across all of the initial files uses the same group of
 variables to allow for easy search and replace. They are listed below.

 Example sed command: `sed -i '' 's/{{INITIATIVE_NAME}}/Inline ASM/g' ./**/*.md`
 *Note* the `-i ''` is important as it is required on some platforms e.g. macOS

 * {{INITIATIVE_NAME}} -> The display name of your group e.g. "Inline ASM".
 * {{INITIATIVE_SLUG}} -> The url slug name of your group used for
   `rust-lang/team` and repo name. e.g. "pg-inline-asm".
 * {{CHAT_PLATFORM}} -> The name of your chat app e.g. "Zulip".
 * {{CHAT_LINK}} -> The hyperlink to your discussions on the chat app
   e.g. "https://rust-lang.zulipchat.com/#narrow/stream/216763-project-inline-asm".
-->

<!--
 Status badge advertising the project as being actively worked on. When the
 project has finished be sure to replace the active badge with a badge
 like: https://img.shields.io/badge/status-archived-grey.svg
-->
![initiative status: active](https://img.shields.io/badge/status-active-brightgreen.svg)
[![initiative documentation](https://img.shields.io/badge/MDBook-View%20Documentation-blue)][gh-pages]


**FIX ME**

<!--
 Provide a short introduction about your initiative. Make sure to include any
 relevant links to information about your group.
-->

Welcome to the repository for the {{INITIATIVE_NAME}} [initiative]! This is the repository we use to organise our work. Please refer to our [charter] as well as our [github pages website][gh-pages] for more information on our goals and current scope.

[charter]: ./CHARTER.md
[gh-pages]: https://rust-lang.github.io/{{INITIATIVE_SLUG}}
[initiative]: https://lang-team.rust-lang.org/initiatives.html

**/FIX ME**

## Current status

The following table lists of the stages of an initiative, along with links to the artifacts that will be produced by the start of that stage.

| Stage                                 | State | Artifact(s) |
| ------------------------------------- | ----- | ----------- |
| [Proposal]                            | ✅    | [Proposal issue](https://github.com/rust-lang/lang-team/) |
| [Experimental]                        | 🦀    | [Charter](./CHARTER.md) |
|                                       |       | [Tracking issue](https://github.com/rust-lang/rust/) |
| [Development]                         | 💤    | [Evaluation](./Evaluation.md) |
|                                       |       | [RFC](./RFC.md) |
| [Feature complete]                    | 💤    | Explainer| 
| [Stabilized]                          | 💤    | Stabilization report |

[Proposal]: https://lang-team.rust-lang.org/initiatives/process/stages/proposal.html
[Experimental]: https://lang-team.rust-lang.org/initiatives/process/stages/proposal.html
[Development]: https://lang-team.rust-lang.org/initiatives/process/stages/development.html
[Feature complete]: https://lang-team.rust-lang.org/initiatives/process/stages/feature-complete.html
[Stabilized]: https://lang-team.rust-lang.org/initiatives/process/stages/stabilized.html

Key:

* ✅ -- phase complete
* 🦀 -- phase in progress
* 💤 -- phase not started yet

## How Can I Get Involved?

**FIX ME**

<!--
 List ways that people from outside your group can get involved and potentially
 become members, include what meetings your team has, and how a person could
 start participating and contributing. Make sure to mention the main platform
 your group hosts its discussions. Be sure to also include links to any
 other projects that your group maintains.
-->

The issues from this repository

[You can find a list of the current members available
on `rust-lang/team`.][team-toml]

If you'd like to participate be sure to check out any of our [open issues] on this
repository.

We also participate on [{{CHAT_PLATFORM}}][chat-link], feel free to introduce
yourself over there and ask us any questions you have.


[open issues]: /issues
[chat-link]: {{CHAT_LINK}}
[team-toml]: https://github.com/rust-lang/team/blob/master/teams/initiative-{{INITIATIVE_SLUG}}.toml

**/FIX ME**

## Building Documentation
This repository is also an mdbook project. You can view and build it using the
following command.

```
mdbook serve
```
