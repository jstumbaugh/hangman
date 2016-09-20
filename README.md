# Hangman

Jason Stumbaugh's submission for the Assignment 2b: Hangman
SMU ID: 39849346
CSE 5345: Advanced Application Programming
September 19th, 2016

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `hangman` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:hangman, "~> 0.1.0"}]
    end
    ```

  2. Ensure `hangman` is started before your application:

    ```elixir
    def application do
      [applications: [:hangman]]
    end
    ```

