# Welcome to WoW Emulation! 🎉

<div align="center">

![TOO SOON](https://raw.githubusercontent.com/wowemulation-dev/.github/refs/heads/main/profile/assets/chibi-ragnaros-banner.jpeg "Chibi Ragnaros surrounded by friends")

</div>

[WoW Emulation][] is a warm, beginner-friendly community that's been growing
since August 2023. We're here for anyone interested in experiencing the classic
versions of [World of Warcraft][] that captured our hearts.

## 🎮 What We're About

We preserve and support World of Warcraft, with a primary focus on **WoW
Classic** and archival support for original releases.

### Classic Releases ([CASC Archive Format with NGDP][cascette-rs]) ✨

These are our primary focus - the modern Classic recreations that let players
experience WoW as it was:

- ⚔️ **Classic Era** (1.13.x, 1.14.x, 1.15.x) - Recreation of Vanilla
- 🔥 **Burning Crusade Classic** (2.5.x) - Recreation of TBC
- ❄️ **Wrath Classic** (3.4.x) - Recreation of WotLK
- 🌋 **Cataclysm Classic** (4.4.x) - Recreation of Cataclysm
- 🐼 **Mists of Pandaria Remix** (5.5.x) - Recreation of MoP

These Classic versions use the [CASC archive format and Blizzard's NGDP
content distribution pipeline][cascette-rs]. We're building a replacement for
the Battle.net client that works with modern WoW Classic clients - it's almost
complete!

### Original Releases ([MPQ Archive Format][warcraft-rs])

These older versions are supported for archival purposes:

- ⚔️ **Vanilla** (1.x) - Where it all began
- 🔥 **The Burning Crusade** (2.x) - Through the Dark Portal
- ❄️ **Wrath of the Lich King** (3.x) - Face the Frozen Throne
- 🌋 **Cataclysm** (4.x) - When the world shattered
- 🐼 **Mists of Pandaria** (5.x) - Discover Pandaria's mysteries

These original versions use [MPQ archives][warcraft-rs] for game data storage.

## 🚀 Featured Projects

| Project | Description |
| ------- | ----------- |
| [cascette-rs][] | NGDP/CASC implementation for modern WoW Classic clients |
| [warcraft-rs][] | File format parsers (MPQ, DBC, BLP, M2, WMO, ADT) |
| [rilua][] | Lua 5.1.1 interpreter in pure Rust |
| [wow-patcher][] | Game client patching tools |
| [recast-rs][] | Navigation mesh library with WASM support |

## 🌟 Community Success Stories

Real achievements from our community members.

### From Zero to Game Data

**The Old Way**: Want to work with WoW game data? Good luck. You'd need to dig through 50 GitHub repositories, join 25 Discord servers, and scour 45 forums and web archives - hoping the code still works, the links aren't dead, and someone actually documented what they figured out.

**What We Built**: Two projects now cover the entire WoW data landscape:

- **warcraft-rs** handles everything from the original 2004 release through Mists of Pandaria - MPQ archives, BLP textures, M2 models, WMO world objects, ADT terrain, DBC databases. Parse it, build it, convert it.

- **cascette-rs** handles modern WoW Classic clients using Blizzard's NGDP distribution protocol and CASC archive format. The same workflow, but for 6.0+ game data.

**Why It Matters**: One organization, authoritative sources, active maintenance. No more treasure hunting. Clone the repo, read the docs, build your tool.

### rilua: When You Need a Lua VM

**The Problem**: WoW uses Lua 5.1 for its interface and scripting. If you're building tooling that needs to run or analyze that code, you either bind to a C library or you're out of luck.

**What Happened**: We built a complete Lua 5.1.1 virtual machine from scratch in pure Rust - compiler, VM, garbage collector, full standard library. It produces byte-identical output to the official PUC-Rio implementation.

**Why It Matters**: Pure Rust, no FFI dependencies, works everywhere including WASM. Embed it in your tools without pulling in native libraries.

---

Building something cool? We'd love to feature it! Drop us a message in [community discussions][] or [Discord][].

## 🤝 Our Mission

We're not here to compete with [Classic WoW][] - [Blizzard][] does their thing,
and we do ours! Our focus is on:

- 🏛️ **Archival** - Preserving gaming history
- 🌟 **Community** - Keeping the magic alive together
- 🎓 **Learning** - Growing our skills while having fun
- 💖 **Inclusivity** - Creating wonderful experiences for everyone

## 🌱 First Time Here? Start Here

**Remember: We're all learning together! Mistakes are how we grow! 🌟**

1. 👋 Say hello in our [community discussions][]
2. 📖 Check out our [Contributing Guide](../CONTRIBUTING.md) (it's super
   friendly!)
3. 🎯 Look for issues labeled "good first issue" in our projects
4. 🤔 Ask questions - seriously, we love helping newcomers!

## 🤗 Get Help & Make Friends

- 💬 **[Community Discussions][]** - Your questions make our community better!
- 💬 **[Discord][]** - Join 100+ active members! Many are creators of WoW
  modding tools.
- 🐘 **[@wowemulation@mastodon.social][]** - Follow us on Mastodon!
- 📧 **[Email us][mail]** - For anything you'd rather discuss privately
- 👨‍💼 **[@danielsreichenbach][]** - Our friendly primary caretaker

## 🚀 Join Our Adventure

We're looking for amazing people like YOU! 👀 Whether you're:

- 🎭 **Community Builders** - Help us create the friendliest corner of GitHub
- 🌟 **Fresh Developers** - Your first PR? We'll guide you through it!
- 🧙‍♂️ **Seasoned Engineers** - Share your wisdom and help us grow
- 🎮 **Testers & Players** - Your feedback shapes our projects
- 📝 **Documentation Writers** - Help others learn what you've discovered
- 🎨 **Creative Minds** - Ideas, art, and enthusiasm all welcome!

**No experience? No problem! Enthusiasm is all you need! 💪**

## 📚 Resources for Beginners

- 🎓 **New to Open Source?** Don't worry, we've all been there!
- 🛠️ **Learning Git?** We'll help you through your first commit
- 🤝 **Need a mentor?** Just ask in discussions!

## 💌 Our Promise to You

- ✨ Your contributions matter, no matter how small
- 🤗 We'll treat you with kindness and respect
- 📈 We'll help you grow your skills
- 🎉 We'll celebrate your successes with you!

[WoW Emulation]: https://wowemulation.dev/
[World of Warcraft]: https://worldofwarcraft.blizzard.com/
[Classic WoW]: https://wowclassic.blizzard.com/
[Blizzard]: https://blizzard.com/
[@wowemulation@mastodon.social]: https://mastodon.social/@wowemulation
[community discussions]: https://github.com/orgs/wowemulation-dev/discussions
[mail]: mailto:hello+github@wowemulation.dev
[@danielsreichenbach]: https://github.com/danielsreichenbach
[Discord]: https://discord.gg/Q44pPMvGEd
[warcraft-rs]: https://github.com/wowemulation-dev/warcraft-rs
[cascette-rs]: https://github.com/wowemulation-dev/cascette-rs
[rilua]: https://github.com/wowemulation-dev/rilua
[wow-patcher]: https://github.com/wowemulation-dev/wow-patcher
[recast-rs]: https://github.com/wowemulation-dev/recast-rs
