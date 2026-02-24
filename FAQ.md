# Frequently Asked Questions

Got questions? We've got answers! 🎉

## General Questions

### Is this legal?

We're a community focused on **preservation and education**. We develop tools
for working with game data files, not for running unauthorized servers. Think of
us like librarians for gaming history - we help preserve and understand the
technology, not circumvent protections or enable piracy.

Our work focuses on:

- Building tools to read and write game data formats
- Documenting how the game clients work
- Creating educational resources for game technology

We don't distribute game client software, assets, or help people avoid paying
for games.

### I found a YouTube video about running a private server

That's probably not us! 🙃 We're a different kind of WoW emulation community.
We focus on:

- **Building tools** - Libraries for reading game files, not running servers
- **Learning** - Understanding how the game works at a technical level
- **Preservation** - Making sure this knowledge isn't lost to time

If you want to learn how game file formats work, how to parse MPQ or CASC
archives, or understand the structure of DBC databases - you're in the right
place!

### What's the difference between original and Classic clients?

**Original clients** (1.x through 5.x) are the versions released from 2004-2012.
They use the MPQ archive format and are no longer officially supported.

**Classic clients** are modern recreations released by Blizzard starting in
2019. They use the CASC archive format and Blizzard's NGDP content delivery
system. These are actively maintained and require an active subscription.

We support both, but our primary focus is on Classic clients since they're the
actively maintained versions.

### Do I need to know programming?

Not necessarily! We welcome:

- **Testers** - Try our tools and report what works or doesn't
- **Documentation writers** - Help explain things in plain language
- **Community helpers** - Answer questions in discussions
- **Ideas people** - Share what you'd like to see

If you do want to learn programming, we're happy to help you get started! Many
of our contributors made their first open source contributions here.

## Technical Questions

### What programming languages do you use?

Most of our projects are written in **Rust** - it's fast, safe, and great for
systems programming. We also have some Python for prototyping and C++ for
legacy compatibility.

Don't know Rust? Don't worry! The community is happy to help you learn.

### What's an MPQ? What's CASC?

These are archive formats used by World of Warcraft to store game data:

- **MPQ** (Mo'PaQ) - Used by original clients (2004-2012). Like a ZIP file but
  specialized for games.
- **CASC** (Content Addressable Storage Container) - Used by modern Blizzard
  games. More complex but more efficient for large games with frequent updates.

Our [warcraft-rs](https://github.com/wowemulation-dev/warcraft-rs) project
handles MPQ files, and [cascette-rs](https://github.com/wowemulation-dev/cascette-rs)
handles CASC/NGDP.

### What's NGDP?

NGDP (Next Generation Distribution Protocol) is Blizzard's system for
delivering game content. It handles:

- Downloading game files
- Verifying file integrity
- Applying patches incrementally

Think of it like a very specialized BitTorrent system for game files.

### Which WoW versions do you support?

Our tools support WoW versions from Vanilla (1.x) through Mists of Pandaria
(5.x), including both original and Classic releases. See our
[profile README](profile/README.md) for the full list.

## Community Questions

### How do I get started?

1. 👋 Say hello in our [Discussions](https://github.com/orgs/wowemulation-dev/discussions)
2. 📖 Read our [Contributing Guide](CONTRIBUTING.md)
3. 🎯 Look for "good first issue" labels in our projects
4. 🤔 Ask questions - we love helping newcomers!

### What if I make a mistake?

Mistakes are how we learn! 🌟 Seriously, everyone starts somewhere. We're here
to help, not judge. Even our most experienced contributors make mistakes
sometimes.

### How can I help?

We're always looking for:

- 🧪 **Testers** - Try our tools with your game files
- 📝 **Documentation writers** - Help explain things clearly
- 🐛 **Bug reporters** - Tell us when things don't work
- 💡 **Feature suggesters** - Share your ideas
- 🤝 **Community helpers** - Answer questions, welcome newcomers

Check out our [Discussions](https://github.com/orgs/wowemulation-dev/discussions)
to see what people are working on!

### Where can I talk to people?

- **[Discord](https://discord.gg/Jj4uWy3DGP)** - Real-time chat with 100+ active
  members
- **[GitHub Discussions](https://github.com/orgs/wowemulation-dev/discussions)** -
  Longer-form conversations
- **[Mastodon](https://mastodon.social/@wowemulation)** - Follow our updates

---

Still have questions? Ask in our
[Discussions](https://github.com/orgs/wowemulation-dev/discussions) or join our
[Discord](https://discord.gg/Jj4uWy3DGP)! We're happy to help! 💚
