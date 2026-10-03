# Hawser

Remote Docker agent for [Dockhand](https://dockhand.pro).

Fork of [Finsys/hawser](https://github.com/Finsys/hawser) with RISC-V (`riscv64`) builds.
Docs and configuration reference: [upstream README](https://github.com/Finsys/hawser#readme).

## Install

```bash
curl -fsSL https://raw.githubusercontent.com/ForkPrince/hawser/main/scripts/install.sh | bash
```

## Configure

Edit `/etc/hawser/config`, then:

```bash
sudo systemctl enable --now hawser
```

## License

MIT — see [LICENSE](LICENSE).
