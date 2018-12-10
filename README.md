# elixir

```
"it's the future" -mr.robot
```

```
enter: iex
exit : control c control c
run : elixir hello_world.exs

in iex:
- h --> help, list of commands
    ex: h String.downcase
```

### WHY ELIXIR
* syntax based loosely on ruby, and cherry picked from other languages 
* industrial strength 
* future = everything is networked 
* can handle concurrency
* is fault tolerant
* developer friendly, nice tools, has decent error messages
* highly scalable, highly concurrent, extremely robust in fault tolerant systems,  

As a programming paradigm, concurrent computing is a form of modular programming, namely factoring an overall computation into subcomputations that may be executed concurrently.

###### What do i need to learn:
* Read, write elixir code
* Create and write recursive function
* Structure programs
* Call erlang code from elixir programs
* Import elixir and erlang dependencies and use in code
* Add own configuration into configuration files, and use in program
* Processes, execute functions within processes, send and receive messages b/w processes
* Write functional programs and thing functional way, by understanding pattern matching concepts
* OTP (framework and tools erlang uses to creating distributed and fault tolerant programming
* Functional programming
* Interactive mode REPL (read evaluate print loop)  {iex}

- Two types of files
    * .ex → compiled down to byte code and run on the erlang beam
    * .exs → scripting files, interpreted like ruby and python
- use snake case to name files
    * hello_world.exs
- comment with #
- functions are grouped in modules
- String interpolation
    * iex> name = "sean"
    * iex> "Hello #{name}"

    * iex> name = "Sean"
    * iex> "Hello " <> name

* Lists can include multiple types
* It’s faster to prepend instead of appending (time complexity is 0n) b/c similar to linked lists
* List concatenation == “++”
* iex> list = [3.15, :pie, "Apple"]

* iex> [“π”] ++ list

* iex> [1, 2] ++ [3, 4, 1]

* iex> ["foo", :bar, 42] -- [42, "bar"]
    ["foo", :bar]

* iex> IO.puts("Hello World!")
    * Hello World!
    * :ok


* IO module
    * :ok is an atom

* To find details about what functions a module has
    * String.downcase == man
    * String. {tab}
        * Shows all possibility you can put with string module
    * C = compile
        * c "./hello_world.exs"
* Compile a file in iex
* To configure iex
    * h IEx.configure
* Atom
    * A constant

#### BASIC TYPES
* Integers → unlimited size, can use _ separator (1_000_000 == 1000000)
* Octals, hexadecimals, binaries
* Floating points
* Exponents
* 3141.0e6
* Atoms
* Immutable strings
    * :hello
* Used as keys, to reference erlang functions, to reference functions within elixir


* Strings
    * “” == string
    * ‘’ == sequence of characters
    * Is_list == ‘hello’
    * Use byte_size
    * booleans

