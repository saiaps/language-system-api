# language-system-api
Every language system in production at SAiaPS must provide the capabilities delineated here.
The canonical page for the language should describe both the current target answers for the language 
and all historical answers that are still in use. That way people know how to use what's there, and also
know what not to copy.

## Story

### Purpose

Why was this language chosen? What kind of applications do we write in it? 
Why would you choose this language over any other at SAiaPS, and when would you not choose it?

### Keepers

What team keeps the tooling and recommendations up to date? Who do you go to with questions?

## Development

### Project Creation

How do I make a new application in this language? What are the standard starting points, and where does it get configured?

### Development environment

What tools do we use to write code here?

Ideally, provide a script for setting up a development environment. This may be in a container.

### Tests

How do we run tests? what frameworks are in use, and how do you run them?

Describe testing practices. Do we use a REPL? Unit tests? API-level tests?

### Build tools

What build tool and dependency manager does a developer need to install?

### Running locally

How do we make it go? How do we hit it when it's going?

### Continuous Integration

Where do automated tests get run, artifacts built, etc? How do you see it, and how do you set it up?

### Libraries

Please specify standard libraries to use for these things, or "Please don't" if we don't use this language for these activities.

Please tell us how to import the libraries, as well. Describe how dependency management works in this language system.

#### HTTP calls

#### Serialization

Whatever serialization formats are used in this org.

#### Logging

#### Configuration

What are our configuration practices?

#### Database

Every database that we use in this organization: how do we access it from this language?

### Artifacts

For libraries and applications, where are artifacts stored?

### Deployment

How do we get applications into production?
Is there a language-specific deploy process, or a particular configuration of the org-wide deployment tool?

## Logging

There's one log aggregator across the organization. How do we send logs to it?

## Alerting

How do alerts from these applications get to people?
