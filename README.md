# Quadro Gerencial · Delta Rio Elevadores

Painel de gestão comercial alimentado pelos relatórios Excel do sistema de orçamentos.

## Importante: este repositório não contém dados de clientes

- `index.html` é só o sistema (código, logo e mapa).
- Os dados entram quando alguém importa o Excel em **Central de atualização**.
- O Excel é lido **no próprio navegador** e fica salvo só nele (IndexedDB). Nada é enviado ao GitHub nem a outro servidor.
- Cada computador e navegador tem a própria base. Não há sincronização entre usuários.

**Nunca envie para este repositório** planilhas, backups JSON, cópias portáteis (`Quadro_Gerencial_*_Portatil_*.html`), relatórios das vendedoras ou exportações em Excel/CSV. Eles têm dados pessoais de clientes (LGPD). O `.gitignore` bloqueia esses arquivos.

## Uso
1. Abra o link do GitHub Pages (ou o `index.html`).
2. Central de atualização → **Atualizar banco** → escolha o relatório `…_ATE_DD-MM-AAAA.xlsx`.
3. Confira o semáforo e confirme.
4. Exporte o backup JSON periodicamente e guarde fora do repositório.

## Atualizar a versão
Substitua o `index.html` pela versão nova e faça o commit. Os dados já importados continuam no navegador de cada usuário.

Versão: 1.17
