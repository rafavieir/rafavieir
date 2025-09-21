
````md
<!-- Banner / título -->
<h1 align="center">Rafael Vieira</h1>
<p align="center">
  <b>SRE Linux · Analista de Sistemas</b><br/>
  Infra estável, observável e automatizada — sem drama.
</p>

<p align="center">
  <a href="mailto:SEUEMAIL@exemplo.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-Contact-blue?logo=gmail&logoColor=white">
  </a>
  <a href="https://www.linkedin.com/in/SEULINK/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Rafael%20Vieira-0A66C2?logo=linkedin&logoColor=white">
  </a>
  <img alt="Linux" src="https://img.shields.io/badge/Linux-Admin-333?logo=linux&logoColor=white">
  <img alt="SRE" src="https://img.shields.io/badge/SRE-ops%20%F0%9F%9A%A7-222">
</p>

---

### 👋 Sobre mim
Profissional focado em **Linux**, **virtualização**, **redes** e **automação**. Gosto de mudanças pequenas, métricas que importam e pós-mortem sem caça às bruxas.

- **Hoje:** hardening, backups testados, playbooks Ansible e runbooks enxutos.  
- **Stack:** Proxmox/KVM, Docker/Compose, Nginx, PostgreSQL, Git, Bash/Python.  
- **Obs.:** Prometheus, Grafana, Loki, Alertmanager e integrações.

---

### 🛠️ Tech Stack (prático)
<p>
  <img src="https://img.shields.io/badge/Linux-🐧-black?logo=linux" />
  <img src="https://img.shields.io/badge/Proxmox-VE-E57000?logo=proxmox" />
  <img src="https://img.shields.io/badge/Docker-Compose-2496ED?logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-Automation-EE0000?logo=ansible&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-Reverse%20Proxy-009639?logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-DB-4169E1?logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-Metrics-E6522C?logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-Dashboards-F46800?logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-Scripting-121011?logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-CLI-3776AB?logo=python&logoColor=white" />
</p>

---

### 🚀 O que curto entregar
- **IaC & Pipelines:** deploy previsível e reversível.  
- **Observabilidade de verdade:** SLI/SLO, alertas úteis (sem pager spam).  
- **Automação pé-no-chão:** scripts que a equipe entende e consegue manter.  
- **Segurança por padrão:** princípio do menor privilégio e TLS em tudo.

---

### 📦 Projetos & exemplos (curtos)
- **nginx-https-starter** — Nginx reverso com ACME automático (Let’s Encrypt) e headers seguros.  
- **ansible-linux-baseline** — hardening básico, usuários, SSH, logs.  
- **pve-toolbox** — scripts para templates, tags e backups no Proxmox.  
- **observability-kit** — Prometheus + Grafana + exporters comuns, pronto pra subir.

> Coloco links reais conforme eu for abrindo os repositórios públicos.

---

### 📈 Métricas (automáticas – opcional)
<p>
  <img src="https://github-readme-stats.vercel.app/api?username=SEUUSUARIO&show_icons=true&theme=transparent" alt="GitHub stats" />
</p>
<p>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=SEUUSUARIO&theme=transparent" alt="GitHub streak" />
</p>

---

### 📚 Snippets que me representam
```bash
# Deploy seguro e reversível
git tag -a v1.4 -m "release"
ansible-playbook site.yml --limit=prod || { echo "rollback"; ansible-playbook rollback.yml; }
````

```yaml
# Alert(a) só quando importa
alert: HighWriteLatency
expr: node_disk_written_bytes_total > 150*1024*1024
for: 10m
labels: { severity: warning }
annotations:
  summary: "IO alto em {{ $labels.instance }}"
  runbook: "docs/runbooks/storage-latency.md"
```

---

### 📬 Contato

* **LinkedIn:** [https://www.linkedin.com/in/SEULINK/](https://www.linkedin.com/in/SEULINK/)
* **E-mail:** [SEUEMAIL@exemplo.com](mailto:SEUEMAIL@exemplo.com)
* **Chave GPG (opcional):** `FINGERPRINT_AQUI`

<sub>“Você não gerencia o que não mede. Você não melhora o que não automatiza.”</sub>

```

Quer que eu já troque os placeholders (email, LinkedIn, usuário do GitHub) e crie os nomes dos repositórios citados?
```
