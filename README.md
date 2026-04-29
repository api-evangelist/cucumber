# Cucumber (cucumber)

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
