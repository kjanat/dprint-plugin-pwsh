# dprint-plugin-pwsh

Release mirror for the [PowerShell dprint plugin][monorepo] — a standalone
PowerShell formatter (no PowerShell, no .NET) matching PSScriptAnalyzer's
`Invoke-Formatter` output.

## Install

```sh
dprint add kjanat/pwsh
```

or pin a version in `dprint.json`:

```jsonc
{
  "powershell": { "indentWidth": 4 },
  "plugins": ["https://plugins.dprint.dev/kjanat/pwsh-x.y.z.wasm"]
}
```

## Source

No source here — code, [configuration docs][config-docs], and issues live in
[kjanat/powershell-formatter][monorepo].

[monorepo]: https://github.com/kjanat/powershell-formatter
[config-docs]: https://github.com/kjanat/powershell-formatter/blob/master/docs/configuration.md
