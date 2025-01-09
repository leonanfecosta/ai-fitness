![image](https://github.com/user-attachments/assets/746adaab-ca47-4d3c-b24c-c1fdf3eba25a)

## Funcionalidades Principais ⚙️ 

### 1. Exibição dos Dados dos Usuários
A aplicação permite visualizar os dados de cada usuário, incluindo:
- Lista de fotos enviadas.
- Percentual de presença na academia nos últimos três meses.
- Informações sobre descontos já recebidos.
- Outros dados relevantes para a análise.

### 2. Botão de Simulação da IA
Na página do usuário, há um botão chamado "Simular Interação com a IA", que representa a decisão da IA baseada nos dados atuais do usuário. Na aplicação real, essa interação ocorreria automaticamente.

## As Funções de Desconto 🎁
Definimos quatro funções que a IA pode chamar, dependendo do nível de engajamento do usuário:

- **Oferecer Desconto na Primeira Aula**:
  - Para usuários desengajados.
  - Oferece um desconto significativo na primeira aula com um personal trainer.

- **Oferecer Desconto no Plano Anual**:
  - Para usuários altamente engajados.
  - Oferece um desconto no plano anual de personal trainer.

- **Motivar Envio de Fotos**:
  - Para usuários desengajados.
  - Incentiva o usuário a enviar cinco fotos consecutivas para ganhar um desconto.

- **Atualizar Campanha de Engajamento**:
  - Verifica se o usuário está cumprindo os requisitos da campanha (por exemplo, enviando as fotos).
  - Atualiza o progresso e decide se o desconto deve ser concedido.

## Como as Funções Operam

- **Atualização de Dados**: Cada função modifica os dados do usuário, registrando informações como descontos oferecidos ou progresso em campanhas.
- **Mensagens para a IA**: As funções retornam mensagens que a IA pode usar para comunicar o resultado ou próximo passo ao usuário.

## Integração com a IA Generativa 🧠
A IA será responsável por:
- Analisar os dados do usuário.
- Decidir qual função chamar com base nos dados.
- Chamar a função adequada para executar a ação necessária.
- Comunicar-se com o usuário através de mensagens claras e úteis.


## Considerações Importantes 📝
- **Tipagem das Funções**: Certifique-se de que todas as funções têm parâmetros e retornos bem definidos e tipados, para que a IA possa utilizá-las corretamente.
- **Mensagens Claras**: As funções devem retornar mensagens que a IA possa usar para interagir com o usuário de forma eficaz.
- **Controle de Fluxo**: Implementar lógica para evitar que descontos sejam oferecidos repetidamente ao mesmo usuário, conforme necessário.
