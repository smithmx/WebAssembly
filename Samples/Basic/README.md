# Basic Sample

Compile the [.NET](https://www.microsoft.com/net) project by running:

```shell
$ dotnet build
```

It will run a post build step that packages the artifacts needed to run the solution.

Then you need to start a Web server. This sample comes with one setup that requires [NodeJS](https://www.nodejs.org) to be installed.
Once you have NodeJS installed, run the following from your shell:

```shell
$ yarn
$ yarn run start
```

Once this is running, you simply navigate to [http://localhost:8080/index.html](http://localhost:8080/index.html).