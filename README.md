# awesome_ruby_testing

Environment Management

rbenv - Use rbenv to pick a Ruby version for your application and guarantee that your development environment matches production.

RVM - RVM is a command-line tool which allows you to easily install, manage, and work with multiple ruby environments from interpreters to sets of gems.

Pik - Multi-Ruby Manager for Windows.

HTTP Clients and tools

Http Client - Gives something like the functionality of libwww-perl (LWP) in Ruby.

RESTClient - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions.

Package Management

Bundler - Manage your application's gem dependencies with less pain.

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

Mobile test automation

Calabash - Calabash enables you to write and execute automated acceptance tests on mobile apps. It's cross-platform, supporting Android and iOS native apps.
appium - An open source test automation framework for use with native, hybrid and mobile web apps. It drives iOS and Android apps using the WebDriver protocol.
Appium Desktop - Appium Desktop is an open source app for Mac, Windows, and Linux which gives you the power of the Appium automation server in a beautiful and flexible UI.
