## Using blocks

All Scratch code blocks should be created as blocks code sections and have a max 64x64 pixel image of the sprite / stage they should be added too.

![scratch sprite](images/sprite.png)

```blocks3
when green flag clicked
move (10) steps
```

To highlight a block (or section of blocks) you should use a `+`.

![scratch sprite](images/sprite.png)

```blocks
when green flag clicked
move (10) steps
+ say [hi] for (2) seconds
```

![scratch sprite](images/sprite.png)

```blocks
when green flag clicked
+ repeat (10)
move (10) steps
say [hi] for (2) seconds
end
```

![scratch sprite](images/sprite.png)

```blocks
when green flag clicked
repeat (10)
move (10) steps
say [hi] for (2) seconds
+turn cw (90) degrees
+start sound [music v]
end
```

To note that a block should be removed you should use a `-`.

![scratch sprite](images/sprite.png)

```blocks
when green flag clicked
repeat (10)
move (10) steps
say [hi] for (2) seconds
turn cw (90) degrees
-start sound [music v]
end
```
