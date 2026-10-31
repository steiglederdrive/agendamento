# Ingressos por Pix (protótipo)

Página de inscrição para venda de ingressos com pagamento por Pix, envio de comprovante e painel de conferência.

## O que tem
- **Inscrição:** dados do participante (CPF validado), QR Code/copia e cola Pix, upload do comprovante e ID E2E (validação de formato e bloqueio de duplicidade).
- **Conferência:** resumo, busca/filtros, detalhe com comprovante, aprovação manual e conciliação com o extrato (`ID E2E;valor;data`).

## Como usar
Abra o `index.html` no navegador. Não precisa de servidor.

## Limites do protótipo
- Os dados ficam só no `localStorage` do navegador.
- O QR Code, a chave Pix, o evento e o valor são exemplos.
- Sem login, sem envio de e-mail e sem integração com banco.

## Próximos passos
1. Backend com banco de dados e login (AD).
2. Integração com a API Pix do banco recebedor (cobrança imediata + webhook) para baixa automática.
3. Importador do extrato do banco (OFX/CSV) como alternativa.
4. Envio do ingresso com QR Code por e-mail e leitura na portaria.
