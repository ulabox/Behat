1.1.3 / 2011-04-28
==================

  * JUnit formatter fix
  * Formatters basePath fix. Now formatters uses CWD as path trimmer
  * Relative paths locator bug fix
  * Show table argument header in HTML formatter

1.1.2 / 2011-04-27
==================

  * Fixed custom features path locator bug(issue #020)

1.1.1 / 2011-04-21
==================

  * Fixed paths finding routines
  * Totally refactored BehatCommand
  * Added rerun functionality (`--rerun`)
  * Ability to remove previously specified paths in `behat.yml`
  * Bugfixes and little tweaks

1.1.0 / 2011-04-04
==================

  * New configuration system with profiles and imports support
  * New event system
  * Environment parameters support
  * Named regex arguments support
  * Japanese translation for formatters
  * JUnit formatter bugfixes
  * HTML and Pretty formatters multiple arguments print bugfix
  * Step snippets (proposals) bugfixes
  * Updated vendor libraries

1.0.0 / 2011-03-08
==================

  * Changed XSD
  * Updated vendors

1.0.0RC6 / 2011-03-03
=====================

  * Cleaned command options
  * Added --init option
  * Multiple paths support in behat.yml
  * Application options refactoring

1.0.0RC5 / 2011-02-25
=====================

  * Windows support
  * Bundled features hooks optimizations

1.0.0RC4 / 2011-02-23
=====================

  * Pretty formatter tag printing fix
  * Custom formatter specification fix in `behat.yml`
  * Symfony components updated
  * Extension configuration manager (Symfony\Component\Config component)
  * Cleaning of `behat.yml` configurator (thanks to Symfony\Component\Config)
  * Additional formatter parameters support in `behat.yml`

1.0.0RC3 / 2011-02-18
=====================

  * Event dispatcher binding optimizations
  * Command API optimizations for easier overloading
  * Formatter path trimming bugfix
  * BehatExtension config merging support

1.0.0RC2 / 2011-02-15
=====================

  * Step printing option bugfix

1.0.0RC1 / 2011-02-15
=====================

  * Gherkin DSL parser is standalone project
  * Own Behat namespace for both Behat & Gherkin
  * Fully rewritten formatters (much cleaner & beautifull API)
  * Big refactoring of whole Behat code (clean code DRYing)
  * Config file is now handled by standart-driven DIC extension (cleaner `behat.yml`)
  * API documentation retouched
  * New `--strict` option
  * New `--no-multiline` option
  * Feature examples in your language with `--usage`
  * Available definitions listing with `--steps`
  * Definition i18n
  * Command refactoring (much cleaner API & actions)
  * Event system refactoring
  * 42 new languages with new Gherkin DSL parser

0.3.6 / 2010-12-07
==================

  * [Behat,Gherkin] Fixed French support includes (fr)

0.3.6 / 2010-12-06
==================

  * [Behat] Updated Symfony2 Components to latest PR4
  * [Gherkin] Added French support (fr)
  * [Gherkin] Added German support (de)
  * [Behat] Small bugfixes

0.3.5 / 2010-11-19
==================

  * [Behat] Refactored EnvironmentBuilder to allow Environment service definition overload

0.3.4 / 2010-11-18
==================

  * [Behat] Introduced environment builder
  * [Gherkin,Behat] id locale support

0.3.3 / 2010-11-07
==================

  * [Gherkin] Added ability to create Table & PyString nodes with hands (in your step to step calls for example)
  * [Gherkin] Added getRowsHash() method to TableNode, so now you can "rotate" given tables
  * [Gherkin] You now can add comments before language specification in your feature files

0.3.2 / 2010-11-06
==================

  * [Gherkin] Added ability to specify extended langs (en-US)
  * [Behat,Gherkin] Added pt-BR translation

0.3.1 / 2010-11-02
==================

  * [Behat] JUnit formatter
  * [Behat] Pretty & HTML formatter background hooks fix
  * [Behat] Other small fixes

0.3.0 / 2010-11-02
==================

  * [Behat] Refactored tags filter
  * [Behat] Added name filter
  * [Behat] Refactored hooks
  * [Behat] Added tagged/named hooks
  * [Behat] Customizable HTML formatter with w3c valid default markup
  * [Behat] Ability to specify out path for formatters
  * [Behat] Bunch of new options
  * [Behat] DIC optimisations

0.2.5 / 2010-10-22
==================

  * [Behat] Format manager introduced
  * [Behat] Formatters refactoring
  * [Behat] Optmized container parameters to support EverzetBehatBundle
  * [Behat] --no-color => --no-colors

0.2.4 / 2010-10-19
==================

  * [Behat] Autoguess of colors support
  * [Behat] Formatter setup bugfix (properl casing)

0.2.3 / 2010-10-19
==================

  * [Behat] Filters optimisations
  * [Behat] Changed Core Loaders with topic-specific (`StepDefinition\Loader\PHPLoader`,
    `Features\Loader\GherkinLoader`)
  * [Behat] Simplified TestCommand in prepare of Symfony2 BehatBundle
  * [Behat] Configuration file/path setting update (you can now create `behat.yml` inside `./config/behat.yml` & Behat
    will load it
  * [Behat] Updated Redundant & Ambiguous exceptions behavior

0.2.2 / 2010-10-10
==================

  * [Behat] Configuration file/path setting update

0.2.1 / 2010-10-10
==================

  * [PEAR] Fix path to phpbin on installation

0.2.0 / 2010-10-08
==================

  * [Behat] Brand new stateless testers, based on Visitor pattern
  * [Behat] Refactored event listeners & event names
  * [Behat] Refactored formatters to confirm with new stateless testers (statuses now sent as event parameters)
  * [Behat] Refactored ConsoleFormatter (and removed base formatter)
  * [Behat] Removed custom I18n classes & refactored Translator routines in flavor of Symfony\Component\Translation
  * [Behat] Added missed translation strings into XLIFF files
  * [Behat] Optimised multiline arguments (Node instances are sent to definitions instead of their plain representations)
  * [Behat] Support for Scenario Outline tokens replace in multiline arguments (tables & pystrings)
  * [Behat] Step arguments transformations (including table transformations)
  * [Behat] Colorize inline step arguments
  * [Behat] Optimized exit statuses of CLI
  * [Behat] Added ability to turn-off colors
  * [Behat] Added ability to translate formatters output with `--i18n` option
  * [Behat] Bunch of new core feature tests
  * [Gherkin] Parser now uses Symfony Dependency Injection to
  * [Gherkin] Refactored parser to be like AST (Nodes that supports Visitor pattern)
  * [Gherkin] Comments support
  * [Gherkin] Fixed PHPUnit warnings
  * [Behat,Gherkin] PEAR release script to support http://pear.everzet.com release model
  * [Behat,Gherkin] DIC naming refactoring
  * [Behat,Gherkin] Autoloader refactoring
  * [Behat,Gherkin] Removed Zend & Goutte depencies

0.1.5 / 2010-09-25
==================

  * Added ability to call other steps inside step definition
  * Added profiles
  * Refactored container creation routine
  * Single quotes support in step definitions
  * Added tests for hooks, profiles, inline steps

0.1.4 / 2010-09-16
==================

  * Refactored code
  * Removed logic from object constructors
  * Added Loader & Filter interfaces

0.1.3 / 2010-09-14
==================

  * Ability to specify arrays of paths/files for loaders
  * Event hooks and support for `support/hooks.php`
  * Formatters listens events with smallest priority
  * Don't try to load steps if `steps` folder doesn't exists
  * Bugfixes/refactoring

0.1.2 / 2010-09-10
==================

  * Added ability to read from `behat.yml` and `behat.xml`
  * Moved tags filter to separate object
  * Refactored injection controller
  * Optimized event names in event dispatcher
  * Other small fixes/refactorings

0.1.1 / 2010-09-09
==================

  * Added `--tags` option
  * Changed environment (world) routines
  * Added lots of core tests (writed in Behat itself)

0.1.0 / 2010-09-08
==================

  * Initial release
