# Descrição do teste para a vaga de Software Developer

Na Eva temos 2 principais recursos do sistema: colaboradores e jornadas.

- Jornadas são sequências de ações a serem executadas pelo sistema.
- Ações são, por exemplo: envio de email, envio de mensagem no whatsapp, requisição para uma API xyz, etc.

## Problema 
Dado um colaborador e uma jornada já criadas, crie uma API rest que permita associar uma jornada e uma data de início a um colaborador já cadastrado. Uma vez associada a jornada, as ações devem ser executadas por um job em background.

Para o frontend, o básico é conseguir realizar a ação de disparar a jornada para o colaborador. Fique à vontade para incrementar onde necessário.

#### Direcionamentos
- A definição dos modelos de colaborador e jornada fica a seu critério
- Não precisa se preocupar com o CRUD completo dos recursos, crie de acordo com sua necessidade
- As ações não precisam fazer chamadas reais a APIs, pode mockar o que for preciso

#### Pontos de avaliação
- Definição dos modelos/schemas
- Organização do projeto (arquivos e arquitetura)
- Clareza do código
- Testes unitários
- Documentação

## Entregável
Espero um sistema funcional e documentado em:
- como executar localmente
- como executar os testes unitários
- setups específicos necessários para a execução
- [OPCIONAL] se tiver o sistema rodando em alguma cloud é bônus, mas **não é requisito**

#### Informações sobre o nosso contexto
- Usamos arquitetura hexagonal
- Usamos bastante programação funcional e Promises/asyncs do Javascript
- Tecnologias/bibliotecas que utilizamos
  - MongoDB
  - [Joi](https://joi.dev/) pra validação de schemas
  - [BullJS](https://github.com/OptimalBits/bull) para jobs em background
  - Jest
  - React (componentes funcionais, React hooks) + [TailwindCSS](https://v2.tailwindcss.com/)
  - [TailwindUI](https://tailwindui.com/components) para biblioteca de componentes para o frontend
