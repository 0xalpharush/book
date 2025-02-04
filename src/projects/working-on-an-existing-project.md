## Working on an Existing Project

Foundry makes developing with existing projects have no overhead.

For this example, we will use [PaulRBerg][paul]'s [`foundry-template`][template].

If you download an existing project that uses Foundry, it is really easy to get going.

First, clone the project and run [`forge install`][install] inside the project directory.

```sh
$ git clone https://github.com/PaulRBerg/foundry-template
$ cd foundry-template 
$ forge install
```

We run [`forge install`][install] to install the submodule dependencies that are in the project.

To build, use [`forge build`][build]:

```sh
{{#include ../output/foundry-template/forge-build:all}}
```

And to test, use [`forge test`][test]:

```sh
{{#include ../output/foundry-template/forge-test:all}}
```

[paul]: https://github.com/PaulRBerg
[template]: https://github.com/PaulRBerg/foundry-template
[install]: ../reference/forge/forge-install.md
[build]: ../reference/forge/forge-build.md
[test]: ../reference/forge/forge-test.md
