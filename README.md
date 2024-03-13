<img align="right" src="https://github-readme-stats.vercel.app/api?username=sgammon&theme=ambient_gradient&show_icons=true&icon_color=FFFFFF&text_color=FFFFFF&hide_title=true&hide_border=true" />

# 👋 Hi there

I'm Sam. I'm a passionate entrepreneur and software professional living in the SF Bay Area. I'm here on Github building stuff like [Elide](https://github.com/elide-dev/elide), a modern
polyglot runtime which Makes Software Fun Again.

## Drop me a line

If you're interested in collaborating or chatting, email me at sam at elide (dot) dev, or [join the ɴᴜʟʟclub Discord](https://elide.dev/discord), where you can find me in the `#elide` or `#general` rooms.

# Current projects

## buildless

We've launched [Buildless](https://less.build) in private beta 🎉. It's a remote build cache, backed by the power of Cloudflare. If you use Gradle, Maven, CCache, Bazel, Turbo, or several other build systems, you can drop in Buildless as a remote cache and share compiled outputs with your friends. Use Buildless from Java, Kotlin, JavaScript, Rust, C/C++, and more. Buildless is part of the Elide Cloud family of devops tools.

## pkgst

[Pkgst](https://docs.less.build/docs/pkgst) is a caching dependency proxy built in partnership with [Cloudflare](https://cloudflare.com). It can accelerate your dependency downloads from Maven, NPM, PyPi, BCR, and more.

## elide

[Elide](https://elide.dev) is a new polyglot software runtime. You can write programs in any mix of JVM (Kotlin, Java), JavaScript/TypeScript, Python, Ruby, LLVM, and WASM. Elide lets you re-use more code than before and, in many cases, outperforms equivalent stock runtimes (in some cases by up to 74x).


## Other open source work

### I am the author of

- [`less.build`](https://less.build): Universal remote build cache for Maven, Gradle, Bazel, TurboRepo, CCache, SCCache, and more.

- [`elide.dev`](https://elide.dev): Polyglot Node-like runtime via [GraalVM](https://graalvm.org).

- [`rules_graalvm`](https://github.com/sgammon/rules_graalvm): Use [GraalVM](https://graalvm.org) from [Bazel](https://bazel.build), with support for `native-image` on Linux, macOS, Windows, and Bazel 4-7.

- [`rules_gradle`](https://github.com/sgammon/rules_gradle): Use [Gradle](https://gradle.org) from within your [Bazel](https://bazel.build) build; run Gradle builds within Bazel's sandbox.

- [`jpms.pkg.st`](https://github.com/javamodules/attic): The "JPMS Attic" repository lets you safely use Java Modules artifacts from the future, before they are officially released.

### I am a contributor to

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
