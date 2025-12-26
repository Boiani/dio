Ferramenta de Análise e Perfil de InvestimentoUma solução inteligente para mapeamento de ativos e definição de estratégias financeiras baseadas no perfil do investidor.Este projeto fornece uma estrutura de dados e lógica para organizar carteiras de investimentos e classificar investidores de acordo com sua tolerância a risco, horizontes de tempo e objetivos financeiros.
Funcionalidades Principais
  Mapeamento de Ativos: Organização detalhada de produtos financeiros (Tesouro Direto, CDB, Fundos de Investimento, Ações e FIIs).
  Análise de Perfil (Suitability): Questionário estruturado para classificar investidores em perfis:
    Conservador: Foco em preservação de capital. 
    Moderado: Equilíbrio entre segurança e crescimento. 
    Arrojado: Foco em maximização de retornos através de renda variável.
  Cálculo de Alocação: Sugestão de distribuição de ativos baseada no score obtido.
Estrutura dos Dados: O projeto utiliza dois datasets principais (em formato CSV/Excel):
  APP: Contém a base de produtos financeiros, categorias de ativos e regras de negócio da aplicação.
  Perfil de investimento: Contém a lógica de pontuação e as perguntas para determinação do perfil do usuário.
Como Utilizar: Se você for integrar este projeto a uma aplicação Python (por exemplo, usando Pandas), pode seguir este exemplo: Pré-requisitosPython 3.8+Biblioteca PandasExemplo de CarregamentoPythonimport pandas as pd
