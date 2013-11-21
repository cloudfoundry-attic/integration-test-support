integration-test-support
========================
Shared code base to help you write Cloud Foundry integration tests, which involves many CF components.

Submodule this repo in a directory like `/vendor` and then include a line like this:

`require_dir '../vendor/integration-test-support/support/**/*.rb'`

in your `spec_helper.rb` file

Example
========================
Please see an example test in 
[here](https://github.com/cloudfoundry/integration-test-support/blob/master/example/example_spec.rb) and [spec_helper](https://github.com/cloudfoundry/integration-test-support/blob/master/example/spec_helper.rb)
