# MicrosoftEntraID
Microsoft Entra ID

Microsoft Entra ID e Segurança em Nuvem
O que é o Microsoft Entra ID?
O Microsoft Entra ID (antigo Azure Active Directory) é a solução de gerenciamento de identidade e acesso (IAM) baseada em nuvem da Microsoft. Ele funciona como o "porteiro" digital das organizações, controlando quem pode acessar quais recursos, aplicativos e dados — tanto na nuvem quanto em ambientes híbridos (on-premises + cloud).

Principais Funcionalidades
🔐 Autenticação e Identidade

SSO (Single Sign-On): o usuário faz login uma única vez e acessa todos os aplicativos integrados (Microsoft 365, Salesforce, GitHub etc.)
MFA (Autenticação Multifator): exige uma segunda forma de verificação além da senha, reduzindo drasticamente o risco de invasões
Autenticação sem senha: suporte a biometria (Windows Hello), aplicativo Microsoft Authenticator e chaves de segurança FIDO2

🛡️ Acesso Condicional
Políticas inteligentes que avaliam o contexto de cada acesso antes de liberar a entrada:

Localização geográfica do usuário
Dispositivo utilizado (gerenciado ou não)
Nível de risco detectado pela IA
Aplicativo que está sendo acessado

👤 Governança de Identidade

Revisões periódicas de acesso para garantir que só quem deve ter acesso, tem
PIM (Privileged Identity Management): acesso privilegiado just-in-time, evitando contas de administrador permanentemente ativas
Ciclo de vida automatizado de usuários (onboarding e offboarding)

🌐 Identidades Externas

Colaboração segura com parceiros, fornecedores e clientes (B2B e B2C) sem precisar criar contas internas


Microsoft Entra ID e Segurança em Nuvem
O Entra ID é um dos pilares da estratégia de segurança em nuvem da Microsoft, operando em conjunto com outras camadas de proteção:
Zero Trust
O Entra ID é o principal habilitador do modelo Zero Trust — "nunca confie, sempre verifique". Nenhum usuário ou dispositivo é considerado confiável por padrão, mesmo dentro da rede corporativa. Cada acesso é avaliado continuamente.
Proteção de Identidade (Identity Protection)
Usa machine learning para detectar comportamentos suspeitos em tempo real, como:

Logins de locais impossíveis (ex: Brasil e Japão com 1h de diferença)
Credenciais vazadas na dark web
Atividade anômala de contas

Integração com o Ecossistema de Segurança
ServiçoFunçãoMicrosoft Defender for IdentityDetecta ataques a identidades no AD localMicrosoft SentinelSIEM/SOAR para análise e resposta a incidentesDefender for Cloud AppsVisibilidade e controle de apps SaaS (Shadow IT)IntuneGerenciamento de dispositivos para acesso seguro

Por que isso importa?
Mais de 80% das violações de segurança envolvem credenciais comprometidas. Com o trabalho remoto e a adoção massiva de SaaS, a identidade se tornou o novo perímetro de segurança — e o Entra ID é a solução da Microsoft para protegê-la em ambientes modernos de nuvem.

Resumo Visual
Usuário tenta acessar um recurso
         ↓
  Microsoft Entra ID avalia:
  ✔ Quem é? (autenticação)
  ✔ Está autorizado? (autorização)
  ✔ Contexto é seguro? (acesso condicional)
         ↓
  ✅ Acesso liberado   ou   ❌ Bloqueado / MFA exigido
O Entra ID transforma a identidade em uma camada de segurança ativa e inteligente, indo muito além do simples gerenciamento de senhas.
