# svg-map-minasgerais-br
Mapa de mesorregiões do Estado de Minas Gerais, Brasil.

Com exibição de dados variáveis a partir do Json.

Obs: A informação contida na propriedade "valor" é fictícia, gerada aleatóriamente para este exemplo.
```js
<script type="text/javascript">
  var ufs = [
    { "codigo": 11, "uf": "RO", "nome": "Rondonia", "valor": "" },
    { "codigo": 12, "uf": "AC", "nome": "Acre", "valor": "" },
    { "codigo": 13, "uf": "AM", "nome": "Amazonas", "valor": "" },
    { "codigo": 14, "uf": "RR", "nome": "Roraima", "valor": "" }, 
    { "codigo": 15, "uf": "PA", "nome": "Para", "valor": "" }, 
    { "codigo": 16, "uf": "AP", "nome": "Amapa", "valor": "5" }, 
    { "codigo": 17, "uf": "TO", "nome": "Tocantins", "valor": "" }, 
    { "codigo": 21, "uf": "MA", "nome": "Maranhao", "valor": "" }, 
    { "codigo": 22, "uf": "PI", "nome": "Piaui", "valor": "65" }, 
    { "codigo": 23, "uf": "CE", "nome": "Ceara", "valor": "" }, 
    { "codigo": 24, "uf": "RN", "nome": "Rio Grande do Norte", "valor": "" }, 
    { "codigo": 25, "uf": "PB", "nome": "Paraiba", "valor": "" }, 
    { "codigo": 26, "uf": "PE", "nome": "Pernambuco", "valor": "" }, 
    { "codigo": 27, "uf": "AL", "nome": "Alagoas", "valor": "" }, 
    { "codigo": 28, "uf": "SE", "nome": "Sergipe", "valor": "" }, 
    { "codigo": 29, "uf": "BA", "nome": "Bahia", "valor": "" }, 
    { "codigo": 31, "uf": "MG", "nome": "Minas Gerais", "valor": "2.999.950" }, 
    { "codigo": 32, "uf": "ES", "nome": "Espirito Santo", "valor": "" }, 
    { "codigo": 33, "uf": "RJ", "nome": "Rio de Janeiro", "valor": "5" }, 
    { "codigo": 35, "uf": "SP", "nome": "Sao Paulo", "valor": "7" }, 
    { "codigo": 41, "uf": "PR", "nome": "Parana", "valor": "9" }, 
    { "codigo": 42, "uf": "SC", "nome": "Santa Catarina", "valor": "12" }, 
    { "codigo": 43, "uf": "RS", "nome": "Rio Grande do Sul", "valor": "" }, 
    { "codigo": 50, "uf": "MS", "nome": "Mato Grosso do Sul", "valor": "" }, 
    { "codigo": 51, "uf": "MT", "nome": "Mato Grosso", "valor": "" }, 
    { "codigo": 52, "uf": "GO", "nome": "Goias", "valor": "" }, 
    { "codigo": 53, "uf": "DF", "nome": "Distrito Federal", "valor": "5" }
  ];
</script>
```
[Fonte: IBGE/UF](http://www.ibge.gov.br/home/geociencias/areaterritorial/principal.shtm)
```js
<script type="text/javascript">
  var meso = [
    { "codigo": "3111", "nome": "CAMPO DAS VERTENTES", "valor": "550" },
    { "codigo": "3106", "nome": "CENTRAL MINEIRA", "valor": "552" },
    { "codigo": "3103", "nome": "JEQUITINHONHA", "valor": "155" },
    { "codigo": "3107", "nome": "METROPOLITANA DE BELO HORIZONTE", "valor": "94" },
    { "codigo": "3101", "nome": "NOROESTE DE MINAS", "valor": "2.355" },
    { "codigo": "3102", "nome": "NORTE DE MINAS", "valor": "156.510" },
    { "codigo": "3109", "nome": "OESTE DE MINAS", "valor": "99" },
    { "codigo": "3110", "nome": "SUL/SUDOESTE DE MINAS", "valor": "236" },
    { "codigo": "3105", "nome": "TRIANGULO MINEIRO/ALTO PARANAIBA", "valor": "2.587" },
    { "codigo": "3104", "nome": "VALE DO MUCURI", "valor": "25" },
    { "codigo": "3108", "nome": "VALE DO RIO DOCE", "valor": "36" },
    { "codigo": "3112", "nome": "ZONA DA MATA", "valor": "879" }
  ];
</script>
```
[Fonte: IBGE/UF/MG/Mesorregioes](http://www.ibge.gov.br/home/geociencias/areaterritorial/principal.shtm)

[Fonte: Wikipedia](https://pt.wikipedia.org/wiki/Minas_Gerais)
