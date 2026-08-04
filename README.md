# Cucumber (cucumber)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Cucumber is an open-source Behavior Driven Development (BDD) tool for running automated tests written in plain language using the Gherkin syntax. It enables collaboration between technical and non-technical team members by expressing executable specifications as Given/When/Then scenarios. Cucumber has implementations for many languages (JVM, JavaScript, Ruby, .NET, Python, Go, Rust) and a shared message protocol that connects parsers, runners, and reporters.

**APIs.yml URL:** https://raw.githubusercontent.com/api-evangelist/cucumber/refs/heads/main/apis.yml

## Scope

- **Type:** Index
- **x-type:** opensource

## Tags

Automation, BDD, Behavior Driven Development, Gherkin, Open Source, Quality Assurance, Test Framework, Testing

## Implementations

### Cucumber JVM
Java/JVM implementation distributed via Maven Central (io.cucumber).
- https://github.com/cucumber/cucumber-jvm

### Cucumber.js
JavaScript/Node.js implementation distributed as @cucumber/cucumber on npm.
- https://github.com/cucumber/cucumber-js

### Cucumber Ruby
The original Ruby implementation, distributed as the cucumber gem.
- https://github.com/cucumber/cucumber-ruby

### Gherkin
The DSL parsers powering all Cucumber implementations.
- https://github.com/cucumber/gherkin

### Cucumber Messages
The protocol for messages exchanged between parsers, runners, and formatters.
- https://github.com/cucumber/messages

## Features

- Plain-language specifications via Gherkin
- Implementations for JVM, JavaScript, Ruby, .NET, Python, Go, and Rust
- Step definitions with Cucumber Expressions or regex
- Hooks and tag-driven configuration
- Cucumber Messages protocol shared across implementations
- Pluggable formatters (pretty, JSON, JUnit, HTML)
- Parallel scenario execution
- CI integration through JUnit/HTML reporting

## Use Cases

- Acceptance testing in cross-functional teams
- Living documentation of system behavior
- API contract testing in BDD style
- Tagged regression suites for CI
- Cross-team communication and shared specifications

## Artifacts

- JSON Schema (Cucumber Messages): [json-schema/cucumber-message-schema.json](json-schema/cucumber-message-schema.json)
- JSON-LD Context: [json-ld/cucumber-context.jsonld](json-ld/cucumber-context.jsonld)
- Vocabulary: [vocabulary/cucumber-vocabulary.yml](vocabulary/cucumber-vocabulary.yml)

## Resources

- Website: https://cucumber.io
- Documentation: https://cucumber.io/docs
- Gherkin Reference: https://cucumber.io/docs/gherkin/reference/
- Cucumber School: https://school.cucumber.io
- GitHub: https://github.com/cucumber

## Maintainers

- Kin Lane (kin@apievangelist.com)
