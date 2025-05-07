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

and make sure to remove and files and code that dont ahve anything to do with your extension type

> [!IMPORTANT]
> The docs are your best friend! Please read them at https://zed.dev/docs/extensions/developing-extensions
> Additionally, for each individual extension type, I've linked more resources in their respective README.md
