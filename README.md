# PortSwigger Web Security Academy - Write-ups & Labs 🛡️

Repositório dedicado à documentação técnica, análise de vulnerabilidades e resolução prática de laboratórios da **[PortSwigger Web Security Academy](https://portswigger.net/web-security)**. 

O foco deste repositório é demonstrar metodologia analítica, fluxo de reconhecimento, exploração controlada (*Proof of Concept - PoC*) e recomendações técnicas de mitigação alinhadas aos padrões de **Application Security (AppSec)** e **Bug Bounty**.

---

## 📊 Progresso dos Laboratórios

| Categoria | Apprentice | Practitioner | Expert | Total |
| :--- | :---: | :---: | :---: | :---: |
| **Access Control (Controle de Acesso)** | 1 | 0 | 0 | **1** |
| **Authentication (Autenticação)** | 1 | 0 | 0 | **1** |
| **Total Geral** | **2** | **0** | **0** | **2** |

---

## 📂 Laboratórios Documentados

### 🔐 Access Control (Controle de Acesso)

| Laboratório | Nível | Vulnerabilidade / Tópico | Write-up |
| :--- | :---: | :--- | :---: |
| **Unprotected admin functionality with unpredictable URL** | `Apprentice` | Broken Access Control / Security through Obscurity | [Acessar Write-up](./access-control/unprotected-admin-functionality-with-unpredictable-url/) |

### 🔑 Authentication (Autenticação)

| Laboratório | Nível | Vulnerabilidade / Tópico | Write-up |
| :--- | :---: | :--- | :---: |
| **Username enumeration via different responses** | `Apprentice` | Broken Authentication / Information Disclosure | [Acessar Write-up](./authentication/username-enumeration-via-different-responses/) |

---

## 🛠️ Ferramentas & Metodologia
- **Intercepção & Proxy:** Burp Suite Community / Professional (Proxy, Repeater, Intruder, Target/Sitemap)
- **Inspeção & Debugging:** DevTools (Network, Console, DOM Inspection)
- **Padrões & Frameworks:** OWASP Top 10, CWE / CVE, NIST SP 800-115
- **Documentação:** Write-ups com requisições HTTP brutas (*Raw HTTP*), evidências visuais e diretrizes de remediação
