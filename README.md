# awesome_ruby_testing

Environment Management

chruby - Change your current Ruby. No shims, no crazy options or features, ~90 LOC.
fry - Simple ruby version manager for fish.
gem_home - A tool for changing your $GEM_HOME.
rbenv - Use rbenv to pick a Ruby version for your application and guarantee that your development environment matches production.
ruby-build - Compile and install Ruby.
ruby-install - Installs Ruby, JRuby, Rubinius, MagLev or MRuby.
RVM - RVM is a command-line tool which allows you to easily install, manage, and work with multiple ruby environments from interpreters to sets of gems.
Tokaido - Ruby, Rails, SQLite and Redis encapsulated in a single drag-and-drop OS X app, designed to make installing a working RoR environment easy for beginners.
RVM - Ruby Version Manager (RVM) is a unix command-line tool which allows you to easily install, manage, and work with multiple ruby environments from interpreters to sets of gems.
Pik - Multi-Ruby Manager for Windows.
rbenv - Use rbenv to pick a Ruby version for your application and guarantee that your development environment matches production.

HTTP Clients and tools

excon - Usable, fast, simple Ruby HTTP 1.1. It works great as a general HTTP(s) client and is particularly well suited to usage in API clients.
Faraday - an HTTP client lib that provides a common interface over many adapters (such as Net::HTTP) and embraces the concept of Rack middleware when processing the request/response cycle.
Device Detector - A precise and fast user agent parser and device detector, backed by the largest and most up-to-date user agent database.
Http Client - Gives something like the functionality of libwww-perl (LWP) in Ruby.
HTTP - The HTTP Gem: a simple Ruby DSL for making HTTP requests.
httparty - Makes http fun again!
Http-2 - Pure Ruby implementation of HTTP/2 protocol
Patron - Patron is a Ruby HTTP client library based on libcurl.
RESTClient - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions.
Savon - Savon is a SOAP client for the Ruby programming language.
Sawyer - Secret user agent of HTTP, built on top of Faraday.
Typhoeus - Typhoeus wraps libcurl in order to make fast and reliable requests.

Package Management

Gems
Bundler - Manage your application's gem dependencies with less pain.
RubyGems - Community's gem hosting service.
Packages and Applications
Berkshelf - A Chef Cookbook manager.
CocoaPods - The Objective-C dependency manager.
Foreman - Manage Procfile-based applications.
fpm - Effing package management! Build packages for multiple platforms (deb, rpm, etc) with great ease and sanity.
Linuxbrew - A fork of Homebrew for Linux.
Homebrew-cask - A CLI workflow for the administration of Mac applications distributed as binaries.
Homebrew - The missing package manager for OS X.
Traveling Ruby - Traveling Ruby lets you create self-contained Ruby app packages for Linux and OS X.

Mocking

ActiveMocker - Generate mocks from ActiveRecord models for unit tests that run fast because they don’t need to load Rails or a database.
TestXml - TestXml is a small extension for testing XML/HTML.
WebMock - Library for stubbing and setting expectations on HTTP requests.
vcr - Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests.

Test data

Fabrication - A simple and powerful object generation library.
factory_bot - A library for setting up Ruby objects as test data.
Fake Person - Uses some of the most popular given & surnames in the US & UK.
faker - A library for generating fake data such as names, addresses, and phone numbers.
ffaker - A faster Faker, generates dummy data, rewrite of faker.
Forgery - Easy and customizable generation of forged data.

Web UI test automation

libraries

Selenium WebDriver - This gem provides Ruby bindings for WebDriver.
API Taster - A quick and easy way to visually test your Rails application's API.
Watir - Web application testing in Ruby.
Watir-webdriver - The most elegant way to use WebDriver with ruby.
Poltergeist - Poltergeist is a driver for Capybara. It allows you to run your Capybara tests on a headless WebKit browser, provided by PhantomJS.
PhantomJS - is a headless WebKit scriptable with a JavaScript API. It has fast and native support for various web standards: DOM handling, CSS selector, JSON, Canvas, and SVG.
unobtainium - configuration driven wrapper for Selenium WebDriver and appium, with PhantomJS support.

frameworks

Capybara - Acceptance test framework for web applications.
Konacha - Test your Rails application's JavaScript with the mocha test framework and chai assertion library.
chemistrykit - Simple and opinionated web testing framework for Selenium WebDriver that follows convention over configuration and integrates with SauceLabs for cross-browser execution in the cloud.
howitzer - is a Ruby-based framework for acceptance testing. It was originally developed for testing web applications, but you can also use it for API testing and web service testing.The framework was built with modern patterns, techniques, and tools in automated testing.

page objects

page-object - Gem to implement PageObject pattern in watir-webdriver and selenium-webdriver.
watirsome - Awesome page objects with Watir.
widgeon - Yet another 'page objects for Capybara' gem with ability to create custom loadable elements akka 'widgets'
Site Prism - A Page Object Model DSL for Capybara

extensions

Selenium-Grid-Extras - Simplify the managment of the Selenium Grid Nodes and stabilize said nodes by cleaning up the test environment after the build has been completed
Mailosaur - Ruby client for email testing/automation via Mailosaur.
Machinist - Fixtures aren't fun. Machinist is.

Reporting

ReportPortal.io - Ruby Cucumber + RSpec powerfull results management and analytics for test automation reports. Powered with Machine Learning. Real-time integration and reports, visualization of trends and statistics, custom dashboards and widgets, gives you real visibility into the state of test automation. Integral part of CI/CD with TA and Continous Testing. Server-client application, can be used for any type of automated tests. Free and OpenSourced, GitHub link.

Useful libs

parallel_tests - Speedup Test::Unit + RSpec + Cucumber by running parallel on multiple CPUs (or cores). ParallelTests splits tests into even groups(by number of tests or runtime) and runs each group in a single process with its own database.
headless - Is the Ruby interface for Xvfb. It allows you to create a headless display straight from Ruby code, hiding some low-level action. It can also capture images and video from the virtual framebuffer.
watir-jquery - Watir-jquery gem allows you to use the jQuery syntax to find page elements and returns Watir-object type.
