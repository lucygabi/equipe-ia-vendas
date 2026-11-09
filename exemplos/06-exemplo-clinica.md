# Exemplo · 06 Agente de Retorno

**Negócio:** clínica de dermatologia (fictícia) · [ver a ficha usada](ficha-clinica.md)
**Agente:** [Agente de Retorno](../agentes/06-agente-de-retorno.md)

Resposta real de uma IA durante os testes do kit (9 de novembro de 2026), sem edição. O negócio e as pessoas são fictícios. Os trechos [COMPLETAR] são de propósito: a IA não inventa o que a ficha não traz.

## O pedido
```text
A Paula pediu horário para consulta de queda de cabelo, eu mandei os horários de terça e ela não respondeu mais. Faz 3 dias.
```

## A resposta
**Mensagem 1 · enviar já (o prazo de 2 a 3 dias depois da última mensagem já passou)**

Oi, Paula! Passando para ver se os horários que enviei para a sua consulta serviram. Se preferir outro dia ou período, é só me dizer que eu confiro a agenda. Qual período fica melhor para você?

**Mensagem 2 · enviar de 5 a 7 dias depois da última mensagem sem resposta (ou seja, daqui a 2 a 4 dias)**

Oi, Paula! Uma informação que pode ajudar: a consulta com a Dra. Marina dura 40 minutos, sem pressa, e o retorno está incluso em até 30 dias. Também aceitamos Bradesco Saúde e SulAmérica para consultas. Se quiser, me diga o melhor período e eu confiro a agenda. Qual período fica melhor para você?

**Mensagem 3 · enviar de 12 a 15 dias depois da última mensagem sem resposta (ou seja, daqui a 9 a 12 dias)**

Oi, Paula! Vou deixar a nossa conversa em aberto por aqui, sem pressa. Quando fizer sentido para você, é só me chamar. Atendemos de segunda a sábado, das 8h às 18h. Desejo tudo de bom!

**Pare a sequência se:** a Paula responder (nesse caso, siga com a 5 · Atendente de WhatsApp), agendar a consulta, disser que não tem interesse ou pedir para não receber mais mensagens.

**Revise e aprove antes de enviar.**
