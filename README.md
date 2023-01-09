# ArgoCD App box
ArgoCD Apps with ApplicationSet Project &amp; Application
Use teh main file that should call the reamaning apps

```
├── ApplicationSet_main.yaml
├── apps
│   ├── app-abc1
│   │   ├── dev
│   │   │   └── Application_dev.yaml
│   │   └── prod
│   │       └── Application_prod.yaml
│   ├── app-abc2
│   │   ├── dev
│   │   │   └── Application_dev.yaml
│   │   └── prod
│   │       └── Application_prod.yaml
│   └── app-abc3
│       ├── dev
│       │   └── Application_dev.yaml
│       └── prod
│           └── Application_prod.yaml
├── ArgoAppProject.yaml
└── README.md
```
