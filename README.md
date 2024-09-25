# react-resizable-missing-react-dom-peer

Reproduce with:

```shell
yarn install
yarn explain peer-requirements
```

Output:

```shell
pbbf4c → ✓ react-resizable-missing-react-dom-peer@workspace:. provides @types/react@npm:17.0.80 to react-dom@npm:17.0.2 [b10e1] and 4 other dependencies
pc79c9 → ✓ react-resizable-missing-react-dom-peer@workspace:. provides @types/react-dom@npm:17.0.25 to react-grid-layout@npm:1.4.4 [b10e1] and 1 other dependency
p8ece4 → ✓ react-resizable-missing-react-dom-peer@workspace:. provides react@npm:17.0.2 to react-dom@npm:17.0.2 [b10e1] and 4 other dependencies
p5f4fb → ✓ react-resizable-missing-react-dom-peer@workspace:. provides react-dom@npm:17.0.2 [b10e1] to react-grid-layout@npm:1.4.4 [b10e1] and 1 other dependency
p3252b → ✓ react-resizable@npm:3.0.5 [cc909] doesn't provide @types/react-dom to react-draggable@npm:4.4.6 [841f5]
p95cf3 → ✘ react-resizable@npm:3.0.5 [cc909] doesn't provide react-dom to react-draggable@npm:4.4.6 [841f5]
```

See [.yarnrc.yml](./.yarnrc.yml) for a hotfix.
