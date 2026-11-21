# SigmaOS-aria2c

SigmaOS integration component for **aria2c**.

## Commands

```bash
sigmaos-aria2c install   # install package + deploy defaults
sigmaos-aria2c deploy    # copy config templates to $HOME
sigmaos-aria2c status    # binary/package/config report
sigmaos-aria2c reset     # remove deployed config
sigmaos-aria2c open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
