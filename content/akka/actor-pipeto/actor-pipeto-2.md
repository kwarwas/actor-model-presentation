## Akka.NET - PipeTo

    var t = Task.Run(async () =>
    {
        var t1 = actorA.Ask("request", TimeSpan.FromSeconds(1));
        var t2 = actorB.Ask("another request", TimeSpan.FromSeconds(5));

        await Task.WhenAll(t1, t2);

        return new Result(t1.Result, t2.Result);
    });

    t.PipeTo(actorC, Self);

