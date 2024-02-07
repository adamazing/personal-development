# Adam's Personal Development Repo

A repository for all links/notes/docs/spikes/projects related to @adamazing's personal development, in and out of Flick.

# Introduction

This README should provide a high-ish-level plan for the next 6-12 months of personal development time, in and out of Flick.
The structure of the repository is subject to change, but should prioritise discoverability/recall of evidence of work/play in support
of my personal development goals and provide personal accountability.

# Goals / Areas Of Focus

  > *A goal is not always meant to be reached, it often serves simply as something to aim at.* <br />
  > &nbsp;&nbsp;&nbsp;  ---   Bruce Lee

Goals are at the highest level and a target to aim at.

## Flick Performance-Review Related Goals

These goals are 6-12 month performance-review goals for the current (2022-2023) cycle as set with @DanM in 1-on-1s.
See: [Small Improvements](https://app.small-improvements.com/app/objectives).

  1. Lead discussions about squad practices and processes and discusses improvements with the squad
      - [Small Improvements](https://app.small-improvements.com/app/objectives/YkyEMuYF3OktAKylEnSgoA/q048JXuh6cY5UBWvEalagw)
      - [PD Repo](/review-objectives/2022-2023-cycle/squad-practices/README.md)
  1. Have a thorough understanding of their squad's domain and Electricity Retailer marketplace, and how it contributes to overall business strategy
      - [Small Improvements](https://app.small-improvements.com/app/objectives/YkyEMuYF3OktAKylEnSgoA/4E202NttCYRC6vwrjlF0rw)
      - [PD Repo](/review-objectives/2022-2023-cycle/understanding-enable-domain/README.md)
  1. Work breakdown as part of incremental value delivery
      - [Small Improvements](https://app.small-improvements.com/app/objectives/YkyEMuYF3OktAKylEnSgoA/qU0dIFREAtjN5SWuvQvmsw)
      - [PD Repo](/review-objectives/2022-2023-cycle/work-breakdown/README.md)

## Personal Goals

These are personal goals that may or may not be technical in nature and may or may not even be career related.

  1. Solidify & develop knowledge of new Rails features
      1. Hotwire/Rails 7
  1. Build People Lead skills
      1. Go through Ankita Kulkarni course
      1. Read Managing Humans on Bookshelf

----

# Strategic Objectives

## Specific Areas of Study/Development To Support Flick Performance Goals

Ideas for PD time or hackdays that aim to directly support performance goals. Where applicable, record which high-level goal is supported by the task/activity or reading/resource.

### Tasks / Activities

  * Diagram processes / current state of Enable services (Goals 1 & 2)
    * ~~Use [PlantUML](https://plantuml.com) to diagram Payment Arrangements work~~
    * ~~Use PlantUML to diagram Enable-stewarded services and their interactions, e.g. Billing/Payments~~
    * Use Miro to whiteboard payments admin app flows/actions
    * Look at other Diagram-As-Code tools more suited for describing flows & system interactions than PlantUML, e.g. [Mermaid](https://mermaid.js.org/intro)
  * Task breakdown activities
    * Join Elspeth to refine user stories for Billing Tools.
  * Take notes on squad practices and actions
    * Contribute more during retrospectives
    * Contribute ideas for actions/ways-of-working

### Reading / Resources

  * Architectural Thinking
    * [Domain Driven Design](https://martinfowler.com/bliki/DomainDrivenDesign.html)
    * [Domain Driven Design Albera Tree](https://app.albera.com/u/adam935ee6/domain-driven-design/)
    * [Microservices Architecture Albera Tree](https://app.albera.com/u/adam935ee6/microservices-architecture/)
  * ...

# Flick Hackdays Projects

Notes about past, present, and future projects completed/planned for hackdays/hack time.

### ZSH (And Posix) Scripting

`flick_cli` has a shell-script component that launches various commands like aws, terraform, etc. but also connects to the rails console and bash console on instances of Flick services.
  * Adding auto-complete configuration files for flick_cli
  * Adding auto-complete auto-install
  * Making the foreground and background colours shown for production instances of Flick services configurable.

### Flick Lint

`flick_lint` is a central repository for lint configs/coding standards tools, i.e. Rubocop
  * Hacktime projects:
    * Custom Rubocops
    * Adding auto-correction rules for existing custom rubocops <- Love this!
    * Adding flick_lint to projects/services depending on rubocop directly.

## Personal Development supporting Hackdays projects

A place to record any personal/work PD time invested in growing skills that may be only tangentially related to day-to-day Flick-work.
E.g. Time spent researching other services ahead of a hackdays project in another squad's domain

  * ...


<br />
<br />

-----

<br />
<br />

# Other Interests

This section is for dumping things I'm doing outside of work:

## [Rustlang](https://www.rust-lang.org/)

  * Knowledge
    * [Rust By Example Book](https://doc.rust-lang.org/rust-by-example/index.html)
    * ...
  * Project Repositories
    * [rust-by-example](https://github.com/adamazing/rust-by-example)
      - A repo for exercises, trying things out, expanding on book examples.
    * [bevy-tutorial](https://github.com/adamazing/bevy-tutorial)
      - Working through the bevy tutorial to build a little game.
    * [colorbuddy](https://github.com/adamazing/colorbuddy)
      - A command line tool for generating a color palette from an image.
  * Exercises / Kata / Testing
    * [Exercism Rust Track]()
  * Communication
    * ...

## Upskilling platforms to investigate

### Codecrafters
[https://app.codecrafters.io/](https://app.codecrafters.io/)

[Discounted sign-up link](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbjNuUlN3WEc5RDFmMjVsNkhheTBaRm9od01yQXxBQ3Jtc0ttNWx2dmxjZkNOeWcwdzdYMEpBM1BpX0NBcDlhbmhGQkh4MTZpWHl6U3hWb0NMaFBWWVdDRGhyanl4Xy1VeElVUGQzN21tOEx1OUhVX19nMXpJTGlpb3lINy1OajZjV2JjTDE3cmxsS1VyS21xT0Viaw&q=https%3A%2F%2Fapp.codecrafters.io%2Fjoin%3Fvia%3Djonhoo&v=jf_ddGnum_4)

**N.B.**  
 - Prices in US Dollars
 - One off payments
#### Membership benefits

|     |Base| Membership | Teams (5+)|
|:----|:---|:-----------|:----------|
|Cost|Free|From $40/m (see below)| From $39/month/seat|
|Features:|Limited content access|Everything in Base plan|Everything in Membership plan|
||Community features|No limits on content|Unlimited seat re-assigns|
|||Access to Perks|Team leaderboard|
|||Priority support|Team usage analytics|
||||Slack app|
||[Get started](https://app.codecrafters.io/catalog)|[Get membership](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbjNuUlN3WEc5RDFmMjVsNkhheTBaRm9od01yQXxBQ3Jtc0ttNWx2dmxjZkNOeWcwdzdYMEpBM1BpX0NBcDlhbmhGQkh4MTZpWHl6U3hWb0NMaFBWWVdDRGhyanl4Xy1VeElVUGQzN21tOEx1OUhVX19nMXpJTGlpb3lINy1OajZjV2JjTDE3cmxsS1VyS21xT0Viaw&q=https%3A%2F%2Fapp.codecrafters.io%2Fjoin%3Fvia%3Djonhoo&v=jf_ddGnum_4)|[Get team plan](https://app.codecrafters.io/teams/pay)|

#### Pricing

|Price|Duration|Notes||
|:--|:--|--|--
|$120| 3 months|
|$216| 1 year| $360 without discount|
|$990| Lifetime access||
