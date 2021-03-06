# Rspec 

This is part of the rspec-2 codebase, which is in alpha release at the moment.
While you are welcome to track, fork, explore, etc, we're too early in the
process to start fielding pull requests and or issues from outside the core
development team, so please don't waste your time until this
notice changes.

This repo will be the source for the rspec-2.x gem, which will serve as a
meta-gem, much like the rails and merb gems. `gem install rspec` will also
install rspec-core, rspec-expectations and rspec-mocks, each of which can be
installed separately and actived in isolation with the `gem` command. Among
other benefits, this will allow you to use rspec-expectations, for example, in
Test::Unit::TestCase if you happen to like that style.

Conversely, if you like Rspec's approach to declaring example groups and
examples (`describe` and `it`) but prefer Test::Unit assertions and mocha, rr
or flexmock for mocking, you'll be able to do that without having to load the
components of rspec that you're not using.

## Install

    [sudo] gem install rspec --prerelease

#### Also see

* [http://github.com/rspec/rspec-dev](http://github.com/rspec/rspec-dev)
* [http://github.com/rspec/rspec-core](http://github.com/rspec/rspec-core)
* [http://github.com/rspec/rspec-expectations](http://github.com/rspec/rspec-expectations)
* [http://github.com/rspec/rspec-mocks](http://github.com/rspec/rspec-mocks)
