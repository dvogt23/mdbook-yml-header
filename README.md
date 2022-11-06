# mdBook-yml-header

A preprocessor for [mdbook](https://github.com/rust-lang-nursery/mdBook) to remove yml-header ([front-matter](https://help.obsidian.md/Advanced+topics/YAML+front+matter)) within `---` at the top of
a `.md` file.

## Installation

If you want to use only this preprocessor, install the tool:

```
cargo install mdbook-yml-header
```

Then add this to your `book.toml`

```toml
[preprocessor.yml-header]
```

## License

MPL. See [LICENSE](LICENSE).  
Copyright (c) 2022 Dmitrij Vogt <divogt@vogt.dev>
