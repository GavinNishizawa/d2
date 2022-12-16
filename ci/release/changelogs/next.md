#### Features 🚀

- Diagram padding can now can be configured in the CLI (default 100px).
  [https://github.com/terrastruct/d2/pull/431](https://github.com/terrastruct/d2/pull/431)

#### Improvements 🧹

- Fmt now preserves leading comment spacing.
  [#400](https://github.com/terrastruct/d2/issues/400)

#### Bugfixes ⛑️

- Fixed crash when sequence diagrams had no messages.
  [https://github.com/terrastruct/d2/pull/427](https://github.com/terrastruct/d2/pull/427)
- Fixed a crash when external connection IDs were prefixes of a sequence diagram ID. [https://github.com/terrastruct/d2/pull/450](https://github.com/terrastruct/d2/pull/450)
- Fixed `constraint` keyword setting label.
  [https://github.com/terrastruct/d2/issues/415](https://github.com/terrastruct/d2/issues/415)
- Fixed serialization affecting binary plugins (TALA).
  [https://github.com/terrastruct/d2/pull/426](https://github.com/terrastruct/d2/pull/426)
