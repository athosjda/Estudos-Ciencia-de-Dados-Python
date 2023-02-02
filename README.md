# Tratamento de Dados

Tratar dados 'tempo.csv'

- Aparência: sol, nublado, chuva
- Temperatura: -135F à 130F
- Umidade: 0 à 100
- Vento: Verdadeiro/Falso
- Jogar: sim/nao

Tratar valores Nulos

### Outliers

Neste exemplos as *outliers* são tratadas como **erros**, isso não equivale para todo o universo em uma analise já que a caracteristica de um dado se qualificar como outlier é ele se diferenciam drasticamente dos demais.

Ela deve ser analisada de forma minunciosa já que a mesma pode causar anomalias nos resultados obtidos por meio de algoritmos e sistemas de análise. Buscar entender por onde se deu aquele valor é fundamental peos os aspectos:
- Os outliers podem viesar negativamente todo o resultado de uma análise;
- O comportamento dass *outliers* pode ser justamente o que está sendo procurado.

Há outras maneira de identificação de *outliers* além da citada na analise de forma extremamente simple e simplificada que é o método pelo o **limite de Tukey**.
