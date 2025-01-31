---
layout: default
title: Contributing
css-icon: fab fa-github
priority: 1000
---

{% include toc_include.md max_level=2 %}

## Code

All new development happens in the `korge` repository:

<https://github.com/korlibs/korge>

You can fork the repository, make changes and create a PR proposing them.

### Building

You can build `korge` with:

```kotlin
git clone https://github.com/korlibs/korge.git
cd korge
./gradlew publishToMavenLocal
```

This publishes all the libraries with the version `2.0.0.999` in the `~/.m2` folder.

To make compilation faster, you can add `org.gradle.parallel=true` to your `~/.gradle/gradle.properties` file (crete it if it doesn't exist).

### Using `korge-next` in a KorGE project

To use korge-next in a KorGE project, just build and publish it locally and replace your version with `2.0.0.999`.

## Documentation

Did you find something **wrong**, **misleading** or **confusing**? Or just want to add more content to the documentation?

In order to make it easier to contribute, each page of the documentation contains a `Suggest Change / Typo`,
so you can propose a change.

<img src="/contributing/suggest_change.png" style="border: 2px solid black;" />

All the documentation is hosted at github using github pages and [jekyll](https://jekyllrb.com/):

<https://github.com/korlibs/korge/tree/main/docs>

