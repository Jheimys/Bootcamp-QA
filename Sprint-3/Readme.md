# Sprint 3 – Projeto: Testes da Funcionalidade de Compartilhamento de Carros – Urban Routes

> Projeto prático de QA: preparação e execução de testes funcionais para o carsharing do Urban Routes, contemplando checklist visual, análise funcional e execução multiplataforma.

---

## Descrição do Projeto

No Sprint 3, o foco é **testar a funcionalidade de compartilhamento de carros** do Urban Routes, avaliando tanto o layout quanto o funcionamento dos principais fluxos do formulário de reserva e pagamento. A execução deve ocorrer tanto no Google Chrome (800x600) quanto no Firefox (1920x1080).

---

## Artefatos da Entrega

- **Google Sheets** contendo todas as etapas e checklists exigidos.
- **Google Docs** reunindo links dos artefatos, resultado dos testes, evidências visuais e relatórios de bug.
- Permissão de acesso liberada para revisão.

---

## Ambientes de Teste Utilizados

- Google Chrome – resolução 800x600
- Firefox – resolução 1920x1080

---

## Evidências Visuais

<p align="center">
  <img src="https://github.com/Jheimys/assets/blob/master/sp4-UR.png" alt="Urban Routes – Layout do Compartilhamento de Carro" width="900"/>
</p>

---

## Etapas do Projeto

### 1️⃣ Checklist do Layout do Formulário de Reserva

- Verificação da ortografia, disposição dos elementos e aparência geral.
- Checagem do mapa de navegação na interface central.
- Teste dos pop-ups:
  - Carro reservado
  - Confirmação de cancelamento ("Você tem certeza que quer cancelar sua viagem?")
  - Viagem cancelada
- **Resultado:** Checklist completo na aba "1. Checklist do layout" do Sheets.

---

### 2️⃣ Checklist de Funcionalidade: Métodos de Pagamento e Adição de Cartão

- Criação do checklist orientado por classes de equivalência e valores-limite.
- Cobertura de testes positivos e negativos.
- Registro na aba "2. Checklist para 'Método de pagamento' e 'Adicionar cartão'".

---

### 3️⃣ Casos de Teste para Botão "Reservar"

- Análise da seção de requisitos para o botão "Reservar".
- Ênfase em cenários positivos/negativos, incluindo validação do texto (distância/tempo) exibido.
- Registro dos cenários na aba "3. Casos de teste para o botão 'Reservar'".
- **Obs:** Não testar cálculo exato de tempo/distância, nem cronômetro do tempo de espera gratuito.

---

### 4️⃣ Casos de Teste para Locação de Carro

- Verificação dos fluxos de locação conforme requisitos ("Reservar carro").
- Cobertura dos cenários esperados e de exceção.
- Registro completo na aba "4. Casos de teste para locação".

---

### 5️⃣ Execução dos Testes e Relatório de Bugs

- Teste do layout em ambos os ambientes definidos.
- Teste da lógica do aplicativo em um dos ambientes.
- Avaliação de resultados: testes marcados como APROVADO ou REPROVADO, conforme resultado.
- Registro de bugs reprovados no Jira, com inserção dos links na planilha correspondente.

---

## Resultados Esperados

- Confirmação da aderência do aplicativo aos requisitos de layout e funcionalidade de carsharing.
- Registro claro dos bugs identificados e linkados ao Jira para correção futura.
- Evidências visuais e documentais de execução dos testes conforme padrões do QA moderno.

---

## Próximos Passos

- Anexar todos os artefatos (Google Sheets, Google Docs, links de relatórios) na plataforma e liberar acesso.
- Concluir a entrega na aba "Revisar" da lição correspondente.
- Preparação para feedback e eventuais ajustes com base nos resultados.

---

## Status do Projeto

Em execução para validação das funcionalidades centrais do carsharing ✔

