# labai-900 - Criando um modelo de previsão:

## _Para criar, implantar e testar um modelo de previsão, eu segui os passos descritos em [Microsoft aprenda](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)_

### Sessões:

- Crie um espaço de trabalho do Azure Machine Learning
- Use aprendizado de máquina automatizado para treinar um modelo
- Avalie o melhor modelo 
- Implantar e testar o modelo
- Testar o serviço implantado

#### Para testar o serviço utilizei o JSON:

```JSON
{
  "Inputs": {
    "data": [
      {
        "day": 1,
        "mnth": 1,
        "year": 2022,
        "season": 2,
        "holiday": 0,
        "weekday": 1,
        "workingday": 1,
        "weathersit": 2,
        "temp": 0.3,
        "atemp": 0.3,
        "hum": 0.3,
        "windspeed": 0.3
      }
    ]
  },
  "GlobalParameters": 1.0
}

```
#### Resultado:
```JSON

{
  "Results": [
    334.1789496520687
  ]
}
```
