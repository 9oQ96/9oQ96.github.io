It's very easy to make some words **bold** and other words *italic* with Markdown.

You can even [link to Duckduckgo!](https://html.duckduckgo.com)

    inventory_items = {"health potion": 10, "cake of the cure": 5, "green elixir": 20, "strength sandwich": 25, "potion of stamina": 15, "soup of power": 30}
    
    health_hearts = 20
    
    health_hearts += inventory_items.pop("potion of stamina", 0)
    health_hearts += inventory_items.pop("soup of power", 0)
    health_hearts += inventory_items.pop("mystic leven loaf", 0)
    
    print("Health Heart Points: " + str(health_hearts))
    print("Inventory Items: " + str(inventory_items))

It's a bit of Python:

> pop() a key out of dict
> add the value to h_p
> (unless there's no corresponding val)

*Well, that was fun!*