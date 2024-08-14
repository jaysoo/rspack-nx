Run `nx show project rspack-project` to see all inferred targets + package scripts.

Run scripts:

```shell
npm run build
npm run dev
```

Those scripts are wrapping the inferred nx commands:

```
nx rspack:build
nx rspack:dev
```

Where `rspack:build` and `rspack:dev` names are configured in `nx.json` (in `plugins`).


