You don't really need docs for this (and I dont think three even is any)

Theres an example snippet in the [premade file](./language.json)

All you need to know is
- Name the file after the language you're making it for, just update the [extension.toml](../extension.toml) aswell
  - I actually dont know if this is required, but I haven't seen a snippets extension that doesn't do it so better safe than sorry

<sub>(still should find out though)</sub>
- To pass args into the snippet code just use `$<arg number>` or `${<arg number>:<arg name>}`
