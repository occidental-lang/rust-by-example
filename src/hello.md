# Hello World

Ti es li code fontal del programma traditional Hello World.

```rust,editable
// Ti es un comenta, e es ignorat del compilator
// Tu posse provar li code per cliccar sur li buton "Run" quel trova se ta ->
// e si tu prefere usar li claviere, tu posse usar li acurtation "Ctrl + Enter"

// Ti-ci code es redactibil, tu posse hackar it si tu vole!
// Un sol clic al buton "Reset" va retornar te al code original ->

// Vi li function main
fn main() {
    // Instructiones (statements) ci es executet quande li binarie complilat es vocat

    // Printar textu al console
    println!("Salute munde!");
}
```

`println!` es un [*macro*][macros] quel printa textu al
console.

On posse generar un binarie con li compilator Rust: `rustc`.

```bash
$ rustc hello.rs
```

`rustc` va producter un binarie `hello` quel es executibil.

```bash
$ ./hello
Salute munde!
```

### Activitá

Clicca 'Run' in supra por vider li surtida expectat. Poy, adjunte un nov
linea con un duesim macro `println!` por que li surtida mey
monstrar:

```text
Salute munde!
I'm a Rustacean!
```

[macros]: macros.md
