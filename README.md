# Pokemonland
Simple pokemon game made only with html and css

[DEMO](https://jsemalvarez.github.io/pokemonland/)

## Recursos 

[Creating a zigzag pattern with just CSS](https://dev.to/cchana/explained-creating-a-zigzag-pattern-with-just-css-13g1)


## CSS counter function

create a counter in the body selector
```

body{
    counter-reset: game;
}

```

increment the counter value
```

input:checked{
    counter-increment: game;
}

```
show the counter value
```

.score::after {
    content: counter(game);
}

```
