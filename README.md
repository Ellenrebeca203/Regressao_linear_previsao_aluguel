# Regressao_linear_previsao_aluguel_P8

## OBJETIVO DO PROJETO:
Prever valor do aluguel através do modelo de Machine Learning Regressão Linear

## DADOS DO DATASET:
- Valor_Aluguel : valor Total pago no aluguel
- Valor_Condominio : Valor do Condomínio.
- Metragem : Metragem do Apartamento.
- N_Quartos : Número de Quartos do Imóvel.
- N_banheiros : Número de banheiros.
- N_Suites : Número de Suítes.
- N_Vagas : Número de Vagas.

## ETAPAS DO PROJETO: 
**Etapa 1: Primeira etapa de pré-processamento dos dados**
- Verificação dos tipos de dados
- Verifique os dados faltantes e tratamento

**Etapa 2: Segunda etapa de pré processamento dos dados**
- Utilição da função describe para identificarmos outliers e verificar a distribuição dos dados.
- Análise e tratamento desses dados
- Realização da análise bivariada dos dados com gráficos

**Etapas 3: Terceira etapa de pré processamento dos dados**
- Análise de correlação. Utilização de gráficos para identificação de variáveis aparentemente mais fortes para o modelo

**Etapa 4: Treinamento do modelo de Regressão Linear Simples e Múltipla**
- Treinamento de Regressão Simples com uma variável independente
- Aplicação do modelo de regressão linear multipla com todas as variáveis independentes

**Etapa 5: Validação de modelo**
- Valor do Coeficiente de Determinação (R quadrado) e avaliação do valor encontrado
- Validação do modelo com métricas
- Comparação das métricas entre os dois modelos

## CONCLUSÃO:
O quadrado da Regressão Linear Simples para os dados de teste foi de 0.53, enquanto que na Múltipla foi de 0.63, isso pode ter ocorrido pois as variáveis em conjunto podem responder melhor a variável Target, tendo mais influência nela do que apenas uma única variável.
