<h1 align="center">Игорь Плотников</h1>
<p align="center">
  <b>Infrastructure Engineer · DevOps</b><br>
  Linux · Сети · Docker · Kubernetes · CI/CD · GitOps · IaC · AI · Observability
</p>

<p align="center">
  Проектирую и эксплуатирую <b>on-prem и облачную</b> инфраструктуру.<br>
  Открыт к удалённой работе.
</p>

---

## Стек

| Направление | Технологии |
| :--- | :--- |
| **Облака и хранилища** | Yandex Cloud · Timeweb Cloud · S3 · Synology|
| **Контейнеры и виртуализация** | Docker · Docker Compose · K8s · Helm · Portainer · Proxmox · KVM |
| **CI/CD и GitOps** | GitHub Actions · GitLab CI · ArgoCD · GHCR · Приватные registry |
| **IaC и автоматизация** | Terraform · Ansible · Jinja2 · Bash · Python |
| **Секреты и безопасность** | HashiCorp Vault · Ansible Vault · Trivy |
| **Сети** | TCP/IP · Cisco · MikroTik · VPN · Nginx · Caddy · Traefik |
| **Observability** | Prometheus · Grafana · Loki · Alertmanager · SNMP |

---

## Проекты

**[infra-k8s-cicd](https://github.com/wwwplotnikov/infra-k8s-cicd)** — end-to-end CI/CD
> Lint и тесты, сборка образа, скан **Trivy** до публикации, деплой через Helm
> в kind-кластер, smoke-тест. Non-root контейнер, security context, liveness
> и readiness пробы.

**[gitops-demo-app](https://github.com/wwwplotnikov/gitops-demo-app)** + **[gitops-demo-config](https://github.com/wwwplotnikov/gitops-demo-config)** — GitOps
> **ArgoCD** по pull-модели, разнесённый на два репозитория: код с CI
> и желаемое состояние кластера.

**[devops-troubleshooting-lab](https://github.com/wwwplotnikov/devops-troubleshooting-lab)** — диагностика
> Воспроизводимые инфраструктурные инциденты. Контейнер поднимается уже
> сломанным: connection refused, цикл рестартов, exit 0 из-за фонового процесса,
> OOM 137, потеря данных мимо volume. К каждому сценарию разбор от симптома
> к причине.

**[ansible-toolkit](https://github.com/wwwplotnikov/ansible-toolkit)** — IaC
> Переиспользуемые роли и плейбуки для типовой настройки сервера: Docker,
> security hardening, базовое окружение. Идемпотентно, с шаблонами на Jinja2.

---

<p align="center">
  <a href="https://iplotnikov.com">iplotnikov.com</a> ·
  <a href="https://t.me/plotnikovig">Telegram</a>
</p>
