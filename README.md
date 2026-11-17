# Previsão de risco de doença cardiovascular

> 🚧 **Em desenvolvimento.** Projeto final da trilha *Data Science & Machine Learning* da [Asimov Academy](https://asimov.academy), refeito por mim do zero.

## Problema

Prever se um paciente tem doença cardiovascular a partir de dados de um exame de rotina: idade, sexo, altura, peso, pressão arterial (sistólica e diastólica), colesterol, glicose e hábitos (fumo, álcool, atividade física). É uma **classificação binária** (coluna `cardio`).

## Perguntas que o projeto responde

- Quais atributos mais influenciam o risco?
- Qual modelo classifica melhor, e com que métrica isso deve ser medido num contexto de saúde (onde um falso negativo custa mais)?
- Como explicar a previsão de um paciente específico?

## Dados

`cardio_train.csv` (~70 mil pacientes), fornecido no material do curso. Os dados não são versionados: coloque o arquivo em `data/`.

## Resultados

| Experimento | Métrica | Resultado |
|---|---|---|
| — | — | — |

## Estrutura

```
data/        dados (não versionados)
notebooks/   NN-sanjos-<descrição>.ipynb
reports/     resultados.md: registro de análises e experimentos
```

As seções dos notebooks seguem as etapas do checklist de projeto de Machine Learning (Géron).

## Como reproduzir

```bash
python3 -m venv .venv && source .venv/bin/activate
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook notebooks/
```
