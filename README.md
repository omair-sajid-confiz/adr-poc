# ADR Demo

Demo project to showcase how to manage ADR using [adr-tools](https://github.com/npryce/adr-tools)


## Demo Steps

### Step 1

Create a new git project using [Git Flow](https://github.com/nvie/gitflow) and add README file

### Step 2

Initialize adr using following command

```
adr init

```

This will create doc/adr directory and will add first ADR to this directory. First ADR just documents the fact that we are going to use ADR for documenting all our architecure decisions

### Step 3

Adda a new ADR using

```
adr new Use Swagger to document APIs
```

This will creae a new ADR file named doc/adr/0002-use-swagger-to-document-apis.md. As this is demo only so we are not updating content of ADR file but in real world this should explain why are we using swagger. Although in case of swagger real question would be why you are not using swagger

The file will look something like this

```
Date: 2018-09-17

## Status

Accepted

## Context

The issue motivating this decision, and any context that influences or constrains the decision.

## Decision

The change that we're proposing or have agreed to implement.

## Consequences

What becomes easier or more difficult to do and any risks introduced by the change that will need to be mitigated.

```

