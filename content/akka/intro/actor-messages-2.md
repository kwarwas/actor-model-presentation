## Akka.NET - Messages

### In Akka.NET messages are **immutable**

    public class OrderMessage
    {
        public int Id { get; }
        public string Name { get; }

        public OrderMessage(int id, string name)
        {
            Id = id;
            Name = name;
        }
    }

http://www.informit.com/articles/article.aspx?p=2416187
https://msdn.microsoft.com/en-us/magazine/dn802602.aspx
