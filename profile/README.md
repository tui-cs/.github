## Modern, cross-platform, terminal UIs using .NET and Swift since 2007.

The **tui-cs** organization hosts projects related to [gui.cs](http://tirania.org/blog/archive/2007/Apr-16.html) that [Miguel de Icaza](https://github.com/migueldeicaza) wrote for [mono-curses](https://github.com/mono/mono-curses) in 2007. The org is now maintained by [Tig Kindel](https://github.com/tig).

The original **gui.cs** was a single file and tied to the [curses library](https://en.wikipedia.org/wiki/Curses_%28programming_library%29). Since then, gui.cs has been transformed into **Terminal.Gui**, a full-featured library for building modern, cross-platform, TUI applications.

A presentation of gui.cs was part of the [Retro.NET](https://channel9.msdn.com/Events/dotnetConf/2018/S313) talk at .NET Conf 2018 [Slides](https://tirania.org/Retro.pdf)

![Terminal.Gui](https://tui-cs.github.io/Terminal.Gui/images/sample.gif)

The other projects in this organization are either dependencies of Terminal.Gui or related offshoots.

## Projects

- **[Terminal.Gui](https://github.com/tui-cs/Terminal.Gui)** — the cross-platform TUI toolkit for .NET (v2).
- **[clet](https://github.com/tui-cs/clet)** — CLI-lets: rich TUI prompts with consistent JSON output and clean exit codes, for humans *and* AI agents.
- **[cli](https://github.com/tui-cs/cli)** — a library that exposes Terminal.Gui views as scriptable CLI commands with typed JSON output, POSIX exit codes, and AI-agent discoverability.
- **[PSTui](https://github.com/tui-cs/PSTui)** — PowerShell TUI cmdlets (`Out-ConsoleGridView`/`ocgv`, `Show-ObjectTree`/`shot`), built on Terminal.Gui v2. The community continuation of `Microsoft.PowerShell.ConsoleGuiTools` — `Install-Module PSTui`.

The maintainers welcome contributions from the community.
