# Todo

Ref:
http://geoffreylessel.com/2016/from-zero-to-ecto-in-10-minutes/

Simple app demonstrating using Ecto in a simple Elixir project (no phoenix)

- mix deps.get
- mix compile
- mix help
- mix ecto.gen.repo
- mix ecto.create
- mix ecto.gen.migration create_items
- mix ecto.migrate
- 
- iex -S mix
- alias Todo.Repo
- alias Todo.Item
- Repo.all Item
- Repo.insert %Item{title: "Talk at fullstack"}


## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `todo` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:todo, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/todo](https://hexdocs.pm/todo).

