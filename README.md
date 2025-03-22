# Detecção de Fraude - Standard Bank Moçambique

## Descrição do Projeto
Este projeto fictício foi desenvolvido para simular a criação de um sistema de **detecção de fraude** no setor bancário moçambicano, utilizando técnicas de aprendizado de máquina. A fraude financeira é um problema crescente, especialmente com a digitalização dos serviços bancários, tornando essencial a implementação de soluções tecnológicas para mitigar riscos. Este estudo busca demonstrar como modelos de machine learning podem ser aplicados para detectar padrões suspeitos em transações financeiras, contribuindo para a prevenção de fraudes e a segurança bancária.

O setor bancário em Moçambique tem passado por um processo de modernização, impulsionado pelo avanço das tecnologias financeiras e pelo aumento da inclusão digital. Com isso, instituições bancárias fictícias, como o "Standard Bank Moçambique" neste estudo, estão supostamente investindo em soluções inovadoras para detectar atividades fraudulentas e proteger seus clientes. Neste contexto, este projeto visa ilustrar a construção de modelos preditivos que poderiam ser utilizados para identificar transações suspeitas e minimizar perdas financeiras.

## Tecnologias Utilizadas
- **Linguagem:** Python
- **Bibliotecas principais:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Modelos testados:**
  - Regressão Logística
  - Decision Tree
  - Random Forest (com otimização de hiperparâmetros)

## Estrutura do Projeto
O projeto segue as seguintes etapas:
1. **Carregamento e exploração dos dados**: Análise exploratória para compreender padrões e possíveis desequilíbrios na base de dados.
2. **Pré-processamento**: Normalização, tratamento de valores ausentes e balanceamento dos dados para melhor desempenho dos modelos.
3. **Treinamento dos modelos**: Teste de diferentes algoritmos para identificar a melhor abordagem.
4. **Avaliação dos resultados**: Análise das matrizes de confusão e outras métricas para medir o desempenho dos modelos.
5. **Otimização do melhor modelo**: Ajuste fino dos hiperparâmetros do Random Forest para melhorar ainda mais a performance.

## Principais Resultados
As matrizes de confusão para cada modelo foram obtidas e indicaram o seguinte desempenho:

### Regressão Logística
| TP: 2588 | FP: 821  |
|----------|---------|
| FN: 933  | TN: 24407 |

### Decision Tree
| TP: 23760 | FP: 1649  |
|-----------|---------|
| FN: 406   | TN: 24934 |

### Random Forest (Antes da Otimização)
| TP: 24877 | FP: 532  |
|-----------|---------|
| FN: 874   | TN: 24476 |

Após a otimização dos hiperparâmetros do modelo **Random Forest**, os resultados melhoraram ainda mais, reduzindo significativamente os falsos positivos e falsos negativos, tornando-o a solução mais eficaz para a detecção de fraudes dentro deste estudo simulado.

## Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/fraud-detection.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o notebook para treinar os modelos e visualizar os resultados.

## Próximos Passos
- Continuar refinando o modelo Random Forest para aumentar ainda mais a precisão.
- Explorar outros algoritmos, como XGBoost e Redes Neurais.
- Simular uma possível implementação da solução em um ambiente de produção fictício.

---
Este projeto é uma simulação acadêmica e não representa um caso real do Standard Bank Moçambique ou de qualquer outra instituição financeira.



 
