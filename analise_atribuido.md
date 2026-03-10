# Análise do dataset atribuído - Consumption
Análise feita ao dataset atribuído sobre consumo (consumption), antes de depois dos dados serem devidamente tratados.

## Resultados antes do tratamento
Antes de qualquer tratamento de dados, haviam 8736 linhas para usar.

### Date/Time
- É lido como uma `String`
- Não tem missing values
- Não tem valores duplicados (são todos únicos)
- Formato: `AAAA-MM-DD HH:MM:SS`
- O valor dos minutos e dos segundos é sempre `00`, logo os intervalos de tempo são de 1 hora

> **Tratamento:** Converter a coluna para um formato de data e hora apropriados (se possível sem minutos ou segundos). Eventualmente descartar os valores de minutos e segundos, já que são sempre `00`.

---

### Very High Voltage (kWh)
- É lido como um `Float`
- Tem missing values (**919**) (valor não existente)
- Min: **0**
- Max: **102237.245225**
- Média: **72973.42748490183**
- Distribuição Normal (+/-)

> **Tratamento:** O melhor a fazer será substituí-los pela média ou mediana da coluna. Contudo a variação é muito grande talvez não seja o mais correto (falar com o professor).

---

### High Voltage (kWh)
- É lido como um `Float`
- Tem missing values (**844**) (valor não existente)
- Min: **21141.178325**
- Max: **242378.063775**
- Média: **197751.3912339391**
- Distribuição Normal (+/-  Mais concentrada no final)

> **Tratamento:** O melhor a fazer será substituí-los pela média ou mediana da coluna. Como a variação é relativamente pequena não devará ser um problema (falar com o professor).

---

### Medium Voltage (kWh)
- É lido como uma `String`
- Tem missing values representados por `nan`

> **Tratamento:** Converter a coluna para um formato numérico apropriado (`Float`). Substituir os missing values (`nan`) pela média ou mediana da coluna (em princípio). Temos de verificar depois esses valores antes da substituição para perceber se a variação é grande ou pequena e escolher a melhor opção.

---

### Low Voltage (kWh)
- É lido como um `Float`
- Tem missing values (**875**) (valor não existente)
- Min: **676.0027515**
- Max: **1615625.90223325**
- Média: **779487.2213085972**
- Distribuição Normal (+/-)

> **Tratamento:** O melhor a fazer será substituí-los pela média ou mediana da coluna. Contudo a variação é muito grande talvez não seja o mais correto (falar com o professor).

---

### Total (kWh)
- É lido como uma `String`
- Tem missing values representados por `nan`

> **Tratamento:** Converter a coluna para um formato numérico apropriado (`Float`). Substituir os missing values (`nan`) pela média ou mediana da coluna (em princípio). Temos de verificar depois esses valores antes da substituição para perceber se a variação é grande ou pequena e escolher a melhor opção.

---

### temperature_2m (°C)
- É lido como um `Float`
- Tem missing values (**828**) (valor não existente)
- Min: **2.1**
- Max: **43.2**
- Média: **17.90498229640868**
- Distribuição Normal (+/-)

> **Tratamento:** O melhor a fazer será substituí-los pela média ou mediana da coluna. Como a variação é relativamente pequena não devará ser um problema (falar com o professor).

---

### relative_humidity_2m (%)
- É lido como um `Float`
- Tem missing values (**892**) (valor não existente)
- Min: **10**
- Max: **100**
- Média: **	68.46545130035669**
- Distribuição Linear

> **Tratamento:** O melhor a fazer será substituí-los pela média ou mediana da coluna. Como a variação é relativamente pequena não devará ser um problema. Outra opção é assumirmos que o valor será `0` (falar com o professor).

---

### precipitation (mm)
- É lido como um `Float`
- Tem missing values (**7747**) (valor não existente)
- Min: **0.1**
- Max: **10.2**
- Média: **0.7811931243680487**
- Distribuição Assimétrica (muitos valores próximos de `0` e poucos valores mais altos)

> **Tratamento:** Neste caso acho que podemos assumir que os missing values correspondem a `0`, ou seja ausência de precipitação (falar com o professor).

---

### apparent_temperature (°C)
- É lido como um `Float`
- Tem missing values (**845**) (valor não existente)
- Min: **-1.4**
- Max: **43**
- Média: **16.594335318717548**
- Distribuição Normal (+/-)

**Nota:** Existe uma correlação (+1) muito forte com a coluna `temperature_2m`, possível caso de ambiguidades (falar com o professor).

> **Tratamento:** O melhor a fazer será substituí-los pela média ou mediana da coluna. Como a variação é relativamente pequena não devará ser um problema (falar com o professor).

---

### rain (mm)
- É lido como um `Float`
- Tem missing values (**7755**) (valor não existente)
- Min: **0.1**
- Max: **10.2**
- Média: **0.7731906218144741**
- Distribuição Assimétrica (muitos valores próximos de `0` e poucos valores mais altos)

