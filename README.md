## HELM Charts 

O **Helm** é um gerenciador de pacotes de aplicações em execução no Kubernetes que descreve a estrutura de uma aplicação através dos *Helm Charts*, facilitando a instalação e o gerenciamento de pacotes e suas dependências. O Helm é semelhante aos gerenciadores de pacotes de sistemas operacionais yum, apt m, Homebrew, etc.

## API - Beneficiário Tasy
```
├── charts
├── Chart.yaml
├── README.md
├── templates
│   ├── deployment.yaml
│   ├── hpa.yaml
│   ├── services.yaml
│   └── tests
└── values.yaml
```
Diretório: "templates" é onde fica concentrado todos os yamls ou "charts" responsáveis por subir o container em kubernetes da api do beneficiário do tasy.
