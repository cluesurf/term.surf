

<h3 align='center'>term.tree</h3>
<p align='center'>
  The Seed DSL Library
</p>

<br/>

## Overview

term.tree contains the DSL definitions for the Seed language's parsing
and compilation system. It provides the declarative grammars that drive
how `.tree` source is parsed, analyzed, and transformed.

### Mill/Mine/Mint System

The core DSL is the **mill** system, which has three layers:

- **mill** declares a combined parser/builder processor
- **mine** (parser) matches patterns in the input and emits named nodes
  via `take`
- **mint** (builder) observes mine events via `case`, stores values in
  `slot`, and constructs typed AST nodes in `hook make`

## License

Copyright 2021-2026+ <a href='https://clue.surf'>ClueSurf</a>

Licensed under the Apache License, Version 2.0 (the "License"); you may
not use this file except in compliance with the License. You may obtain
a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## ClueSurf

Made by [ClueSurf](https://clue.surf), meditating on the universe ¤.
Follow the work on [YouTube](https://youtube.com/@cluesurf),
[X](https://x.com/cluesurf),
[Instagram](https://instagram.com/cluesurf),
[Substack](https://cluesurf.substack.com),
[Facebook](https://facebook.com/cluesurf), and
[LinkedIn](https://linkedin.com/company/cluesurf), and browse more of
our open-source work here on [GitHub](https://github.com/cluesurf).
