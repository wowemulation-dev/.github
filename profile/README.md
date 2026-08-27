# WoW Emulation &mdash; we are preserving World of Warcraft Classic

<div align="center">

![TOO SOON](https://raw.githubusercontent.com/wowemulation-dev/.github/refs/heads/main/profile/assets/chibi-ragnaros-banner.jpeg "Chibi Ragnaros surrounded by friends")

</div>

WoW Emulation is an open-source community building the tools, servers, and
research to run World of Warcraft Classic on your own hardware — fully
local, with no dependency on Battle.net. We cover every Classic
generation: Classic Era (1.13.x, 1.14.x, 1.15.x), TBC Classic (2.5.x),
Wrath Classic (3.4.x), Cataclysm Classic (4.4.x), and Mists of Pandaria
Classic (5.5.x).

**Join us!** Drop into our [Discord][] or [community discussions][] to
meet fellow enthusiasts, ask questions, and contribute to the future of
WoW Classic preservation.

## What We Work On

- **Content delivery** — [cascette-rs][] implements Blizzard's NGDP
  distribution pipeline and CASC archive format for Classic clients;
  [cascette-py][] is the Python companion for format analysis and
  prototyping. [warcraft-rs][] parses and creates the game file formats
  (MPQ, DBC, BLP, M2, WMO, ADT, WDT, WDL).
- **Client modification** — [wow-patcher][] patches WoW executables to
  connect to a server you control: login redirection, RSA modulus
  replacement, and custom certificate bundle injection.
- **Servers** — [wooly-beast][] runs the game world (TrinityCore fork
  for Wrath 3.3.5); [tavern][] provides the Battle.net account and
  authentication services the clients log in against.
- **Research and tooling** — [binanana][] maintains symbol databases and
  Ghidra analysis scripts for Classic client binaries;
  [protobuf-decompiler][] reconstructs `.proto` files from protobuf
  reflection metadata; [rilua][] is a from-scratch Lua 5.1.1 interpreter
  for addon support; [recast-rs][] provides navigation mesh generation
  and pathfinding.

## Featured Projects

| Project         | Description                                       |
| --------------- | ------------------------------------------------- |
| [cascette-rs][] | NGDP/CASC content delivery for Classic clients    |
| [warcraft-rs][] | File format parsers (MPQ, DBC, BLP, M2, WMO, ADT) |
| [tavern][]      | Battle.net account and authentication services    |
| [wooly-beast][] | Game server (TrinityCore fork, Wrath 3.3.5)       |
| [wow-patcher][] | Client patching tools                             |
| [binanana][]    | Symbol database and Ghidra analysis for Classic   |
| [rilua][]       | Lua 5.1.1 interpreter in pure Rust                |
| [recast-rs][]   | Navigation mesh generation and pathfinding        |

## Getting Started

We're all learning together — mistakes are how we grow.

1. Join our [Discord][] and say hello
2. Introduce yourself in our [community discussions][]
3. Check out our [Contributing Guide](../CONTRIBUTING.md)
4. Look for issues labeled "good first issue" in our projects
5. Ask questions — we love helping newcomers

**New to open source?** We've all been there. Need help with Git? Want a
mentor? Ask in discussions.

## Connect

- [Community Discussions][] - Your questions make our community better!
- [Discord][] - Join our server! Many members are creators of WoW modding
  tools.
- <a rel="me" href="https://toot.wowemulation.dev/@wowemulation">Mastodon</a> -
  Follow us @wowemulation@wowemulation.dev
- [Email us][mail] - For anything you'd rather discuss privately
- [@danielsreichenbach][] - Our friendly primary caretaker

[community discussions]: https://github.com/orgs/wowemulation-dev/discussions
[mail]: mailto:hello+github@wowemulation.dev
[@danielsreichenbach]: https://github.com/danielsreichenbach
[Discord]: https://discord.gg/Jj4uWy3DGP
[warcraft-rs]: https://github.com/wowemulation-dev/warcraft-rs
[cascette-rs]: https://github.com/wowemulation-dev/cascette-rs
[cascette-py]: https://github.com/wowemulation-dev/cascette-py
[tavern]: https://github.com/wowemulation-dev/tavern
[wooly-beast]: https://github.com/wowemulation-dev/wooly-beast
[wow-patcher]: https://github.com/wowemulation-dev/wow-patcher
[binanana]: https://github.com/wowemulation-dev/binanana
[protobuf-decompiler]: https://github.com/wowemulation-dev/protobuf-decompiler
[rilua]: https://github.com/wowemulation-dev/rilua
[recast-rs]: https://github.com/wowemulation-dev/recast-rs
