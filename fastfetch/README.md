# fastfetch — painel de nave (NixOS)

Config de fastfetch estilizada como painel de comando de nave espacial, feita pra NixOS.

## Instalação

Copie a pasta `fastfetch` para dentro do seu `~/.config/`:

```bash
cp -r fastfetch ~/.config/
```

Ou, se você gerencia dotfiles com home-manager, aponte o `xdg.configFile` pra este diretório:

```nix
xdg.configFile."fastfetch".source = ./fastfetch;
```

## Estrutura

```
fastfetch/
├── config.jsonc       # config principal
└── ascii/
    └── nixos.txt       # arte ASCII exibida no topo
```

## Uso

```bash
fastfetch
```