**Nota:** Existe uma correlação (+1) **muito muito** forte com a coluna `precipitation`, possível caso de ambiguidades (falar com o professor).

> **Tratamento:** Neste caso acho que podemos assumir que os missing values correspondem a `0`, ou seja ausência de chuva (falar com o professor).

---

### snowfall (cm)
- É lido como um `Float`
- Tem missing values (**841**) (valor não existente)
- Min: **0**
- Max: **0**
- Média: **0**

> **Tratamento:** Neste caso acho que podemos assumir que os missing values correspondem a `0`, ou seja ausência de neve. Contudo como a coluna está completamente preenchida por `0` talvez seja melhor descartá-la (falar com o professor).

---

### cloud_cover (%)
- É lido como um `Float`
- Tem missing values (**885**) (valor não existente)
- Min: **0**
- Max: **100**
- Média: **43.245064323016265**
- Distribuição Assimétrica (muitos valores próximos de `0` e muitos valores próximos de `100`)

> **Tratamento:** O melhor a fazer será substituí-los pela média ou mediana da coluna. Como a variação é relativamente grande (pois é %) talvez seja melhor assumir que os missing values correspondem a `0` ou `100` (falar com o professor).

---

### surface_pressure (hPa)
- É lido como um `Float`
- Tem missing values (**874**) (valor não existente)
- Min: **965.8**
- Max: **1004.7**
- Média: **988.9970236581013**
- Distribuição Normal (+/-)

> **Tratamento:** O melhor a fazer será substituí-los pela média ou mediana da coluna. Como a variação é relativamente pequena não devará ser um problema.

---

### wind_speed_10m (km/h)
- É lido como um `Float`
- Tem missing values (**823**) (valor não existente)
- Min: **0**
- Max: **47.3**
- Média: **12.04866675091623**
- Distribuição Assimétrica (muitos valores próximos da esquerda (média))

> **Tratamento:** O melhor a fazer será substituí-los pela média da coluna.

---

### Diffuse_Radiation
- É lido como uma `String`
- Tem missing values (**891**) (valor não existente)
- Gama de valores (3):

    1. None (3704)
    2. Low (3694)
    3. Medium (447)

> **Tratamento:** Perguntar ao professor como podemos distribuir os valores.

---

### Direct_Radiation
- É lido como uma `String`
- Tem missing values (**863**) (valor não existente)
- Gama de valores (4):

    1. None (4205)
    2. Low (1836)
    3. Medium (1120)
    4. High (712)

> **Tratamento:** Perguntar ao professor como podemos distribuir os valores.

---

### wind_speed_100m (km/h)
- É lido como um `Float`
- Tem missing values (**905**) (valor não existente)
- Min: **0.4**
- Max: **74.5**
- Média: **19.999948920955177**
- Distribuição Assimétrica (muitos valores próximos da esquerda (média))

> **Tratamento:** O melhor a fazer será substituí-los pela média da coluna.

---

### wind_direction_10m (°)
- É lido como um `Float`
- Tem missing values (**895**) (valor não existente)
- Min: **1**
- Max: **360**
- Média: **227.83165412574928**
- Distribuição Linear (+/- Mais concentrada no final)

> **Tratamento:** O melhor a fazer será substituí-los pela média da coluna.

---

### wind_direction_100m (°)
- É lido como um `Float`
- Tem missing values (**882**) (valor não existente)
- Min: **0**
- Max: **360**
- Média: **225.71848739495826**
- Distribuição Linear (+/- Mais concentrada no final)

> **Tratamento:** O melhor a fazer será substituí-los pela média da coluna.

---

### wind_gusts_10m (km/h)
- É lido como um `Float`
- Tem missing values (**908**) (valor não existente)
- Min: **1.4**
- Max: **92.2**
- Média: **25.302248339294884**
- Distribuição Assimétrica (muitos valores próximos da esquerda (média))

> **Tratamento:** O melhor a fazer será substituí-los pela média da coluna.

---

### terrestrial_radiation (W/m²)
- É lido como um `Float`
- Tem missing values (**869**) (valor não existente)
- Min: **0**
- Max: **1279.7**
- Média: **337.3013728231845**
- Distribuição Assimétrica (muitos valores entre 0 e 128, cerca de 50%)

> **Tratamento:** O melhor a fazer será substituí-los por valores mais próximos do intervalo `[0, 128]` (falar com o professor).

---

### Consumption
- É lido como uma `String`
- Não tem missing values (13):
    
    1. Medium Consumption (2085)
    2. Low Consumption (1994)
    3. Medium-High Consumption (2173)
    4. High Consumption (788)
    5. Medium-Low Consumption (1671)
    6. Lw (4)
    7. MedLow (2)
    8. Hgh (2)
    9. Medium (3)
    10. MedioBaixo (3)
    11. MedHgh (5)
    12. MedioAlto (3)
    13. Med (3)

> **Tratamento:** Como os valores de `6` até  `13` são variações dos valores de `1` até `5`, o melhor a fazer será substituir os valores de `6` até `13` pelos valores correspondentes de `1` até `5`.