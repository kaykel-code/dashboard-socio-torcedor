# Dashboard Sócio Torcedor · FutebolCard

Hub de dashboards analíticos de programas de Sócio Torcedor para clubes parceiros da FutebolCard.

## Estrutura

| Arquivo | Clube | Rota |
|---|---|---|
| `index.html` | Hub geral | `/` |
| `overview.html` | Visão executiva | `/overview` |
| `nautico-dashboard-final.html` | Náutico | `/nautico` |
| `abc-dashboard.html` | ABC FC | `/abc` |
| `abc-exclusivo.html` | ABC FC (versão clube) | `/abc-exclusivo` |
| `avai-dashboard.html` | Avaí FC | `/avai` |
| `america-dashboard.html` | América-RN | `/america` |
| `confianca-dashboard.html` | Confiança | `/confianca` |
| `ponte-dashboard.html` | Ponte Preta | `/ponte` |
| `sampaio-dashboard.html` | Sampaio Corrêa | `/sampaio` |
| `santacruz-dashboard.html` | Santa Cruz | `/santacruz` |
| `sergipe-dashboard.html` | Sergipe | `/sergipe` |

## Base de dados

Todos os dashboards utilizam bases exportadas de **02/06/2026**.  
Análises processadas via Python (pandas) a partir dos CSVs do sistema FutebolCard.

## Deploy

Hospedado no Vercel. Cada push na branch `main` aciona deploy automático.

---

*FutebolCard · Inteligência de Dados · 2026*
