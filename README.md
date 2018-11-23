# ReleaseTasks

Attempt to standardize release tasks and slightly nicer error messages when 
using confex to resolve production env var resolution ala the 12 factor app

Basic stuff - resolves env vars and provides some helpers for runtime seeding.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `release_tasks` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:release_tasks, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/release_tasks](https://hexdocs.pm/release_tasks).

