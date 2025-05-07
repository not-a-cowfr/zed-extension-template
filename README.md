<h1><a href="https://zed.dev/">Zed</a> extension template</h1>

- To make a theme extension:
  - Create json schema in [themes](./themes) directory
  - Edit schema version variable in [extension.toml](./extension.toml)
- To make a regular extension:
  - Edit [cargo.toml](./cargo.toml)
  - Edit [src/lib.rs](./src/lib.rs)
- To make a language extension:
  - Create schema files in the [languages](./languages) directory
  - Edit [config.toml](./config.toml)
- To make a snippets extension:
  - Create [snippets json](./snippets/snippets.json) file
  - Edit snippets variable in [extension.toml](./extension.toml)

<details><summary>Make sure to remove and files and code that dont ahve anything to do with your extension type</summary>

Extension specific things:
- theme:
  - themes/
  - schema_version var in exntension.toml
- regular:
  - src/
  - cargo.toml
  - cargo.lock
  - .gitignore, since it currently is only for target/
- language:
  - languages/
  - config.toml
- snippets:
  - snippets/
  - snippets var in extension.toml

</details>

And dont forget, if you wish to use a different license, change it! This repository uses the unlicense which may not be what you want

> [!IMPORTANT]
> The docs are your best friend! Please read them at https://zed.dev/docs/extensions/developing-extensions
> Additionally, for each individual extension type, I've linked more resources in their respective README.md
