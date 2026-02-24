# Welcome to WoW Emulation

<div align="center">

![TOO SOON](https://raw.githubusercontent.com/wowemulation-dev/.github/refs/heads/main/profile/assets/chibi-ragnaros-banner.jpeg "Chibi Ragnaros surrounded by friends")

</div>

WoW Emulation is a warm, beginner-friendly community that preserves
and archives all versions of World of Warcraft.

**Join us!** Drop into our [Discord][] or
[community discussions][] to meet fellow enthusiasts, ask
questions, and contribute to the future of WoW preservation.

We actively develop tools for modern WoW Classic clients,
letting you experience the game without relying on Battle.net.
Our [cascette-rs][] project implements Blizzard's NGDP
distribution protocol and CASC archive format, creating a
complete alternative for playing Classic Era, TBC Classic,
Wrath Classic, Cataclysm Classic, and Mists of Pandaria
Classic.

## What We Work On

We actively develop for modern WoW Classic clients while
providing archival support for original releases.

| Era                     | Versions               | Format    |
| ----------------------- | ---------------------- | --------- |
| Classic Era             | 1.13.x, 1.14.x, 1.15.x | CASC/NGDP |
| Burning Crusade Classic | 2.5.x                  | CASC/NGDP |
| Wrath Classic           | 3.4.x                  | CASC/NGDP |
| Cataclysm Classic       | 4.4.x                  | CASC/NGDP |
| Mists of Pandaria Remix | 5.5.x                  | CASC/NGDP |
| Vanilla                 | 1.x                    | MPQ       |
| The Burning Crusade     | 2.x                    | MPQ       |
| Wrath of the Lich King  | 3.x                    | MPQ       |
| Cataclysm               | 4.x                    | MPQ       |
| Mists of Pandaria       | 5.x                    | MPQ       |

**CASC/NGDP**: Modern archive format with Blizzard's content
distribution pipeline. We build replacement infrastructure for
the Battle.net client that works with modern WoW Classic
clients.

**MPQ**: Legacy archive format used in original releases
through Mists of Pandaria. Supported for archival purposes.

## Featured Projects

| Project         | Description                                             |
| --------------- | ------------------------------------------------------- |
| [cascette-rs][] | NGDP/CASC implementation for modern WoW Classic clients |
| [warcraft-rs][] | File format parsers (MPQ, DBC, BLP, M2, WMO, ADT)       |
| [rilua][]       | Lua 5.1.1 interpreter in pure Rust                      |
| [wow-patcher][] | Game client patching tools                              |
| [recast-rs][]   | Navigation mesh library with WASM support               |

## Community Projects

### One Home for WoW Tooling

Working with WoW game data used to mean digging through
dozens of repositories and forums, hoping code still worked
and links weren't dead. Everyone solved the same problems
in isolation.

Now **warcraft-rs** handles original releases (MPQ, BLP textures,
M2 models, WMO objects, ADT terrain, DBC databases) and
**cascette-rs** handles modern Classic clients (NGDP, CASC).
One place, one community - your next project starts with working
code instead of weeks of research.

### A Lua VM, Built Together

WoW uses Lua 5.1 for its interface and scripting. Building tooling
around it meant binding to a C library - if you could make it work
on your platform.

Together we built **rilua**: a complete Lua 5.1.1 virtual
machine in pure Rust. Compiler, VM, garbage collector, full
standard library. Byte-identical to official PUC-Rio
implementation. Pure Rust, no FFI, works everywhere including
WASM. One community effort everyone can build on.

---

Building something cool? We'd love to feature it! Drop us a
message in [community discussions][] or [Discord][].

## Our Mission

- Archival - Preserving gaming history
- Community - Keeping the magic alive together
- Learning - Growing our skills while having fun
- Inclusivity - Creating wonderful experiences for everyone

## Getting Started

Remember: We're all learning together! Mistakes are how we grow!

1. Say hello in our [community discussions][]
2. Check out our [Contributing Guide](../CONTRIBUTING.md)
3. Look for issues labeled "good first issue" in our projects
4. Ask questions - we love helping newcomers

**New to open source?** We've all been there! Need help with Git? Want a mentor? Just ask in discussions!

## Connect

- [Community Discussions][] - Your questions make our community better!
- [Discord][] - Join our server! Many members are creators of WoW modding tools.
- [@wowemulation@mastodon.social][] - Follow us on Mastodon
- [Email us][mail] - For anything you'd rather discuss privately
- [@danielsreichenbach][] - Our friendly primary caretaker

[@wowemulation@mastodon.social]: https://mastodon.social/@wowemulation
[community discussions]: https://github.com/orgs/wowemulation-dev/discussions
[mail]: mailto:hello+github@wowemulation.dev
[@danielsreichenbach]: https://github.com/danielsreichenbach
[Discord]: https://discord.gg/Jj4uWy3DGP
[warcraft-rs]: https://github.com/wowemulation-dev/warcraft-rs
[cascette-rs]: https://github.com/wowemulation-dev/cascette-rs
[rilua]: https://github.com/wowemulation-dev/rilua
[wow-patcher]: https://github.com/wowemulation-dev/wow-patcher
[recast-rs]: https://github.com/wowemulation-dev/recast-rs
