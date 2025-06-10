<h1 align='center'> Clareyamar X Tarrasque - Previsão do pH de amostras de água </h1>
<h3 align="center"><i>Inluminans Ignotus</i></h3>

<h3 align='center'> Previsão do pH de água a partir de dados da concentração de soluto dissolvido nas amostras utilizando uma rede neural MLP com o módulo PyTorch.</h4>

<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

![_Beige Medieval City Desktop Wallpaper](https://github.com/user-attachments/assets/aac17c75-806e-4130-b3eb-0e0960b2c9e2)

## 📝 Resumo do projeto

Como projeto final da disciplina de Redes Neurais e Algoritmos Genéticos, ministrada pelo Professor Daniel Roberto Cassar, o grupo formado pelos discentes Gabriel Martins, Maria Clara Lelis e Yasmin Shimizu, autoentitulados "Divisão Clareyamar", desenvolveu uma Rede Neural (RN) do tipo MLP para regressão utilizando o módulo Pytorch, a fim de prever o pH de amostras de água a partir de quantidades de diversos componentes químicos presentes nas amostras. Além disso, otimizamos os hiperparâmetros da rede MLP através do módulo optuna, que testa diferentes arquiteturas da rede, compara as métricas de performance dessas diferentes arquiteturas e retorna ao usuário os hiperparâmetros do modelo com a menor função de perda.

O dataset usado no projeto foi obtido na plataforma Kaggle, e se refere a caracteríısticas de amostras de água obtidos de vários distritos. Os dados foram coletados do Telangana Open Data portal, do estado de Telangana, na India. O conjunto que utilizamos é referente ao ano de 2018, e contém 26 colunas, como: número de série (sno), Distrito, Vila, Latitude, Longitude, Produtos Químicos (como Ca, Mg, CO3 etc.), Dureza total da água, Total de sólidos dissolvidos, e as variáveis-alvo do dataset 'Classificação' e 'Classificação1'. Para a nossa aplicação de previsão do pH, iremos utilizar apenas as colunas de: TDS, CO3, HCO3, Cl, F, NO3, SO4, Na, K, Ca, Mg, RSC meq / L e pH.

Separamos os dados em treino e teste, para verificar a performance do modelo que iremos aplicar. Porém, para a validação das diferentes arquiteturas testadas no processo de otimização, dividimos os dados de treino em treino e validação. Em seguida, testamos o melhor modelo encontrado nos dados de teste, e obtivemos sua métrica de performance. Ao final, obtivemos a curva de aprendizado do modelo, e comparamos os valores previstos com os reais. Além disso, classificamos os valores de pH entre: valores ideais para uso humano, valores abaixo do ideal e valores acima do ideal, segundo um documento da Organização Mundial da Saúde 

## ☀️🌊 Lore

## 🖇️Recursos Utilizados

<img src="https://github.com/user-attachments/assets/78c00970-b717-4c28-b086-a4b73a294a27" alt="Texto Alternativo" width="100">

<img src="https://github.com/user-attachments/assets/ad7a787e-678e-45a2-ac94-f045bc68990b" alt="Texto Alternativo" width="100">

<img src="https://github.com/user-attachments/assets/26e144d6-9a5d-4f45-a880-15a0d093f7d5" alt="Texto Alternativo" width="150">

<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/dd5953d4-0b62-467b-85ed-9a992d6c1511" alt="Texto Alternativo" width="101">

<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/025152bd-de97-420c-8a96-bf4d675bea31" alt="Texto Alternativo" width="101">

<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/314dcd00-784b-4f40-b361-a46329aad30e" alt="Texto Alternativo" width="145">

<img src="https://github.com/user-attachments/assets/379bd928-e479-427d-8d49-651a65dc1315" alt="Texto Alternativo" width="195">

<img src="https://github.com/user-attachments/assets/ac550461-c75f-40aa-ba05-6c9189de6825" alt="Texto Alternativo" width="103">

## 💧Data Set

Utilizamos no projeto o dataset Water Quality Data [Telangana Groundwater], obtido na plataforma *Kaggle*, um site de hospedagem de diversos datasets muito utilizado para obter dados para o treinamento de modelos de Machine Learning (ML). Os dados foram coletados do Telangana Open Data portal, do estado de Telangana, na India. Esses dados contêm amostras de água testadas de vários distritos. O conjunto que utilizamos é referente ao ano de 2018, e contém 26 colunas, como: número de série (sno), Distrito, Vila, Latitude, Longitude, Produtos Químicos (como Ca, Mg, CO3 etc.), Dureza total da água, Total de sólidos dissolvidos, e as variáveis-alvo do dataset 'Classificação' e 'Classificação1'. Para a nossa aplicação de previsão do pH, iremos utilizar apenas as colunas de: TDS, CO3, HCO3, Cl, F, NO3, SO4, Na, K, Ca, Mg, RSC  meq  / L e pH. É possível acessar a página do dataset no Kaggle [aqui](https://www.kaggle.com/datasets/sivapriyagarladinne/telangana-post-monsoon-ground-water-quality-data)

## ⚙️Redes Neurais MLP

## 🔢 Resultados

## 📔Acesso ao projeto
Os arquivos presentes nesse repositório são:

* <code>título do jupyter</code>:
* <code>título do dataset </code>:
* <code>README</code>: descrição geral do projeto

O Notebook com os códigos para execução da Rede Neural estão armazenados nesse repositório e podem ser rodados em compiladores de Python como Jupyter Notebook, Visual Studio Code e Google Colab. Tanto a tabela de dados utilizados quanto o link para o site de armazenamento do dataset estão também neste repositório, basta fazer o download dos dados.

## 🗂️ Referências 



## 🛐 Agradecimentos

## 🧠 Contribuições dos Colaboradores

<table align="center">
  <tr>
    <!-- Desenvolvedor 1 -->
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/172425313?v=4" width="140"><br>
      <sub>
        <strong>
          <a href="https://github.com/GabrielMartinsSousa" target="_blank">Gabriel Martins</a>
        </strong>
      </sub><br>
      <sub><a href="https://ilum.cnpem.br/" target="_blank">Ilum - CNPEM</a></sub><br>
      <sub><a href="http://lattes.cnpq.br/xxxxxxxxxxxxxxx" target="_blank">Currículo Lattes</a></sub><br>
      <sub><a href="https://www.linkedin.com/in/usuario" target="_blank">LinkedIn</a></sub>
    </td>
    <!-- Personagem 1 -->
    <td align="center">
      <img src="https://github.com/user-attachments/assets/28fd049c-d60b-4c86-b7b6-2d794dea3fdf" width="140"><br>
      <sub><em>como <strong>Haryell Marino</strong></em></sub><br>
      <sub>Legião da Alvorada</sub><br>
      <sub>Divisão Clareyamar</sub><br>
      <sub>Mago do Mar</sub>
    </td>
    <td width="30"></td>
    <!-- Desenvolvedor 2 -->
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/172424981?v=4" width="140"><br>
      <sub>
        <strong>
          <a href="https://github.com/ClaraLelis" target="_blank">Clara Lelis</a>
        </strong>
      </sub><br>
      <sub><a href="https://ilum.cnpem.br/" target="_blank">Ilum - CNPEM</a></sub><br>
      <sub><a href="http://lattes.cnpq.br/xxxxxxxxxxxxxxx" target="_blank">Currículo Lattes</a></sub><br>
      <sub><a href="https://www.linkedin.com/in/usuario" target="_blank">LinkedIn</a></sub>
    </td>
    <!-- Personagem 2 -->
    <td align="center">
      <img src="https://github.com/user-attachments/assets/6cc61d25-b6fb-4cd1-a724-26d55bab1fac" width="140"><br>
      <sub><em>como <strong>Olive Solace</strong></em></sub><br>
      <sub>Legião da Alvorada</sub><br>
      <sub>Divisão Clareyamar</sub><br>
      <sub>Arcano do Sol</sub>
    </td>
    <td width="30"></td>
    <!-- Desenvolvedor 3 -->
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/171518829?v=4" width="140"><br>
      <sub>
        <strong>
          <a href="https://github.com/yasminbshimizu" target="_blank">Yasmin Shimizu</a>
        </strong>
      </sub><br>
      <sub><a href="https://ilum.cnpem.br/" target="_blank">Ilum - CNPEM</a></sub><br>
      <sub><a href="https://lattes.cnpq.br/7813674402525956">Currículo Lattes</a></sub><br>
      <sub><a href="https://www.linkedin.com/in/yasminbshimizu/" target="_blank">LinkedIn</a></sub>
    </td>
    <!-- Personagem 3 -->
    <td align="center">
      <img src="https://github.com/user-attachments/assets/f79e5706-9497-4185-b489-2972365729d0" width="140"><br>
      <sub><em>como <strong>Ebony Vitrum</strong></em></sub><br>
      <sub>Legião da Alvorada</sub><br>
      <sub>Divisão Clareyamar</sub><br>
      <sub>Escudeiro de Cristal</sub>
    </td>
  </tr>
</table>


#### Para o Projeto:
* Gabriel Martins: .
* Clara Lelis: .
* Yasmin Shimizu: .

#### Para o Repositório GitHub:
* Gabrel Martins: .
* Clara Lelis: .
* Yasmin Shimizu: .

**Orientação e Revisão:** Prof. Dr. Daniel R. Cassar.
