# Integrantes

- Pedro Henrique dos Santos RM559064
- Thiago Thomaz RM 557992

-----------------------

## Arquivos Necessarios para serem baixados

https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption
https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction

## Dataset 1

O conjunto de dados utilizado é o **Individual household electric power consumption Data Set**, que contém medições de consumo de energia elétrica em uma residência, registradas em intervalos de um minuto durante quase 4 anos.  

**Link para download do dataset:** [Individual household electric power consumption](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)

### Descrição das colunas

O arquivo contém as seguintes colunas:

| Coluna                     | Descrição                                                                 |
|-----------------------------|---------------------------------------------------------------------------|
| Date                        | Data da medição (formato: dd/mm/yyyy)                                     |
| Time                        | Hora da medição (formato: hh:mm:ss)                                       |
| Global_active_power         | Potência ativa global (em kilowatts)                                      |
| Global_reactive_power       | Potência reativa global (em kilowatts)                                    |
| Voltage                     | Tensão da rede elétrica (em volts)                                        |
| Global_intensity            | Intensidade global da corrente (em amperes)                               |
| Sub_metering_1              | Medição do submedidor 1 (cozinha)                                         |
| Sub_metering_2              | Medição do submedidor 2 (lavanderia)                                      |
| Sub_metering_3              | Medição do submedidor 3 (aquecimento e ar-condicionado)                   |

**Observações importantes:**

- As medições foram feitas a cada minuto.
- Alguns valores podem estar ausentes ou nulos (`?` no arquivo original).

---

## Dataset 2

**Descrição:**  
Este dataset contém medições de consumo de energia de aparelhos domésticos em intervalos de 10 minutos, juntamente com variáveis ambientais internas e externas, permitindo análise e previsão de consumo.

**Link para download:** [Appliances energy prediction](https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction)

### Colunas do dataset

O dataset inclui:

### Colunas do dataset Appliances Energy Prediction

| Coluna        | Papel     | Tipo        | Descrição                                   | Unidade  | Valores ausentes |
|---------------|----------|------------|--------------------------------------------|----------|----------------|
| date          | Feature  | Date       | Data e hora da medição                      | -        | não            |
| Appliances    | Target   | Integer    | Consumo total de energia dos aparelhos      | Wh       | não            |
| lights        | Feature  | Integer    | Consumo de energia das luzes                | Wh       | não            |
| T1            | Feature  | Continuous | Temperatura do escritório                   | °C       | não            |
| RH_1          | Feature  | Continuous | Umidade relativa do escritório             | %        | não            |
| T2            | Feature  | Continuous | Temperatura da cozinha                       | °C       | não            |
| RH_2          | Feature  | Continuous | Umidade relativa da cozinha                 | %        | não            |
| T3            | Feature  | Continuous | Temperatura do sala de lavanderia           | °C       | não            |
| RH_3          | Feature  | Continuous | Umidade relativa do sala de lavanderia     | %        | não            |
| T4            | Feature  | Continuous | Temperatura da sala de estar                | °C       | não            |
| RH_4          | Feature  | Continuous | Umidade relativa da sala de estar          | %        | não            |
| T5            | Feature  | Continuous | Temperatura do quarto 1                      | °C       | não            |
| RH_5          | Feature  | Continuous | Umidade relativa do quarto 1               | %        | não            |
| T6            | Feature  | Continuous | Temperatura do quarto 2                      | °C       | não            |
| RH_6          | Feature  | Continuous | Umidade relativa do quarto 2               | %        | não            |
| T7            | Feature  | Continuous | Temperatura do banheiro                      | °C       | não            |
| RH_7          | Feature  | Continuous | Umidade relativa do banheiro               | %        | não            |
| T8            | Feature  | Continuous | Temperatura da sala de jantar               | °C       | não            |
| RH_8          | Feature  | Continuous | Umidade relativa da sala de jantar         | %        | não            |
| T9            | Feature  | Continuous | Temperatura da lavanderia externa           | °C       | não            |
| RH_9          | Feature  | Continuous | Umidade relativa da lavanderia externa     | %        | não            |
| T_out         | Feature  | Continuous | Temperatura externa                          | °C       | não            |
| Press_mm_hg   | Feature  | Continuous | Pressão atmosférica                          | mm Hg    | não            |
| RH_out        | Feature  | Continuous | Umidade relativa externa                     | %        | não            |
| Windspeed     | Feature  | Continuous | Velocidade do vento                          | m/s      | não            |
| Visibility    | Feature  | Continuous | Visibilidade                                 | km       | não            |
| Tdewpoint     | Feature  | Continuous | Ponto de orvalho                             | °C       | não            |
| rv1           | Feature  | Continuous | Variável de referência 1                     | -        | não            |
| rv2           | Feature  | Continuous | Variável de referência 2                     | -        | não            |
