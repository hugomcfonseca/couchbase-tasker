# couchbase-tasker

`couchbase-tasker` is an application, developed in Go, that contains a library implementing some unimplemented endpoints from Couchbase client and a HTTP client providing some helpful use cases when you want to use Couchbase API.

Currently, I am working to provide this use cases:

* Initialization of Couchbase cluster
* Modification of Couchbase initial parameters
* Creation of buckets
* Deleting of buckets

## Getting Started

Provided two methods to help you run `couchbase-tasks`: **Standalone** is the usual way to run any Go application, you just need to setup your Go environment, get dependencies, build it and run as normal binary file; and **Docker** is the containerized version of this tasker, that will run in the top of a Docker container and you can use it as an ephemeral container, by executing your tasks and remove container after exit, or run the container permanently and execute all your tasks into the container.

### Standalone

Here I will give the instructions about `git clone`, `go get` and `go build` this client and start using it.

### Docker

Here I will give the instructions about `docker pull`, `docker build` and `docker run` the container.

### Use cases

...

## API

...Couchbase API...

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details

## Supported versions

## Contributing

Contribution, in any kind of way, is highly welcome! 
It doesn't matter if you are not able to write code.
Creating issues or holding talks and help other people to use [couchbase-tasker](https://github.com/hugomcfonseca/couchbase-tasker) is contribution, too!
A few examples:

* Correct typos in the README / documentation
* Reporting bugs
* Implement a new feature, task or endpoint

If you are new to pull requests, checkout [Collaborating on projects using issues and pull requests / Creating a pull request](https://help.github.com/articles/creating-a-pull-request/).
If you've found a bug, a typo, have a question or a want to request new feature, please [report it as a GitHub issue](https://github.com/hugomcfonseca/couchbase-tasker/issues).
