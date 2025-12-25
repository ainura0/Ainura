/project-repository
├── README.md                      // Осы жоспар
├── .github/                       // CI/CD (GitHub Actions)
│   └── workflows/ci-cd.yml        
├── /src                           // Қосымша кодтары (Go және Next.js)
│   ├── /backend
│   └── /frontend
└── /infra                         // Инфрақұрылым код ретінде (IaC)
    ├── Dockerfile.backend         // Go қосымшасына арналған Dockerfile
    └── /terraform
        ├── main.tf                // K8s кластері, DB, Redis
        └── variables.tf
