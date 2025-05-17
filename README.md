# Estufa - Plataforma Pessoal para Moranguetes

**Estufa** é uma plataforma desenvolvida para ajudar você e seus amigos, os **Moranguetes**, a se manterem motivados na academia, além de facilitar o controle de dívidas entre os membros. A proposta é criar um ambiente interativo onde todos possam compartilhar seus progressos e se organizar de forma prática e divertida.

## Funcionalidades

### 1. **Controle de Presença na Academia**

- **Envio de Foto do Dia**: Cada Moranguete pode enviar uma foto todos os dias, como uma "batida de ponto", para registrar sua presença na academia. Isso ajuda a garantir que todos estejam cumprindo seus compromissos com o exercício físico.
  
- **Justificativa de Faltas**: Caso um Moranguete não envie a foto do dia, ele poderá clicar em um botão para justificar sua falta, informando o motivo da ausência.

- **Visão de Calendário**: O sistema oferece uma visão de calendário onde os Moranguetes podem acompanhar seus dias de presença na academia. Isso facilita o acompanhamento da frequência e do progresso ao longo do tempo.

- **Ranking de Faltas**: O sistema gera um ranking de faltas entre os membros do grupo, onde cada um pode ver quantas vezes faltou durante a semana. Caso o usuário tenha informado que vai à academia, por exemplo, 3 vezes na semana e vá apenas 1, ele acumulará 2 faltas. Esse ranking cria uma dinâmica amigável de competição saudável entre os Moranguetes.

### 2. **Controle de Dívidas**

- **Registro de Dívidas**: Os Moranguetes podem registrar dívidas entre si, seja de compras, empréstimos ou outros compromissos financeiros. 

#### Funcionalidades:

- **Dividir Contas**: Caso um Moranguete pague por outro em uma situação de gasto conjunto, o sistema pode calcular quanto cada um deve e criar um histórico de pagamentos.

- **Notificação de Dívidas Pendentes**: O sistema pode alertar os membros quando uma dívida não for paga dentro de um determinado período, garantindo que ninguém se esqueça de acertar as contas.

- **Saldo devedor**: Cada Moranguete pode visualizar seu saldo devedor total, com um histórico das dívidas passadas e pagas.

## Como Usar

1. **Cadastre-se no Sistema**: Faça seu cadastro com um nome de usuário único e crie uma senha segura.
  
2. **Defina Suas Metas na Academia**: Ao se cadastrar, você poderá definir quantos dias por semana planeja ir à academia. Não se esqueça de atualizar sua frequência no calendário enviando fotos todos os dias!

3. **Adicione e Controle Dívidas**: Quando ocorrer qualquer tipo de dívida entre você e os outros Moranguetes, registre no sistema para que todos tenham o controle e consigam pagar o que devem.

4. **Acompanhe o Ranking e Se Mantenha Motivado**: Veja como está seu desempenho no ranking de faltas e divirta-se com a interação entre os Moranguetes. 

## Tecnologias Utilizadas

- **Frontend**: React.js para uma interface intuitiva e responsiva.
- **Backend**: Node.js com Express para gerenciamento de dados e autenticação.
- **Banco de Dados**: MongoDB para armazenar dados de usuários, presenças e dívidas.
- **Armazenamento de Imagens**: AWS S3 para armazenar as fotos enviadas pelos usuários.
- **Autenticação**: JWT para segurança nas sessões de usuário.

## Contribuições

Se você tem sugestões de funcionalidades, melhorias ou gostaria de contribuir para o desenvolvimento da Estufa, fique à vontade para abrir uma *issue* ou *pull request* no repositório.

## Licença

Este projeto é licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

**Estufa** foi criada para manter os **Moranguetes** motivados e organizados, seja no treino ou nas finanças entre amigos. Bora juntos nessa jornada! 💪🍓
