Today I Learnt
===

1. [Primitive Types](https://hexdocs.pm/ecto/Ecto.Schema.html)
- [jsfuck](http://www.jsfuck.com/)
- [ook](https://www.splitbrain.org/services/ook)
- [elxir postgres practice](http://www.glydergun.com/diving-into-ecto/)
- the power of xargs, -> xargs -p -L 1 mix ecto.gen.migration < migrations
- [Foreign keys can be null](http://searchoracle.techtarget.com/answer/What-is-a-primary-key-Composite-PK-Foreign-key-Tuple)
- make multiple files with -> touch {x,y].txt
- [check browser support](https://caniuse.com/)
- [naive_datetime in Ecto](https://github.com/elixir-ecto/ecto/issues/1466)
- Redis is a in-memory data structure store -> makes lookups fast
- [Redis strings, hashes, sets and sorted sets](https://trello.com/c/chaFqznO)
- Changing Logger config level to reduce debug output [Read More](https://stackoverflow.com/questions/30297825/disable-elixir-ecto-debug-output)
- How to convert big to little endian[SigFox](https://digmat.freshdesk.com/support/solutions/articles/16000061215-decoding-the-oyster-sigfox-payload-examples)
- BigInteger can chain arithmetic, and very FP [GitHub](https://github.com/peterolson/BigInteger.js)
- Today I learn about docker [APIs](https://hub.docker.com/explore/)
- Knex Query Builder [Docs](http://knexjs.org/#Builder)
- HTTP Status Codes [Cheatsheet](https://httpstatuses.com/)
- [Airbnb Style Guide](https://github.com/airbnb/javascript#variables) - great javascript style guide
- [Async /Await](https://medium.com/@bluepnume/learn-about-promises-before-you-start-using-async-await-eb148164a9c8) - finally learnt async/await proper syntax use. Thanks Tom!
- [x-clip](https://askubuntu.com/questions/383462/unable-to-paste-with-xclip-outside-of-terminal) - Using xclip to paste into ubuntu clipboard
- Ubuntu CLI commands - `ctr-a/e` (move start/end), `ctr-u/k` (delete start/end) [Read](https://trello.com/c/5d7msXVC)
- Rediscovered the beauty of Router.route('/').get(...).post(...) [API](https://expressjs.com/en/guide/routing.html)
- `git checkout .` removes all unstaged tracked files
- `git stash apply stash@{x}` allows you to apply changes repeatedly
- Deployed Docker and docker-compose successfully! Thanks to [this article](https://medium.com/@nickpeleh/dockerizing-a-node-js-web-app-with-redis-and-postgresql-60ddc697b44)
- [ARIA] is for Accessibility Rich Internet Applications (https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-label_attribute)
- always preload before any operation in a changeset
- An Elixir value always returns the value defined at the time of its definition
- learnt some basic [psql](https://trello.com/c/3ZPR8Srg)
- successfully migrated and seeded a Postgres DB using Knex
- Learn how to compile top level .scss into .css [Thanks SO!](https://stackoverflow.com/questions/34896279/how-to-compile-scss-to-css-with-node-sass)
- learnt how to [pass parameters into script tags](https://stackoverflow.com/questions/16098397/pass-variables-to-javascript-in-expressjs)
#### End
- `ctr`+`alt`+`f1` switches you to a virtual terminal, [READ THIS](https://askubuntu.com/questions/474932/help-i-broke-ubuntu-by-uninstalling-compiz) for ubuntu OS breaks
- [Express generator steps](https://expressjs.com/en/starter/generator.html)
- [node_redis](https://github.com/NodeRedis/node_redis)
- [Ecto.Query.API.left_in_right is **really** useful](https://hexdocs.pm/ecto/Ecto.Query.API.html#in/2)
- `distinct: foo.bar` to find unique entries [Ecto.Query](https://hexdocs.pm/ecto/Ecto.Query.html#content)
- [An ExUnit beginner's cheatsheet](http://blog.lucidsimple.com/2016/01/31/exunit-cheat-sheet.html)
Phoenix form helpers are at [Phoenix.HTML](https://hexdocs.pm/phoenix_html/Phoenix.HTML.Form.html)
- use `sudo syscallbypid.d` to trace for syscalls [Read More](https://apple.stackexchange.com/questions/178281/how-to-investigate-high-kernel-task-memory-usage)
- Made a terrible mistake regarding [circular dependencies](https://www.reddit.com/r/elixir/comments/6zvsxd/avoiding_circular_dependencies_in_a_phoenix/?st=j99b3s3b&sh=ae0560b3) - and I'm still trying to reconcile it
- Learnt how to migrate/rollback knex one at a time - by migrating one at a time(duh\!)
- Learnt about [emmets](https://emmet.io/) - a fast way to write html
- Learnt that constructor functions cannot implement ES6 arrow functions
- Learnt how to use Ecto [cast_embed](https://hexdocs.pm/ecto/Ecto.Changeset.html#cast_embed/3), [add_error](https://hexdocs.pm/ecto/Ecto.Changeset.html#add_error) and that Ex's [reduce_while](https://hexdocs.pm/elixir/Enum.html#reduce_while/3) can have two heads
- Compilers, interpreters, optimisations in [Javascript](https://hacks.mozilla.org/2017/02/a-crash-course-in-just-in-time-jit-compilers/)
- Learnt about [spread syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_operator) in JS
- Dos and donts of Javascript [mutation](https://medium.com/@fknussel/arrays-objects-and-mutations-6b23348b54aa)
- Learnt about Ecto.Changeset [fields](https://hexdocs.pm/ecto/Ecto.Changeset.html#module-the-ecto-changeset-struct)
- Learnt about tranpose (`ctr+T`) to swap two letters
- How to install [ngrok](https://gist.github.com/wosephjeber/aa174fb851dfe87e644e)
- [Ecto.multi](https://hexdocs.pm/ecto/Ecto.Multi.html#content) is Ecto's version of a database transaction [Read More](https://medium.com/heresy-dev/a-brief-guide-to-ecto-multi-9c8ea0c729f0)
- Reminder on [mutability of javascript objects](https://wecodetheweb.com/2016/02/12/immutable-javascript-using-es6-and-beyond/)

- [action fallback controllers](https://swanros.com/2017/03/04/action-fallback-contexts-phoenix1-3-tiny-controllers/) make phoenix controllers really, really lean
- found [another TIL](https://til.hashrocket.com/elixir) done by the team at hashrocket\!
- Best ever [article](https://medium.com/@gajus/using-dataloader-to-batch-requests-c345f4b23433) for understanding the N+1 problem in GraphQL and dataloading
- Learnt basic graphQL using [absinthe](https://hexdocs.pm/absinthe/Absinthe.html)
- Python: use "\" to use multi-line function expressions and ";\" to mark the end of a command and continuing on to a new line
