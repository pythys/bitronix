# Bitronix Transaction Manager (BTM)

Bitronix Transaction Manager (BTM) is a simple but complete implementation of
the Java Transaction API (JTA) 1.1. This eXtended Architecture (XA) transaction
manager provides all services required by the JTA while keeping the code as
simple as possible for easier understanding of XA semantics.

## Maintainers

Lead Maintainer: Taher Alkhateeb <taher@pythys.com>

## Building

To build this project, you must have JDK17+ installed on your machine.

`./mvnw clean install`

## Documentation

Javadocs:
  - generate: `./mvnw javadocs:javadocs`
  - view: `btm/target/reports/apidocs/index.html`

Asciidocs:
  - generate: `./mvnw generate-resources`
  - view: `btm-docs/target/generated-docs/index.html`

## Linting

check linting issues:
`./mvnw spotless:check`

fix linting issues:
`./mvnw spotless:apply`

## Credits

BTM was created and maintained by the Bitronix team, namely:

- [Ludovic Orban](https://x.com/bitronix) (Original Author)
- [Brett Wooldridge](https://x.com/BrettWooldridge) (Former Maintainer)
