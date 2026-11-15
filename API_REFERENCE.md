# API reference

TCP/UDP handles are opaque `usize` values returned by the host. The package validates ports and IPv4 text before a host call; send/receive status remains an explicit signed result. Hosts own socket lifetime and must make close idempotent.

