# Shuttle.Core.Json

Json.Net implementation of the `ISerializer` interface.

## Usage

```
PM> Install-Package Shuttle.Core.Json
```

``` c#
var serializer = JsonSerializer.Default();
````

You can also specify `JsonSerializerSettings` when using the constructor to create the `JsonSerializer`:

``` c#
var serializer = new JsonSerializer(new JsonSerializerSettings());
````

The serializer will register itself when using [Shuttle.Core container bootstrapping](http://shuttle.github.io/shuttle-core/overview-container/#bootstrapping).
