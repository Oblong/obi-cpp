# obi-cpp

An [obi](https://github.com/Oblong/obi) template for basic C++ projects.

## Instructions

First, [install obi](https://github.com/Oblong/obi#install).

Then, install the template.  Be sure to pass the optional `[<name>]` argument
(`cpp`) or obi will complain.

``` bash
$ obi template install git@github.com:Oblong/obi-cpp cpp
```

Finally, create a new project, build it, and run the thing!

``` bash
$ obi new cpp helloworld
$ cd helloworld
$ obi go
```

See the `project.yaml` file in the generated project for adding new rooms and
customizing how your project is built and run.
