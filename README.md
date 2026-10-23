<div align="center">

# AshReo

<sub>FOUNDER · <a href="https://github.com/EmergeShift">EMERGESHIFT</a></sub>

</div>

Most agents can call tools. Few can keep a machine.

I work on the other half: an environment with a filesystem, a desktop, an undo, and a way to
move — one protocol covering all four. The state-holding and protocol-parsing layers are
written in Rust, because those are the parts that must not fail quietly.

## Selected work

### [mixumOS](https://github.com/EmergeShift/mixumOS)

An Arch-based operating system for agents. The workspace is an event-sourced filesystem: every
task begins with a snapshot, any snapshot forks into a parallel timeline, and the whole tree can
be pushed to another machine while the agent's windows keep streaming.

### [Mixum Agent Protocol](https://github.com/EmergeShift/Mixum-Agent-Protocol)

The contract between an agent and its environment — tasks, snapshots, mobility, windows.
MCP standardized the tool; MAP standardizes the machine.

### [MixumART](https://github.com/EmergeShift/MixumART)

The host runtime: one Tauri app and one CLI that turn Apple Container, Docker, or WSL 2 into a
disposable, inspectable mixumOS environment.

## Now

- Taking mixumOS from v0.1.5 to 1.0
- Freezing the MAP v1 wire format
- Keeping what still doesn't work documented

## Stack

`Rust` `TypeScript` `Python` `C` `Tauri` `Wayland`

---

<p align="center"><sub>Built in the open at <a href="https://github.com/EmergeShift">EmergeShift</a>.</sub></p>
