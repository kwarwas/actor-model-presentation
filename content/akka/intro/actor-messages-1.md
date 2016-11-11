## Akka.NET - Messages

### In Akka.NET messages are **immutable**

    public class OrderMessage
    {
        public int Id { get; private set; }
        public string Name { get; private set; }

        public OrderMessage(int id, string name)
        {
            Id = id;
            Name = name;
        }
    }
