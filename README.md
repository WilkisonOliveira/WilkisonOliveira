<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B3D91,100:00B4D8&height=200&section=header&text=Wilkison%20Oliveira&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=32&desc=Desenvolvedor%20Full%20Stack%20-%20C%23%2C%20.NET%2C%20Node.js%2C%20React%2C%20Next.js%2C%20TypeScript%2C%20PostgreSQL%2C%20Docker&descAlignY=50&descSize=13" width="100%"/>

Juiz de Fora, MG · wilkisonoliveira0@gmail.com · [LinkedIn](https://www.linkedin.com/in/wilkisonoliveira)

Aberto a novas oportunidades como Desenvolvedor/Estagiário 

</div>

---

## Um pouco sobre mim

Passei os últimos 3 anos no Exército Brasileiro trabalhando com Suporte de TI e Infraestrutura - resolvendo problema de hardware, software, sistema operacional e rede no dia a dia. Foi ali que peguei gosto por entender como as coisas funcionam por baixo do capô, e isso acabou me puxando naturalmente para o desenvolvimento.

Hoje estou cursando Análise e Desenvolvimento de Sistemas no Centro Universitário Newton Paiva (previsão de conclusão em 2027) e migrando de vez para o mundo Full Stack. Já são três projetos próprios em produção - o que eu mais me orgulho é o [Nivvo](https://nivvo-three.vercel.app), um SaaS multi-tenant que já roda com um cliente real. Nas horas vagas, estou sempre voltando para Clean Architecture, Docker e APIs REST, tentando entender cada vez melhor como construir sistemas que aguentam o mundo real.

## Com o que eu trabalho

- **Backend** - C#, .NET, Node.js, TypeScript, JavaScript
- **Frontend** - React, Next.js, HTML, CSS, Tailwind
- **Dados** - PostgreSQL, MySQL, Prisma, Supabase
- **DevOps & Cloud** - Docker, Git, GitHub Actions, AWS, Railway
- **Infraestrutura & Redes** - TCP/IP, DNS, VLANs, Windows, macOS

## O que eu já construí

### [Nivvo](https://nivvo-three.vercel.app) - SaaS multi-tenant de gestão de condomínios

Esse é o projeto que mais me desafiou até hoje. É uma plataforma com três painéis rodando em tempo real sobre o mesmo banco: Portaria (visitantes e encomendas), Administração (financeiro, unidades, usuários) e Portal do Morador (autorização de visitantes, boletos, reservas, avisos). Já está em produção, com um condomínio piloto real - o "Belo Vale" - usando o sistema todos os dias.

Alguns pontos que valem destaque:

- Isolamento multi-tenant de verdade - os dados de cada condomínio ficam completamente separados
- Autenticação JWT customizada com login multi-tenant (`usuario@condominio`) + 2FA via WhatsApp OTP
- Mais de 15 módulos funcionais: visitantes, encomendas, reservas de área comum, financeiro, boletos, ocorrências, enquetes/votação, manutenção preventiva, livro de plantão da portaria, entre outros
- Integração com WhatsApp (Meta Cloud API) para notificações e cobrança automática de boletos via Asaas (webhooks reais, não simulados)
- Dashboards com Recharts, 100% responsivo e pensado mobile-first

**Stack:** Next.js 16, TypeScript, Prisma 7, Supabase, Tailwind v4, shadcn/ui

[Ver em produção](https://nivvo-three.vercel.app) · Repositório privado

### [Resolvia](https://github.com/WilkisonOliveira/resolvia)

Um sistema de gestão de chamados construído do zero em Clean Architecture, tentando simular de perto o dia a dia de uma operação de suporte técnico / service desk - bagagem que eu trago da minha experiência anterior.

- Autenticação JWT + BCrypt, com controle de acesso por perfil (Cliente, Atendente, Admin)
- SLA dinâmico, calculado automaticamente por categoria e prioridade do chamado
- Histórico de auditoria automático - toda mudança de status ou atribuição fica registrada
- Comentários públicos e notas internas, com upload de anexos via Cloudflare R2
- Deploy em produção via Docker + Railway

**Stack:** C#, .NET, PostgreSQL, Docker, Railway

[Testar a API ao vivo (Swagger)](https://resolvia-production-fe32.up.railway.app/swagger) · [Documentação completa](https://github.com/WilkisonOliveira/resolvia#readme)

### [WyxSync](https://wyxsync.com)

Uma plataforma fitness com IA para personalizar treinos e acompanhar progresso. Também está em produção, com usuários reais usando no dia a dia - o que muda completamente a forma como eu penso o código, porque bug em produção é gente de verdade sendo afetada.

- Integração com IA (OpenAI / Groq) para personalização de treinos
- Login com Google OAuth e pagamentos via Mercado Pago
- Containerizado com Docker, deploy via Railway
- Desenvolvido e mantido por mim, de ponta a ponta

**Stack:** React, ASP.NET Core, PostgreSQL, OpenAI, Docker

[Acessar o site](https://wyxsync.com)

### ProductClientHub

Uma API REST em ASP.NET Core para gerenciamento de clientes e produtos - projeto mais focado em fundamentos, onde apliquei arquitetura em camadas, DTOs, injeção de dependência e persistência com Entity Framework Core.

**Stack:** C#, Entity Framework Core

## Cursos e certificações

| Curso | Instituição |
|---|---|
| Formação Full Stack | Meta \| Coursera |
| Fundamentos de Cibersegurança | Meta \| Coursera |
| Clean Code | Rocketseat |
| Infraestrutura de Redes | Nuclemig |
| Técnico em Manutenção e Reparo de Hardware (1,5 ano) | Nuclemig |
| Tecnologia da Informação e Comunicação | Senai |

## Da minha bagagem em suporte e infraestrutura

<details>
<summary>Suporte e Infraestrutura</summary>
<br/>

Suporte técnico N1/N2 · Diagnóstico de hardware e software · Manutenção preventiva e corretiva · Windows · macOS · Instalação e configuração de sistemas · Inventário de ativos · Troubleshooting

</details>

<details>
<summary>Redes</summary>
<br/>

TCP/IP · Modelo OSI · IPv4/IPv6 · Sub-redes · DNS · DHCP · VLANs · Switching · Roteamento · Wireless · Cabeamento estruturado · Fibra óptica · Racks e Patch Panels

</details>

<details>
<summary>Segurança da Informação</summary>
<br/>

Hardening · Controle de acesso · Backup e recuperação de dados · Fundamentos de cibersegurança

</details>

## Contribuições

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/WilkisonOliveira/WilkisonOliveira/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/WilkisonOliveira/WilkisonOliveira/output/github-contribution-grid-snake.svg" />
  <img src="https://raw.githubusercontent.com/WilkisonOliveira/WilkisonOliveira/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</picture>

## Bora conversar?

Se você chegou até aqui, seja porque tá recrutando, seja porque curtiu algum projeto - me chama, sempre bom trocar ideia:

wilkisonoliveira0@gmail.com · [LinkedIn](https://www.linkedin.com/in/wilkisonoliveira) · [GitHub](https://github.com/WilkisonOliveira)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B3D91,100:00B4D8&height=120&section=footer" width="100%"/>
