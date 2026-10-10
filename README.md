# Política de Privacidade — PreCalc (extensão do Chrome)

*Última atualização: 10 de outubro de 2026*

A extensão PreCalc, desenvolvida por **Gabriel de Jesus Silva**, automatiza
tarefas do sistema PreCalc no PJe e no SAPRE do Tribunal de Justiça do Piauí
(TJPI): a intimação da memória de cálculo no PJe e o preenchimento dos valores
da memória de cálculo no Pagamento Geral do SAPRE.

## Resumo

- A extensão **não coleta, não vende e não envia** dados ao desenvolvedor.
- Não há anúncios, rastreamento, análise de uso (analytics) nem cookies próprios.
- O que a extensão guarda fica **no navegador do próprio usuário**.
- A extensão só se comunica com os sistemas do TJPI (`*.tjpi.jus.br`): o PJe,
  o SAPRE e o servidor do PreCalc, usando a sessão em que o usuário já está
  logado.

## Quais dados a extensão acessa

Para funcionar, a extensão lê as telas do PJe e do SAPRE abertas pelo
usuário. Essas telas contêm dados de processos judiciais, como número do
processo, nomes das partes e destinatários das intimações, prazos, texto da
minuta e valores de pagamento.

Na página dos autos, a extensão lê só os **nomes** das partes, sem CPF, CNPJ
ou OAB, para montar os destinatários da intimação.

A extensão **não lê nem guarda senhas nem o PIN do certificado digital**. O
login é feito pelo usuário nos próprios sistemas, e o PIN é digitado por ele
no PJeOffice.

## Onde os dados ficam

| Dado | Onde fica |
|---|---|
| Opções escolhidas no popup e endereço do PreCalc | Armazenamento local do navegador (`chrome.storage`) |
| Log das últimas execuções (até 300 linhas) | Armazenamento local do navegador |
| Histórico das intimações (até 3.000 registros: número do processo, data, resultado, destinatários e meio de intimação) | Armazenamento local do navegador |
| Histórico exportado em CSV ou captura de tela para suporte | Arquivo baixado no computador do usuário, só quando ele clica no botão correspondente |

Remover a extensão apaga os dados guardados no navegador. Os arquivos baixados
continuam no computador até o usuário apagá-los.

## Para onde os dados podem ser enviados

1. **PJe e SAPRE do TJPI** — as operações rodam nos próprios sistemas, com a
   sessão do usuário, como se ele estivesse fazendo à mão.
2. **Servidor do PreCalc do TJPI** (`precalc-hom.tjpi.jus.br`) — no SAPRE, a
   extensão consulta o número do processo e o identificador do pagamento para
   buscar a memória de cálculo (valor líquido, IR e previdência) já registrada
   no PreCalc. O acesso exige login no PreCalc com perfil autorizado.
3. **PJeOffice** (aplicativo de assinatura no computador do usuário) — só
   quando o usuário pede para assinar a intimação.

Nenhum dado é enviado a qualquer outro destino.

## Uso limitado

O uso das informações obtidas pela extensão segue a
[Política de Dados do Usuário da Chrome Web Store](https://developer.chrome.com/docs/webstore/program-policies/user-data-faq),
incluindo os requisitos de **Uso Limitado**: os dados são usados apenas para
oferecer as funções da extensão descritas acima; não são transferidos a
terceiros, não são usados para publicidade nem para avaliar crédito, e não são
lidos por pessoas, exceto pelo próprio usuário.

## LGPD

O tratamento dos dados pessoais exibidos no PJe e no SAPRE é feito pelo
usuário, no exercício das suas funções e sob a responsabilidade do Tribunal de
Justiça do Piauí. A extensão é apenas uma ferramenta executada no computador do
usuário; o desenvolvedor não recebe esses dados.

## Contato

Dúvidas sobre esta política: Gabriel de Jesus Silva —
gabrieldjesus588@gmail.com.

Mudanças nesta política serão publicadas nesta mesma página, com a data de
atualização.
