# Projeto: Análise de Rotatividade de Clientes - Model Fitness 🏋️‍♀️📊

## Descrição do Projeto
A rede de academias **Model Fitness** busca desenvolver uma estratégia de interação com os clientes baseada em **dados analíticos** para enfrentar o desafio da **rotatividade de clientes**. Esse é um problema comum no setor de academias e serviços, onde identificar clientes que "saíram de fininho" pode ser complicado.

Este projeto tem como objetivo principal analisar os perfis de clientes, identificar padrões de comportamento e desenvolver estratégias para aumentar a retenção.

---

## Objetivos do Projeto
1. **Predição da Probabilidade de Rotatividade**:
   - Desenvolver um modelo que estime a probabilidade de um cliente abandonar a academia no mês seguinte.

2. **Segmentação de Clientes**:
   - Criar retratos de usuários típicos, selecionando os grupos mais marcantes e descrevendo suas principais características.

3. **Análise de Fatores de Rotatividade**:
   - Investigar os fatores que mais influenciam a saída de clientes.

4. **Recomendações Estratégicas**:
   - Desenvolver sugestões para reduzir a rotatividade, como identificar grupos-alvo e propor melhorias no serviço.

---

## Metodologia
A análise foi conduzida utilizando os dados digitalizados dos perfis dos clientes. As principais etapas incluem:
1. **Análise Exploratória de Dados (AED)**:
   - Identificar padrões gerais e possíveis anomalias nos dados.
2. **Mapas de Calor e Visualizações**:
   - Analisar discrepâncias no comportamento entre clientes com rotatividade e os demais.
3. **Construção de Modelos Preditivos**:
   - Aplicação de algoritmos de machine learning para prever a rotatividade.
4. **Segmentação e Clusterização**:
   - Agrupamento de clientes para melhor entendimento de perfis comportamentais.
5. **Testes Estatísticos**:
   - Avaliar a significância de diferenças nos comportamentos dos grupos com alta rotatividade.
6. **Insights e Recomendações**:
   - Interpretação dos resultados para formular estratégias práticas de retenção.

---

## Resultados do Estudo
Com base na análise, os principais resultados obtidos foram:
- Observou-se uma discrepância significativa no comportamento de clientes com **alta rotatividade (churn)** em comparação aos demais. Os usuários que apresentaram maior probabilidade de rotatividade foram agrupados nos **grupos 0 e 3**.
- Perfis predominantes nos grupos de alta rotatividade:
  - Idade entre **25 e 32 anos**.
  - Não são funcionários de empresas parceiras.
  - Não participam de **sessões de grupo**.
- Identificou-se que uma **frequência alta nas primeiras semanas** é um forte indicativo de manutenção de frequência ao longo do tempo.

### Recomendações
Para reduzir a rotatividade, sugerimos as seguintes ações para a equipe de marketing:
1. **Estudar os perfis dos usuários com alta rotatividade** e desenvolver campanhas que motivem o engajamento já nas primeiras semanas de adesão.
2. **Promover sessões de grupo** como parte dos pacotes de adesão.
3. **Expandir parcerias corporativas** para atrair clientes que tendem a ter maior retenção.
4. Oferecer **incentivos e promoções** para estimular o uso contínuo dos serviços.

---

## Tecnologias Utilizadas
- **Linguagem de Programação**: Python
- **Bibliotecas**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Ambiente de Desenvolvimento**: Jupyter Notebook

---

## Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu_usuario/seu_repositorio.git
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o Jupyter Notebook principal:
   ```bash
   jupyter notebook rotatividade_clientes.ipynb
   ```

---

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma **issue** ou enviar um **pull request** com melhorias ou sugestões.

---

## Licença
Este projeto está licenciado sob a [Licença MIT](LICENSE).

---

## Contato
- **Autor**: [Danilo José](https://www.linkedin.com/in/danilojosedelara/)
- **Email**: lara.danilo25@email.com

