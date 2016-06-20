# RSpecRequestGen

Hex package that calls an API for a supplied URL and generates a Ruby RSpec
request spec matching on the response

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add spec_request_gen to your list of dependencies in `mix.exs`:

        def deps do
          [{:spec_request_gen, "~> 0.0.1"}]
        end

  2. Ensure spec_request_gen is started before your application:

        def application do
          [applications: [:spec_request_gen]]
        end

