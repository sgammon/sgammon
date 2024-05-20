## open source work

### I am the author of

- [`less.build`](https://less.build): Universal remote build cache for Maven, Gradle, Bazel, TurboRepo, CCache, SCCache, and more.

- [`elide.dev`](https://elide.dev): Polyglot Node-like runtime via [GraalVM](https://graalvm.org).

- [`rules_graalvm`](https://github.com/sgammon/rules_graalvm): Use [GraalVM](https://graalvm.org) from [Bazel](https://bazel.build), with support for `native-image` on Linux, macOS, Windows, and Bazel 4-7.

- [`rules_gradle`](https://github.com/sgammon/rules_gradle): Use [Gradle](https://gradle.org) from within your [Bazel](https://bazel.build) build; run Gradle builds within Bazel's sandbox.

- [`jpms.pkg.st`](https://github.com/javamodules/attic): The "JPMS Attic" repository lets you safely use Java Modules artifacts from the future, before they are officially released.

- [`hashlock`](https://github.com/sgammon/hashlock): Bun/Node/Deno CLI/library/GitHub Action for verifying `smth.sha256`-style "hash lock" files

### I am a contributor to

- [`node-glob`](https://github.com/isaacs/node-glob): Added Deno compat to one of the most popular NPM packages on earth (31k dependents)

- [`commander.js`](https://github.com/tj/commander.js): I made the popular `commander` library compatible with Deno

- [Google: Guava](https://github.com/google/guava): I've helped fix some build issues in Maven, and introduced JPMS support

- [Google: Error Prone Compiler](https://github.com/google/error-prone): I contributed [JPMS support](https://github.com/google/error-prone/pull/4311) to the Error Prone Annotations, released at [`2.26.1`](https://github.com/google/error-prone/releases/tag/v2.26.1)

- [Google: J2ObjC](https://github.com/google/j2objc): I contributed [JPMS support](https://github.com/google/j2objc/pull/2302), released at [`3.0.0`](https://github.com/google/j2objc/commit/a883dd3f90d51d5ccad4aa3af8feaaeed6560109)

- [Micronaut](https://micronaut.io): I contributed [Soy integration for `micronaut-views`](https://micronaut-projects.github.io/micronaut-views/latest/guide/#soy)

- [Axios](https://github.com/axios/axios): I contributed a [`fetch`-based adapter for Axios](https://github.com/axios/axios/pull/5146)

- [Redisson](https://redisson.org): I added support for [`io_uring`](https://github.com/netty/netty-incubator-transport-io_uring) (thanks to Netty it was only a few lines)

- [Buildkite](https://buildkite.com): I added the emojis for [Buf, Gitpod, Copybara and Cloudflare](https://github.com/buildkite/emojis/pulls?q=author%3Asgammon)


#### Lost to the sands of time

Some of these PRs are now obsolete or were never merged, but they are lovely nonetheless.

- [`rules_buf`](https://github.com/sgammon/rules_buf): Use [Buf](https://buf.build) from your [Bazel](https://bazel.build) build.

- [`canteen`](https://github.com/sgammon/canteen): Python framework which "holds a little bit more water than a Flask." Includes a nice DSL for graph-style in-memory databasing on top of Redis.

- [Closure Compiler](https://github.com/google/closure-compiler): I contributed a [GraalVM native image](https://github.com/google/closure-compiler/pull/3958) of Closure which accelerated JS builds up to 70%
