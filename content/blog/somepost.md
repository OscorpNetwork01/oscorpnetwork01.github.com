+++
title = "The first post"
slug = "20250823-first-post"
date = "2025-08-23"
template = "page.html"

[extra]
mermaid = true
+++
# Paragrap
Hello! This is my first post!

## Some subheading
Let me try to show some C# code!

{% mermaid() %}

sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!

{% end %}

```csharp
public class HelloWorld {
    public static void Main() {
        Console.WriteLine("Hello, world!");
    }
}
```

How does it look?
> Not bad my man!