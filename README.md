📈 Ferramenta de Análise e Perfil de InvestimentoUma solução inteligente para mapeamento de ativos e definição de estratégias financeiras baseadas no perfil do investidor.Este projeto fornece uma estrutura de dados e lógica para organizar carteiras de investimentos e classificar investidores de acordo com sua tolerância a risco, horizontes de tempo e objetivos financeiros.📋 Funcionalidades PrincipaisMapeamento de Ativos: Organização detalhada de produtos financeiros (Tesouro Direto, CDB, Fundos de Investimento, Ações e FIIs).Análise de Perfil (Suitability): Questionário estruturado para classificar investidores em perfis:Conservador: Foco em preservação de capital.Moderado: Equilíbrio entre segurança e crescimento.Arrojado: Foco em maximização de retornos através de renda variável.Cálculo de Alocação: Sugestão de distribuição de ativos baseada no score obtido.🛠️ Estrutura dos DadosO projeto utiliza dois datasets principais (em formato CSV/Excel):ArquivoDescriçãoAPP.csvContém a base de produtos financeiros, categorias de ativos e regras de negócio da aplicação.Perfil de investimento.csvContém a lógica de pontuação e as perguntas para determinação do perfil do usuário.🚀 Como UtilizarSe você for integrar este projeto a uma aplicação Python (por exemplo, usando Pandas), pode seguir este exemplo:Pré-requisitosPython 3.8+Biblioteca PandasExemplo de CarregamentoPythonimport pandas as pd

# Carregando a base de ativos
df_ativos = pd.read_csv('FERRAMENTA.xlsx - APP.csv')

# Carregando a lógica de perfil
df_perfil = pd.read_csv('FERRAMENTA.xlsx - Perfil de investimento.csv')

# Exemplo: Filtrar apenas ativos de Renda Fixa
renda_fixa = df_ativos[df_ativos['Categoria'] == 'Renda Fixa']
print(renda_fixa)
📊 Regras de Negócio: Perfil de InvestimentoA ferramenta utiliza uma matriz de decisão baseada em:Conhecimento do mercado: Experiência prévia com ativos voláteis.Horizonte de tempo: Quanto tempo o investidor pretende manter o capital aplicado.Tolerância a perdas: Reação do investidor diante de uma queda de 10% ou mais no patrimônio.🤝 ContribuiçãoFaça um Fork do projeto.Crie uma Branch (git checkout -b feature/melhoria-perfil).Faça o Commit (git commit -m 'Adicionando novos ativos').Dê um Push (git push origin feature/melhoria-perfil).Abra um Pull Request.
