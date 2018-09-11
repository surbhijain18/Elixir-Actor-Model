# Newproj1

RUNNING ON 2+ MACHINES:
STEPS:

ON ALL MACHINES RUN:
$ iex –name node@IPAddress –cookie chocolate -S mix

CONNECT TO OTHER MACHINE:
iex>Node.ping :”node2@IP”
iex>MainModule.list 			(Will list all connect nodes)
iex>Proj1.main(N,K)			    (run from your server machine)



**
######################################################
##Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `newproj1` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:newproj1, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/newproj1](https://hexdocs.pm/newproj1).
