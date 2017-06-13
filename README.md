# W.D.T. Definition

W.D.T. is an esoteric programming language that can be (theoretically) used for anything, but would be extremely impractical.
The name stands for W.eird D.ata T.ypes and means that instead of normal data types, it has weird replacements.

Take a look at this example:
```
@L1,2,3,4
2,4,6,8
3,6,9,c
4,8,c,10
}L|`|``
-|-|-|-
````

> _**NOTE**: some newlines are `\n` while others are `\r`_

That program prints
```
1|2|3|4
-|-|-|-
2|4|6|8
-|-|-|-
3|6|9|12
-|-|-|-
4|8|12|16
```

In the exmaple above, we can find three data types:
* **`csv`**: in W.D.T. , there are no `arrays` there are tables, csv tables.
* **`hexadecimal`**: **every** `number` is a complex hexadecimal number.
* **`pbrain string`**: you know how many programming languages have a simpler one that it can interpret, like `python` with it's [`lambda`](https://en.wikipedia.org/wiki/Lambda_calculus), well here we have [`pbrain`](https://esolangs.org/wiki/Pbrain) embedded, oh yeah, it can also be used as a normal `string`.

We can also find three operators:
* **`@`**: the `@` operator takes two arguments after it, the first being the _(single letter)_ name of the variable, the second being the variable's data.
* **`}`**: it takes one argument _(after)_ and outputs it.
* **`|`**: joins a `csv` into a pbrain or a psuedo 1d array.