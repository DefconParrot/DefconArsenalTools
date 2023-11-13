#  STrace

Category/Tags: Framework, DTrace, Windows SysCall

 Tool Presented at: Defcon 30 - (Y.2023)

 Author/Presenter: [Stephen Eckels](https://twitter.com/stevemk14ebr) 

## Tool Description

 ![STrace](https://user-images.githubusercontent.com/6619205/239956166-bc9b2103-717a-4df1-8c6a-a001db1c75fc.png)

Steve's Tracer — a reimplementation of Windows syscall hook using DTrace. A PatchGuard-compatible SSDT hook, but without any hacks. It doesn't extend support to SSSDT (win32k APIs) since the DTrace system call APIs inherently lack compatibility with this additional table. However, it enables tracing Zw* kernel APIs along with all user-mode SSDT syscalls.

## Reference Links:

 - Link to Tool⚙️ => https://github.com/mandiant/STrace

 - Link to slide✍️ => https://media.defcon.org/DEF%20CON%2030/DEF%20CON%2030%20presentations/Stephen%20Eckels%20-%20STrace%20-%20A%20DTrace%20on%20windows%20reimplementation.pdf

 - Link to Talk(presentation)📺 => *pending*

 - Link to blog🧾 => *pending*

## Author Description

 - *Stephen Eckels* Senior Reverse Engineer (FLARE)

## Author's Social Links:

 - [Twitter: @stevemk14ebr↗](https://twitter.com/stevemk14ebr)
