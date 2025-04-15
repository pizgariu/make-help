## About

This is an extended fork of [Xanders/make-help](https://github.com/Xanders/make-help), 
featuring:

- support for required/optional arguments (`!@`, `?@`)
- required/optional options (`!--`, `?--`)
- group metadata with priority-based ordering (`# Group: Name`)
- CLI validation (missing/invalid arguments or options)
- usage line generation per target (`Usage:` section)
- support for private targets (marked with `# Private` — hidden from default help)
- detection and rendering of undocumented targets (targets without any metadata)
- per-target help: `make help <target>` shows usage for a single command only
