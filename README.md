**`👋🏻` Hey, I'm Susie\~**

```rust
struct Person {
  name: &'static str,
  pronouns: Vec<&'static str>,
  interests: Vec<&'static str>,
  languages: Vec<&'static str>,
}

let susie = Person {
  name: "Susie",
  pronouns: vec!["she", "her"],
  interests: vec!["Data Science", "AI"],
  languages: vec!["Rust", "Python"],
};
```
