# Learn Go

Sections and links are ordered alphabetically.

See the Tracks section to get started.

Some thoughts that may help you acclimate:

### Language

Go has an opinioned design.
Whereas some languages enable, and even encourage, more than one way to do things, for Go there is only the Go Way.
This is what is meant by Go idioms or being idiomatic Go.
Things tend to be simpler and easier if you do them the Go Way.

Go is a relatively new language and does some things differently:

- Single command-line tool
- Built-in building, installing, running, testing, benchmarking, profiling, vendoring, code generation, build constraints, and documentation
- Decentralized package management
- Clean, quiet, and fast builds
- Cross compilation
- Standard code style and formatter
- Concurrency support and automatic parallelism
- Composition instead of inheritance
- Crashing early for programmer errors
- No assertions
- Table-driven tests
- No leveled logging

Go was made to fill a void: writing high-performance server software productively.
Go is not suitable for all purposes.

### Team

The core group of engineers that contribute to Go are called the Go Team.
They are smart, thoughtful, opinionated, and principled.
They are also pragmatic and careful.
They can be [abrasive](https://twitter.com/rob_pike/status/617548868641656832); try not to take it personally.

They do not add something if they do not know how to do it well, and they are serious about the Go 1 compatibility promise.
These explain why Go lacked or lacks some features.

The [Gopher](https://blog.golang.org/gopher) is the official Go mascot and community members are called Gophers.

### Community

The Go community is large and thriving.
A new language means new opportunities for new libraries and tools.
There are many open-source packages.
There are many companies using Go.
There are many places to go for help.
There are many conferences and meetups.
Sometimes Go Team members attend [the San Francisco Go meetup](https://www.meetup.com/golangsf) and [the Sydney Go meetup](https://www.meetup.com/golang-syd).
There is a [code of conduct](https://golang.org/conduct) for communities moderated by the Go Team.

## Articles

Advice:

- [http://www.golangbootcamp.com/book/tricks_and_tips](http://www.golangbootcamp.com/book/tricks_and_tips)
- [https://blog.rubylearning.com/best-practices-for-a-new-go-developer-8660384302fc](https://blog.rubylearning.com/best-practices-for-a-new-go-developer-8660384302fc)
- [https://github.com/beyondns/gotips](https://github.com/beyondns/gotips)

Blog:

- [https://blog.golang.org/c-go-cgo](https://blog.golang.org/c-go-cgo)
- [https://blog.golang.org/constants](https://blog.golang.org/constants)
- [https://blog.golang.org/context](https://blog.golang.org/context)
- [https://blog.golang.org/cover](https://blog.golang.org/cover)
- [https://blog.golang.org/defer-panic-and-recover](https://blog.golang.org/defer-panic-and-recover)
- [https://blog.golang.org/error-handling-and-go](https://blog.golang.org/error-handling-and-go)
- [https://blog.golang.org/errors-are-values](https://blog.golang.org/errors-are-values)
- [https://blog.golang.org/examples](https://blog.golang.org/examples)
- [https://blog.golang.org/generate](https://blog.golang.org/generate)
- [https://blog.golang.org/go-concurrency-patterns-timing-out-and](https://blog.golang.org/go-concurrency-patterns-timing-out-and)
- [https://blog.golang.org/go-fmt-your-code](https://blog.golang.org/go-fmt-your-code)
- [https://blog.golang.org/go-maps-in-action](https://blog.golang.org/go-maps-in-action)
- [https://blog.golang.org/go-slices-usage-and-internals](https://blog.golang.org/go-slices-usage-and-internals)
- [https://blog.golang.org/go15gc](https://blog.golang.org/go15gc)
- [https://blog.golang.org/gobs-of-data](https://blog.golang.org/gobs-of-data)
- [https://blog.golang.org/godoc-documenting-go-code](https://blog.golang.org/godoc-documenting-go-code)
- [https://blog.golang.org/gopher](https://blog.golang.org/gopher)
- [https://blog.golang.org/gophercon2015](https://blog.golang.org/gophercon2015)
- [https://blog.golang.org/gos-declaration-syntax](https://blog.golang.org/gos-declaration-syntax)
- [https://blog.golang.org/http-tracing](https://blog.golang.org/http-tracing)
- [https://blog.golang.org/json-and-go](https://blog.golang.org/json-and-go)
- [https://blog.golang.org/laws-of-reflection](https://blog.golang.org/laws-of-reflection)
- [https://blog.golang.org/matchlang](https://blog.golang.org/matchlang)
- [https://blog.golang.org/normalization](https://blog.golang.org/normalization)
- [https://blog.golang.org/open-source](https://blog.golang.org/open-source)
- [https://blog.golang.org/organizing-go-code](https://blog.golang.org/organizing-go-code)
- [https://blog.golang.org/package-names](https://blog.golang.org/package-names)
- [https://blog.golang.org/pipelines](https://blog.golang.org/pipelines)
- [https://blog.golang.org/playground](https://blog.golang.org/playground)
- [https://blog.golang.org/profiling-go-programs](https://blog.golang.org/profiling-go-programs)
- [https://blog.golang.org/share-memory-by-communicating](https://blog.golang.org/share-memory-by-communicating)
- [https://blog.golang.org/slices](https://blog.golang.org/slices)
- [https://blog.golang.org/strings](https://blog.golang.org/strings)
- [https://blog.golang.org/subtests](https://blog.golang.org/subtests)
- [https://blog.golang.org](https://blog.golang.org)

Dave Cheney:

- [https://dave.cheney.net/2010/10/05/how-to-dial-remote-ssltls-services-in-go](https://dave.cheney.net/2010/10/05/how-to-dial-remote-ssltls-services-in-go)
- [https://dave.cheney.net/2010/11/21/how-to-run-godoc-under-launchd-on-os-x](https://dave.cheney.net/2010/11/21/how-to-run-godoc-under-launchd-on-os-x)
- [https://dave.cheney.net/2011/02/19/using-multicast-udp-in-go](https://dave.cheney.net/2011/02/19/using-multicast-udp-in-go)
- [https://dave.cheney.net/2011/07/31/simple-extended-attribute-support-for-go](https://dave.cheney.net/2011/07/31/simple-extended-attribute-support-for-go)
- [https://dave.cheney.net/2012/01/18/why-go-gets-exceptions-right](https://dave.cheney.net/2012/01/18/why-go-gets-exceptions-right)
- [https://dave.cheney.net/2012/02/11/how-the-go-language-improves-expressiveness-without-sacrificing-runtime-performance](https://dave.cheney.net/2012/02/11/how-the-go-language-improves-expressiveness-without-sacrificing-runtime-performance)
- [https://dave.cheney.net/2012/09/08/an-introduction-to-cross-compilation-with-go](https://dave.cheney.net/2012/09/08/an-introduction-to-cross-compilation-with-go)
- [https://dave.cheney.net/2012/10/07/notes-on-exploring-the-compiler-flags-in-the-go-compiler-suite](https://dave.cheney.net/2012/10/07/notes-on-exploring-the-compiler-flags-in-the-go-compiler-suite)
- [https://dave.cheney.net/2013/01/19/what-is-the-zero-value-and-why-is-it-useful](https://dave.cheney.net/2013/01/19/what-is-the-zero-value-and-why-is-it-useful)
- [https://dave.cheney.net/2013/04/30/curious-channels](https://dave.cheney.net/2013/04/30/curious-channels)
- [https://dave.cheney.net/2013/06/02/why-is-a-goroutines-stack-infinite](https://dave.cheney.net/2013/06/02/why-is-a-goroutines-stack-infinite)
- [https://dave.cheney.net/2013/06/04/how-go-uses-go-to-build-itself](https://dave.cheney.net/2013/06/04/how-go-uses-go-to-build-itself)
- [https://dave.cheney.net/2013/06/09/writing-table-driven-tests-in-go](https://dave.cheney.net/2013/06/09/writing-table-driven-tests-in-go)
- [https://dave.cheney.net/2013/06/14/you-dont-need-to-set-goroot-really](https://dave.cheney.net/2013/06/14/you-dont-need-to-set-goroot-really)
- [https://dave.cheney.net/2013/06/19/stress-test-your-go-packages](https://dave.cheney.net/2013/06/19/stress-test-your-go-packages)
- [https://dave.cheney.net/2013/06/30/how-to-write-benchmarks-in-go](https://dave.cheney.net/2013/06/30/how-to-write-benchmarks-in-go)
- [https://dave.cheney.net/2013/09/07/how-to-include-c-code-in-your-go-package](https://dave.cheney.net/2013/09/07/how-to-include-c-code-in-your-go-package)
- [https://dave.cheney.net/2013/10/15/how-does-the-go-build-command-work](https://dave.cheney.net/2013/10/15/how-does-the-go-build-command-work)
- [https://dave.cheney.net/2013/11/07/subcommand-handling-in-go](https://dave.cheney.net/2013/11/07/subcommand-handling-in-go)
- [https://dave.cheney.net/2014/01/21/using-go-test-build-and-install](https://dave.cheney.net/2014/01/21/using-go-test-build-and-install)
- [https://dave.cheney.net/2014/03/17/pointers-in-go](https://dave.cheney.net/2014/03/17/pointers-in-go)
- [https://dave.cheney.net/2014/03/19/channel-axioms](https://dave.cheney.net/2014/03/19/channel-axioms)
- [https://dave.cheney.net/2014/03/25/the-empty-struct](https://dave.cheney.net/2014/03/25/the-empty-struct)
- [https://dave.cheney.net/2014/03/28/associative-commentary](https://dave.cheney.net/2014/03/28/associative-commentary)
- [https://dave.cheney.net/2014/03/30/associative-commentary-follow-up](https://dave.cheney.net/2014/03/30/associative-commentary-follow-up)
- [https://dave.cheney.net/2014/06/07/five-things-that-make-go-fast](https://dave.cheney.net/2014/06/07/five-things-that-make-go-fast)
- [https://dave.cheney.net/2014/06/27/ice-cream-makers-and-data-races](https://dave.cheney.net/2014/06/27/ice-cream-makers-and-data-races)
- [https://dave.cheney.net/2014/07/11/visualising-the-go-garbage-collector](https://dave.cheney.net/2014/07/11/visualising-the-go-garbage-collector)
- [https://dave.cheney.net/2014/09/01/gos-runtime-c-to-go-rewrite-by-the-numbers](https://dave.cheney.net/2014/09/01/gos-runtime-c-to-go-rewrite-by-the-numbers)
- [https://dave.cheney.net/2014/09/14/go-list-your-swiss-army-knife](https://dave.cheney.net/2014/09/14/go-list-your-swiss-army-knife)
- [https://dave.cheney.net/2014/09/28/using-build-to-switch-between-debug-and-release](https://dave.cheney.net/2014/09/28/using-build-to-switch-between-debug-and-release)
- [https://dave.cheney.net/2014/10/17/functional-options-for-friendly-apis](https://dave.cheney.net/2014/10/17/functional-options-for-friendly-apis)
- [https://dave.cheney.net/2014/11/21/visualising-dependencies](https://dave.cheney.net/2014/11/21/visualising-dependencies)
- [https://dave.cheney.net/2014/12/01/five-suggestions-for-setting-up-a-go-project](https://dave.cheney.net/2014/12/01/five-suggestions-for-setting-up-a-go-project)
- [https://dave.cheney.net/2014/12/24/inspecting-errors](https://dave.cheney.net/2014/12/24/inspecting-errors)
- [https://dave.cheney.net/2015/01/26/errors-and-exceptions-redux](https://dave.cheney.net/2015/01/26/errors-and-exceptions-redux)
- [https://dave.cheney.net/2015/03/03/cross-compilation-just-got-a-whole-lot-better-in-go-1-5](https://dave.cheney.net/2015/03/03/cross-compilation-just-got-a-whole-lot-better-in-go-1-5)
- [https://dave.cheney.net/2015/05/22/struct-composition-with-go](https://dave.cheney.net/2015/05/22/struct-composition-with-go)
- [https://dave.cheney.net/2015/08/08/performance-without-the-event-loop](https://dave.cheney.net/2015/08/08/performance-without-the-event-loop)
- [https://dave.cheney.net/2015/08/22/cross-compilation-with-go-1-5](https://dave.cheney.net/2015/08/22/cross-compilation-with-go-1-5)
- [https://dave.cheney.net/2015/10/09/padding-is-hard](https://dave.cheney.net/2015/10/09/padding-is-hard)
- [https://dave.cheney.net/2015/11/05/lets-talk-about-logging](https://dave.cheney.net/2015/11/05/lets-talk-about-logging)
- [https://dave.cheney.net/2015/11/15/the-legacy-of-go](https://dave.cheney.net/2015/11/15/the-legacy-of-go)
- [https://dave.cheney.net/2015/11/18/wednesday-pop-quiz-spot-the-race](https://dave.cheney.net/2015/11/18/wednesday-pop-quiz-spot-the-race)
- [https://dave.cheney.net/2015/11/29/a-whirlwind-tour-of-gos-runtime-environment-variables](https://dave.cheney.net/2015/11/29/a-whirlwind-tour-of-gos-runtime-environment-variables)
- [https://dave.cheney.net/2015/12/07/are-go-maps-sensitive-to-data-races](https://dave.cheney.net/2015/12/07/are-go-maps-sensitive-to-data-races)
- [https://dave.cheney.net/2016/01/18/cgo-is-not-go](https://dave.cheney.net/2016/01/18/cgo-is-not-go)
- [https://dave.cheney.net/2016/02/06/unhelpful-abstractions](https://dave.cheney.net/2016/02/06/unhelpful-abstractions)
- [https://dave.cheney.net/2016/03/19/should-methods-be-declared-on-t-or-t](https://dave.cheney.net/2016/03/19/should-methods-be-declared-on-t-or-t)
- [https://dave.cheney.net/2016/04/07/constant-errors](https://dave.cheney.net/2016/04/07/constant-errors)
- [https://dave.cheney.net/2016/04/27/dont-just-check-errors-handle-them-gracefully](https://dave.cheney.net/2016/04/27/dont-just-check-errors-handle-them-gracefully)
- [https://dave.cheney.net/2016/05/10/test-fixtures-in-go](https://dave.cheney.net/2016/05/10/test-fixtures-in-go)
- [https://dave.cheney.net/2016/06/12/stack-traces-and-the-errors-package](https://dave.cheney.net/2016/06/12/stack-traces-and-the-errors-package)
- [https://dave.cheney.net/2016/06/24/gophers-please-tag-your-releases](https://dave.cheney.net/2016/06/24/gophers-please-tag-your-releases)
- [https://dave.cheney.net/2016/08/20/solid-go-design](https://dave.cheney.net/2016/08/20/solid-go-design)
- [https://dave.cheney.net/2016/11/13/do-not-fear-first-class-functions](https://dave.cheney.net/2016/11/13/do-not-fear-first-class-functions)
- [https://dave.cheney.net/2016/12/15/declaration-scopes-in-go](https://dave.cheney.net/2016/12/15/declaration-scopes-in-go)
- [https://dave.cheney.net/2016/12/20/thinking-about-gopath](https://dave.cheney.net/2016/12/20/thinking-about-gopath)
- [https://dave.cheney.net/resources-for-new-go-programmers](https://dave.cheney.net/resources-for-new-go-programmers)

Rob Pike:

- [https://commandcenter.blogspot.com/2012/06/less-is-exponentially-more.html](https://commandcenter.blogspot.com/2012/06/less-is-exponentially-more.html)
- [https://commandcenter.blogspot.com/2014/01/self-referential-functions-and-design.html](https://commandcenter.blogspot.com/2014/01/self-referential-functions-and-design.html)
- [https://go-proverbs.github.io](https://go-proverbs.github.io)

## Community

- [http://golangweekly.com](http://golangweekly.com)
- [http://www.womenwhogo.org](http://www.womenwhogo.org)
- [https://anvaka.github.io/pm](https://anvaka.github.io/pm)
- [https://changelog.com/gotime](https://changelog.com/gotime)
- [https://coveralls.io](https://coveralls.io)
- [https://forum.golangbridge.org](https://forum.golangbridge.org)
- [https://github.com/avelino/awesome-go](https://github.com/avelino/awesome-go)
- [https://github.com/golang](https://github.com/golang)
- [https://github.com/golang/go](https://github.com/golang/go)
- [https://go-lang.cat-v.org](http://go-lang.cat-v.org)
- [https://go.libhunt.com](https://go.libhunt.com)
- [https://godoc.org](https://godoc.org)
- [https://golang.org/conduct](https://golang.org/conduct)
- [https://golang.org/help](https://golang.org/help)
- [https://golangnews.com](https://golangnews.com)
- [https://gophercon.com](https://gophercon.com)
- [https://gophers.slack.com](https://gophers.slack.com) (sign up on [https://invite.slack.golangbridge.org](https://invite.slack.golangbridge.org))
- [https://gophervids.appspot.com](https://gophervids.appspot.com)
- [https://goreportcard.com](https://goreportcard.com)
- [https://groups.google.com/d/forum/golang-announce](https://groups.google.com/d/forum/golang-announce)
- [https://groups.google.com/d/forum/golang-dev](https://groups.google.com/d/forum/golang-dev)
- [https://groups.google.com/d/forum/golang-nuts](https://groups.google.com/d/forum/golang-nuts)
- [https://stackoverflow.com/tags/go](https://stackoverflow.com/tags/go)
- [https://travis-ci.org](https://travis-ci.org)
- [https://twitter.com/golang](https://twitter.com/golang)
- [https://webchat.freenode.net](https://webchat.freenode.net) (#go-nuts)
- [https://www.meetup.com/atxgolang](https://www.meetup.com/atxgolang)
- [https://www.meetup.com/golang-syd](https://www.meetup.com/golang-syd)
- [https://www.meetup.com/golangsf](https://www.meetup.com/golangsf)
- [https://www.reddit.com/r/golang](https://www.reddit.com/r/golang)
- [https://www.youtube.com/user/gocoding](https://www.youtube.com/user/gocoding)

## Documentation

Web:

- [https://golang.org/doc/articles/go_command.html](https://golang.org/doc/articles/go_command.html)
- [https://golang.org/doc/articles/race_detector.html](https://golang.org/doc/articles/race_detector.html)
- [https://golang.org/doc/articles/wiki](https://golang.org/doc/articles/wiki)
- [https://golang.org/doc/asm](https://golang.org/doc/asm)
- [https://golang.org/doc/cmd](https://golang.org/doc/cmd)
- [https://golang.org/doc/code.html](https://golang.org/doc/code.html)
- [https://golang.org/doc/codewalk/functions](https://golang.org/doc/codewalk/functions)
- [https://golang.org/doc/codewalk/markov](https://golang.org/doc/codewalk/markov)
- [https://golang.org/doc/codewalk/sharemem](https://golang.org/doc/codewalk/sharemem)
- [https://golang.org/doc/devel/release.html](https://golang.org/doc/devel/release.html)
- [https://golang.org/doc/effective_go.html](https://golang.org/doc/effective_go.html)
- [https://golang.org/doc/faq](https://golang.org/doc/faq)
- [https://golang.org/doc/gdb](https://golang.org/doc/gdb)
- [https://golang.org/doc/install/source](https://golang.org/doc/install/source)
- [https://golang.org/doc/install](https://golang.org/doc/install)
- [https://golang.org/doc](https://golang.org/doc)

Commands:

- `go help build`
- `go help clean`
- `go help doc`
- `go help env`
- `go help environment`
- `go help fmt`
- `go help generate`
- `go help get`
- `go help gopath`
- `go help importpath`
- `go help install`
- `go help list`
- `go help packages`
- `go help run`
- `go help test`
- `go help testflag`
- `go help testfunc`
- `go help version`
- `go help vet`
- `go help`

## Introduction

- [https://gobyexample.com](https://gobyexample.com)
- [https://learnxinyminutes.com](https://learnxinyminutes.com)
- [https://play.golang.org](https://play.golang.org)
- [https://tour.golang.org/basics](https://tour.golang.org/basics)
- [https://tour.golang.org/concurrency](https://tour.golang.org/concurrency)
- [https://tour.golang.org/flowcontrol](https://tour.golang.org/flowcontrol)
- [https://tour.golang.org/list](https://tour.golang.org/list)
- [https://tour.golang.org/methods](https://tour.golang.org/methods)
- [https://tour.golang.org/moretypes](https://tour.golang.org/moretypes)
- [https://tour.golang.org/welcome](https://tour.golang.org/welcome)
- [https://tour.golang.org](https://tour.golang.org)

## Libraries

Standard:

- [https://golang.org/pkg/bufio](https://golang.org/pkg/bufio)
- [https://golang.org/pkg/bytes](https://golang.org/pkg/bytes)
- [https://golang.org/pkg/context](https://golang.org/pkg/context)
- [https://golang.org/pkg/crypto/hmac](https://golang.org/pkg/crypto/hmac)
- [https://golang.org/pkg/crypto/sha1](https://golang.org/pkg/crypto/sha1)
- [https://golang.org/pkg/crypto/tls](https://golang.org/pkg/crypto/tls)
- [https://golang.org/pkg/crypto/x509](https://golang.org/pkg/crypto/x509)
- [https://golang.org/pkg/crypto](https://golang.org/pkg/crypto)
- [https://golang.org/pkg/database/sql](https://golang.org/pkg/database/sql)
- [https://golang.org/pkg/encoding/gob](https://golang.org/pkg/encoding/gob)
- [https://golang.org/pkg/encoding/json](https://golang.org/pkg/encoding/json)
- [https://golang.org/pkg/errors](https://golang.org/pkg/errors)
- [https://golang.org/pkg/flag](https://golang.org/pkg/flag)
- [https://golang.org/pkg/fmt](https://golang.org/pkg/fmt)
- [https://golang.org/pkg/io/ioutil](https://golang.org/pkg/io/ioutil)
- [https://golang.org/pkg/io](https://golang.org/pkg/io)
- [https://golang.org/pkg/log](https://golang.org/pkg/log)
- [https://golang.org/pkg/math/big](https://golang.org/pkg/math/big)
- [https://golang.org/pkg/math/rand](https://golang.org/pkg/math/rand)
- [https://golang.org/pkg/math](https://golang.org/pkg/math)
- [https://golang.org/pkg/net/http/httptest](https://golang.org/pkg/net/http/httptest)
- [https://golang.org/pkg/net/http/httptrace](https://golang.org/pkg/net/http/httptrace)
- [https://golang.org/pkg/net/http/httputil](https://golang.org/pkg/net/http/httputil)
- [https://golang.org/pkg/net/http](https://golang.org/pkg/net/http)
- [https://golang.org/pkg/net/rpc/jsonrpc](https://golang.org/pkg/net/rpc/jsonrpc)
- [https://golang.org/pkg/net/rpc](https://golang.org/pkg/net/rpc)
- [https://golang.org/pkg/net/url](https://golang.org/pkg/net/url)
- [https://golang.org/pkg/net](https://golang.org/pkg/net)
- [https://golang.org/pkg/os/signal](https://golang.org/pkg/os/signal)
- [https://golang.org/pkg/os](https://golang.org/pkg/os)
- [https://golang.org/pkg/path/filepath](https://golang.org/pkg/path/filepath)
- [https://golang.org/pkg/path](https://golang.org/pkg/path)
- [https://golang.org/pkg/reflect](https://golang.org/pkg/reflect)
- [https://golang.org/pkg/regexp/syntax](https://golang.org/pkg/regexp/syntax)
- [https://golang.org/pkg/regexp](https://golang.org/pkg/regexp)
- [https://golang.org/pkg/runtime](https://golang.org/pkg/runtime)
- [https://golang.org/pkg/sort](https://golang.org/pkg/sort)
- [https://golang.org/pkg/strconv](https://golang.org/pkg/strconv)
- [https://golang.org/pkg/strings](https://golang.org/pkg/strings)
- [https://golang.org/pkg/sync/atomic](https://golang.org/pkg/sync/atomic)
- [https://golang.org/pkg/sync](https://golang.org/pkg/sync)
- [https://golang.org/pkg/testing](https://golang.org/pkg/testing)
- [https://golang.org/pkg/time](https://golang.org/pkg/time)
- [https://golang.org/pkg/unicode/utf8](https://golang.org/pkg/unicode/utf8)
- [https://golang.org/pkg/unicode](https://golang.org/pkg/unicode)
- [https://golang.org/pkg](https://golang.org/pkg)

Third party:

- [https://github.com/alecthomas/kingpin](https://github.com/alecthomas/kingpin)
- [https://github.com/facebookgo/flagenv](https://github.com/facebookgo/flagenv)
- [https://github.com/go-kit/kit](https://github.com/go-kit/kit)
- [https://github.com/jinzhu/gorm](https://github.com/jinzhu/gorm)
- [https://github.com/jmoiron/sqlx](https://github.com/jmoiron/sqlx)

## Reference

- [https://golang.org/ref/mem](https://golang.org/ref/mem)
- [https://golang.org/ref/spec](https://golang.org/ref/spec)

## Talks

- [https://talks.golang.org/2011/lex.slide](https://talks.golang.org/2011/lex.slide)
- [https://talks.golang.org/2012/10things.slide](https://talks.golang.org/2012/10things.slide)
- [https://talks.golang.org/2012/chat.slide](https://talks.golang.org/2012/chat.slide)
- [https://talks.golang.org/2012/go-docs.slide](https://talks.golang.org/2012/go-docs.slide)
- [https://talks.golang.org/2012/go1.slide](https://talks.golang.org/2012/go1.slide)
- [https://talks.golang.org/2012/goforc.slide](https://talks.golang.org/2012/goforc.slide)
- [https://talks.golang.org/2012/insidepresent.slide](https://talks.golang.org/2012/insidepresent.slide)
- [https://talks.golang.org/2012/simple.slide](https://talks.golang.org/2012/simple.slide)
- [https://talks.golang.org/2012/splash.article](https://talks.golang.org/2012/splash.article)
- [https://talks.golang.org/2012/splash.slide](https://talks.golang.org/2012/splash.slide)
- [https://talks.golang.org/2012/tutorial.slide](https://talks.golang.org/2012/tutorial.slide)
- [https://talks.golang.org/2012/waza.slide](https://talks.golang.org/2012/waza.slide)
- [https://talks.golang.org/2012/zen.slide](https://talks.golang.org/2012/zen.slide)
- [https://talks.golang.org/2013/advconc.slide](https://talks.golang.org/2013/advconc.slide)
- [https://talks.golang.org/2013/bestpractices.slide](https://talks.golang.org/2013/bestpractices.slide)
- [https://talks.golang.org/2013/distsys.slide](https://talks.golang.org/2013/distsys.slide)
- [https://talks.golang.org/2013/go-sreops.slide](https://talks.golang.org/2013/go-sreops.slide)
- [https://talks.golang.org/2013/go4python.slide](https://talks.golang.org/2013/go4python.slide)
- [https://talks.golang.org/2014/c2go.slide](https://talks.golang.org/2014/c2go.slide)
- [https://talks.golang.org/2014/compiling.slide](https://talks.golang.org/2014/compiling.slide)
- [https://talks.golang.org/2014/go4gophers.slide](https://talks.golang.org/2014/go4gophers.slide)
- [https://talks.golang.org/2014/gocon-tokyo.slide](https://talks.golang.org/2014/gocon-tokyo.slide)
- [https://talks.golang.org/2014/gotham-context.slide](https://talks.golang.org/2014/gotham-context.slide)
- [https://talks.golang.org/2014/hammers.slide](https://talks.golang.org/2014/hammers.slide)
- [https://talks.golang.org/2014/hellogophers.slide](https://talks.golang.org/2014/hellogophers.slide)
- [https://talks.golang.org/2014/names.slide](https://talks.golang.org/2014/names.slide)
- [https://talks.golang.org/2014/organizeio.slide](https://talks.golang.org/2014/organizeio.slide)
- [https://talks.golang.org/2014/playground.slide](https://talks.golang.org/2014/playground.slide)
- [https://talks.golang.org/2014/readability.slide](https://talks.golang.org/2014/readability.slide)
- [https://talks.golang.org/2014/research.slide](https://talks.golang.org/2014/research.slide)
- [https://talks.golang.org/2014/research2.slide](https://talks.golang.org/2014/research2.slide)
- [https://talks.golang.org/2014/static-analysis.slide](https://talks.golang.org/2014/static-analysis.slide)
- [https://talks.golang.org/2014/taste.slide](https://talks.golang.org/2014/taste.slide)
- [https://talks.golang.org/2014/testing.slide](https://talks.golang.org/2014/testing.slide)
- [https://talks.golang.org/2015/dynamic-tools.slide](https://talks.golang.org/2015/dynamic-tools.slide)
- [https://talks.golang.org/2015/go-for-java-programmers.slide](https://talks.golang.org/2015/go-for-java-programmers.slide)
- [https://talks.golang.org/2015/go-gc.pdf](https://talks.golang.org/2015/go-gc.pdf)
- [https://talks.golang.org/2015/gofmt-en.slide](https://talks.golang.org/2015/gofmt-en.slide)
- [https://talks.golang.org/2015/gogo.slide](https://talks.golang.org/2015/gogo.slide)
- [https://talks.golang.org/2015/gophercon-goevolution.slide](https://talks.golang.org/2015/gophercon-goevolution.slide)
- [https://talks.golang.org/2015/gotham-grpc.slide](https://talks.golang.org/2015/gotham-grpc.slide)
- [https://talks.golang.org/2015/how-go-was-made.slide](https://talks.golang.org/2015/how-go-was-made.slide)
- [https://talks.golang.org/2015/json.slide](https://talks.golang.org/2015/json.slide)
- [https://talks.golang.org/2015/simplicity-is-complicated.slide](https://talks.golang.org/2015/simplicity-is-complicated.slide)
- [https://talks.golang.org/2015/tricks.slide](https://talks.golang.org/2015/tricks.slide)
- [https://talks.golang.org](https://talks.golang.org)

## Tips

- [https://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang](https://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang)
- [https://medium.com/@Jarema./golang-slice-append-gotcha-e9020ff37374](https://medium.com/@Jarema./golang-slice-append-gotcha-e9020ff37374)

## Tools

- [https://github.com/alecthomas/gometalinter](https://github.com/alecthomas/gometalinter)
- [https://github.com/derekparker/delve](https://github.com/derekparker/delve)
- [https://github.com/fatih/vim-go](https://github.com/fatih/vim-go)
- [https://github.com/github/gitignore](https://github.com/github/gitignore)
- [https://github.com/golang/lint](https://github.com/golang/lint)
- [https://github.com/kardianos/govendor](https://github.com/kardianos/govendor)
- [https://github.com/mailgun/godebug](https://github.com/mailgun/godebug)
- [https://github.com/motemen/gore](https://github.com/motemen/gore)
- [https://github.com/nsf/gocode](https://github.com/nsf/gocode)
- [https://github.com/rogpeppe/godef](https://github.com/rogpeppe/godef)
- [https://github.com/zmb3/gogetdoc](https://github.com/zmb3/gogetdoc)
- [https://godoc.org/golang.org/x/tools/cmd/goimports](https://godoc.org/golang.org/x/tools/cmd/goimports)
- [https://godoc.org/golang.org/x/tools/cmd/gomvpkg](https://godoc.org/golang.org/x/tools/cmd/gomvpkg)
- [https://godoc.org/golang.org/x/tools/cmd/gorename](https://godoc.org/golang.org/x/tools/cmd/gorename)
- [https://godoc.org/golang.org/x/tools/cmd/present](https://godoc.org/golang.org/x/tools/cmd/present)
- [https://godoc.org/golang.org/x/tools/cmd/stringer](https://godoc.org/golang.org/x/tools/cmd/stringer)
- [https://godoc.org/golang.org/x/tools/cmd](https://godoc.org/golang.org/x/tools/cmd)

## Tracks

New Mac environment:

- Install Homebrew: [https://brew.sh](https://brew.sh)
- Install Go: `brew install go`
- Configure GOPATH: `export GOPATH=~/Developer/go` (you can symlink ~/Developer/go if needed)
- Configure PATH: `export PATH=$PATH:~/Developer/go/bin`
- Install goimports: `go get golang.org/x/tools/cmd/goimports`
- Install gometalinter: `go get github.com/alecthomas/gometalinter && gometalinter --install`
- [Configure your editor](https://github.com/golang/go/wiki/IDEsAndTextEditorPlugins)
- Useful alias: `alias cdd=cd ~/Developer`
- Useful alias: `alias cdg=cd ~/Developer/go`
- Useful alias: `alias cds=cd ~/Developer/go/src`

Sections for little or no experience:

- Introduction
- Reference
- Documentation
- Libraries
- Tools
- Community

Sections for some experience:

- Articles
- Tips
- Videos
- Talks
- Wiki

## Videos

- [A Simple Programming Environment](https://vimeo.com/53221558)
- [Advanced Go Concurrency Patterns](https://youtu.be/QDDwwePbDtw)
- [Cancellation, Context, And Plumbing](https://vimeo.com/115309491)
- [Code That Grows With Grace](https://vimeo.com/53221560)
- [Concurrency Is Not Parallelism](https://youtu.be/cN_DpYBzKso)
- [Dynamic Tools](https://www.youtube.com/watch?v=a9xrxRsIbSU)
- [GRPC](https://www.youtube.com/watch?v=vTIyz2QfExc)
- [Go Concurrency Patterns](https://youtu.be/f6kdp27TYZs)
- [Go For Gophers](https://www.youtube.com/watch?v=dKGmK_Z1Zl0)
- [Go From C To Go](https://www.youtube.com/watch?v=QIE5nV5fDwA)
- [Go Proverbs](https://youtu.be/PAAkCSZUG1c)
- [Go for Java Programmers](https://www.youtube.com/watch?v=_c_tQ6_3cCg)
- [Go for Pythonistas](https://www.youtube.com/watch?v=elu0VpLzJL8)
- [GopherCon 2015](https://www.youtube.com/playlist?list=PL2ntRZ1ySWBf-_z-gHCOR2N156Nw930Hm)
- [GopherCon 2016](https://www.youtube.com/playlist?list=PL2ntRZ1ySWBdliXelGAItjzTMxy2WQh0P)
- [Hello, Gophers](https://www.youtube.com/watch?v=VoS7DsT1rdM)
- [How Go Was Made](https://www.youtube.com/watch?v=0ht89TxZZnk)
- [Lexical Scanning In Go](https://youtu.be/HxaD_trXwRE)
- [Public Static Void](https://youtu.be/5kj5ApnhPAE)
- [Solving The Latency Problem](https://youtu.be/aiv1JOfMjm0)
- [Static Analysis Tools](https://vimeo.com/114736889)
- [Stupid Gopher Tricks](https://www.youtube.com/watch?v=UECh7X07m6E)
- [Testing Techniques](https://www.youtube.com/watch?v=ndmB0bj7eyw)
- [The Evolution of Go](https://www.youtube.com/watch?v=0ReKdcpNyQg)

## Wiki

- [https://github.com/golang/go/wiki/Articles](https://github.com/golang/go/wiki/Articles)
- [https://github.com/golang/go/wiki/Blogs](https://github.com/golang/go/wiki/Blogs)
- [https://github.com/golang/go/wiki/Books](https://github.com/golang/go/wiki/Books)
- [https://github.com/golang/go/wiki/CodeReviewComments](https://github.com/golang/go/wiki/CodeReviewComments)
- [https://github.com/golang/go/wiki/CodeTools](https://github.com/golang/go/wiki/CodeTools)
- [https://github.com/golang/go/wiki/Conferences](https://github.com/golang/go/wiki/Conferences)
- [https://github.com/golang/go/wiki/Errors](https://github.com/golang/go/wiki/Errors)
- [https://github.com/golang/go/wiki/GOPATH](https://github.com/golang/go/wiki/GOPATH)
- [https://github.com/golang/go/wiki/GoTalks](https://github.com/golang/go/wiki/GoTalks)
- [https://github.com/golang/go/wiki/GoUserGroups](https://github.com/golang/go/wiki/GoUserGroups)
- [https://github.com/golang/go/wiki/Gopher](https://github.com/golang/go/wiki/Gopher)
- [https://github.com/golang/go/wiki/HowToAsk](https://github.com/golang/go/wiki/HowToAsk)
- [https://github.com/golang/go/wiki/IDEsAndTextEditorPlugins](https://github.com/golang/go/wiki/IDEsAndTextEditorPlugins)
- [https://github.com/golang/go/wiki/LearnConcurrency](https://github.com/golang/go/wiki/LearnConcurrency)
- [https://github.com/golang/go/wiki/LearnServerProgramming](https://github.com/golang/go/wiki/LearnServerProgramming)
- [https://github.com/golang/go/wiki/Learn](https://github.com/golang/go/wiki/Learn)
- [https://github.com/golang/go/wiki/PackageManagementTools](https://github.com/golang/go/wiki/PackageManagementTools)
- [https://github.com/golang/go/wiki/PackagePublishing](https://github.com/golang/go/wiki/PackagePublishing)
- [https://github.com/golang/go/wiki/Podcasts](https://github.com/golang/go/wiki/Podcasts)
- [https://github.com/golang/go/wiki/Projects](https://github.com/golang/go/wiki/Projects)
- [https://github.com/golang/go/wiki/Screencasts](https://github.com/golang/go/wiki/Screencasts)
- [https://github.com/golang/go/wiki/SliceTricks](https://github.com/golang/go/wiki/SliceTricks)
- [https://github.com/golang/go/wiki/TableDrivenTests](https://github.com/golang/go/wiki/TableDrivenTests)
- [https://github.com/golang/go/wiki/Training](https://github.com/golang/go/wiki/Training)
- [https://github.com/golang/go/wiki/cgo](https://github.com/golang/go/wiki/cgo)
- [https://github.com/golang/go/wiki](https://github.com/golang/go/wiki)
