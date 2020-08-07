It's very easy to make some words **bold** and other words *italic* with Markdown.

You can even [link to Duckduckgo!](https://html.duckduckgo.com)

    available_items = {"health potion": 10, "cake of the cure": 5, "green elixir": 20, "strength sandwich": 25, "stamina grains": 15, "power stew": 30}
    
    health_points = 20
    
    health_points += available_items.pop("stamina grains", 0)
    health_points += available_items.pop("power stew", 0)
    health_points += available_items.pop("mystic bread", 0)
    
    print("Health Points: " + str(health_points))
    print("Available Items: " + str(available_items))

It's a bit of Python:

> pop() a key out of dict
> add the value to h_p
> (unless there's no corresponding val)

*Well, that was fun!*