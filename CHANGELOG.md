1.0.4 / 2016-06-18
==================

  * fix issue #6; runtime facts unique to each run()

1.0.3 / 2016-06-15
==================

  * fix issue #5; dependency error babel-core/register

1.0.0 / 2016-05-01
==================

  * api stable; releasing 1.0
  * engine.run() now returns triggered events

1.0.0-beta10 / 2016-04-16
==================

  * Completed the 'fact-dependecy' advanced example
  * Updated addFact and addRule engine methods to return 'this' for easy chaining

1.0.0-beta9 / 2016-04-11
==================

  * Completed the 'basic' example
  * [BREAKING CHANGE] update engine.on('success') and engine.on('failure') to pass the current almanac instance as the second argument, rather than the engine
