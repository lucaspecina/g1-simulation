# g1-simulation

```bash
cp scripts/lab.env.example scripts/lab.env   # completar con los recursos de Azure
bash scripts/lab_up.sh      # GitHub -> VM -> simulador -> túnel
bash scripts/lab_down.sh    # cierra todo y desasigna la VM
bash scripts/lab_sync.sh    # sólo sincroniza una VM ya encendida
```

VM desde cero: [`scripts/vm/README.md`](scripts/vm/README.md).
