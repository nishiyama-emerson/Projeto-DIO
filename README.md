# Projeto-DIO
Desafio de criar um NotebookLM sobre assunto financeiro introdutório do Bootcamp N8N Santander Open Academy 2026

# Link do NotebookLM
https://notebook.google.com/notebook/471b5c05-f4f3-432f-bd2c-568824e714b5

# Finanças Pessoais: Guia Introdutório

Este projeto é um guia prático e simplificado para quem deseja entender os conceitos fundamentais da educação financeira, organizar seu orçamento e dar os primeiros passos no universo dos investimentos.

# Objetivo:

- Apresentar conceitos básicos de educação financeira de forma acessível.
- Apresentar ferramentas simples (como planilhas e checklists) para controle financeiro.
- Organização do orçamento pessoal.

# Fontes:

1- https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Cuidando_do_seu_dinheiro_Gestao_de_Financas_Pessoais/caderno_cidadania_financeira.pdf
2- https://fia.com.br/blog/financas-pessoais/
3- https://riconnect.rico.com.vc/blog/financas-pessoais/
4- https://www.contabilizei.com.br/contabilidade-online/9-dicas-para-organizar-suas-financas-pessoais/
5- https://contaazul.com/blog/controle-financeiro-pessoal/

# Engenharia de Prompts & Troubleshooting

    ### Tabela de Prompts
      
      * Prompt1: Explique o que é a regra 50/15/35.
      * Resposta: Resposta muito genérica e teórica.
      * Dificuldades: Falta de contexto prático e ausência de exemplos reais. Ele até sugere quais despesas dar prioridade em cada regra, porém não faz uma simulação ou um exemplo prático.

      * Prompt2: Explique a regra 50/15/35 para um estudante universitário com renda de R$ 2.000.
      * Resposta: Resposta prática, com divisão exata dos valores (R$ 1000 / R$ 300 / R$ 700).
      * Comparativo Prompt1 vs Prompt2: Com um prompt mais específico (Prompt2), a resposta foi mais explicativa, com exemplo prático de como dividir o orçamento de R$2.000,00. Além disso, a reposta dá uma observação de que com a estrutura apresentada na resposta do Prompt2 é possível o estudante a cobrir os custos fixos e guardar dinheiro para o futuro sem precisar abrir mão do lazer durante a faculdade. E também pergunta se o usuário quer que monte uma estratégia de investimento com os R$300, que seriam destinados à quitações  de dívidas, caso não tenha nenhuma dívida. 

     ### Solução

       Refinar o mesmo prompt, porém especificando uma persona e sua renda como exemplo. Ao invés de utilizar o prompt1 no primeiro teste, o Prompt2 foi refinado para que ele explicasse o conceito da Regra 50/15/35 para um estudante com uma determinada renda mensal, como se a IA fosse um professor/consultor financeiro técnico e direto.

# Miniguia de Estudo

Este guia consolidado reúne os conceitos fundamentais sobre finanças pessoais, um glossário com os principais termos do mercado e uma biblioteca de prompts para estudos futuros.

    ### Organização & Orçamento
      - Mapeamento de Fluxo de Caixa: Entendimento claro entre Receitas(entradas) e Despesas(saídas).
      - Classificação de Gastos:
        - Fixos: Contas previsíveis com pouca variação (ex.: aluguel, condomínio).
        - Variáveis: Gastos flutuantes ajustáveis no curto prazo (ex.: lazer, alimentação fora).
      - Método 50/35/15: Divisão pragmática da renda líquida:
        - 50%: Necessidades (Essencial)
        - 15%: Objetivos Financeiros (Reserva e investimentos)
        - 35%: Desejos Pessoais (Lazer e estilo de vida)     

    ### Introdução aos Investimentos
      - Opções de Investimentos: Apresentação e foco em Renda Fixa
      - Renda Fixa: O investidor "empresta" dinheiro a uma instituição (Governo, Banco ou Empresa) em troca de uma rentabilidade pré ou pós-fixada.
      - Trinômio dos Investimentos:Relação direta entre Risco, Retorno e Liquidez (não é possível maximizar os três simultaneamente).

    ### Estratégia a Curto e Médio prazo
      - Orientação de um Fundo de Reserva: Construir uma reserva de emergência em opções de baixo risco e alta liquidez para cobrir imprevistos.
      - Estratégia do "Pague-se Primeiro": Programar uma aplicação automática para manter a consistência do investimento.
      - O que evitar: Aconselha a evitar investimento em Poupança, por causa do baixo rendimento, e apostas em BETS e Criptomoedas, pois não são modalidades de investimento e apresentam alto risco de perda do patrimônio.

  ## Glossário de Conceitos Chave
    
    - "Taxa Selic": A taxa básica de juros da economia brasileira, definida pelo Banco Central. Serve de referência para todas as outras taxas.
    - "CDI (Certificado de Depósito Interbancário)": Taxa de juros praticada entre os bancos que serve de referência de rentabilidade para a maioria dos investimentos em Renda Fixa. 
    - "Liquidez": A velocidade e facilidade com que você consegue transformar um investimento de volta em dinheiro na sua conta. 
    - "Inflação (IPCA)": O aumento generalizado de preços que reduz o poder de compra do dinheiro ao longo do tempo. 
    - "Diversificação": Estratégia de distribuir os recursos em diferentes ativos para reduzir o risco geral da carteira. 

  ## Biblioteca de Prompts Reutilizáveis para Estudos

    1- "Atue como um educador financeiro didático. Explique o conceito de [INSERIR CONCEITO, ex: Taxa Selic] para uma pessoa leiga, utilizando uma analogia do dia a dia e evitando jargões técnicos. Ao final, apresente um exemplo numérico simples."
    2- "Atue como um especialista em orçamento pessoal. Eu ganho R$ [VALOR] por mês e tenho as seguintes despesas: [LISTAR DESPESAS E VALORES]. Aplique a regra 50/15/35 a este cenário, identifique gargalos onde posso cortar custos e sugira uma distribuição ideal para os meus objetivos."
    3- "Atue como um analista de investimentos. Crie uma tabela comparativa entre [ATIVO 1, ex: Tesouro Selic] e [ATIVO 2, ex: CDB 100% do CDI]. Compare: Liquidez, Risco, Tributação (Imposto de Renda), Rendimento esperado e Indicação de uso."
    
