# MICROSOFT AZURE AL900 - LANGUAGE STUDIO - PARA ALÉM DO QUE ESTÁ ESCRITO📝
Projeto com Language Studio, analisando sentimentos e opiniões, com base em sentenças criadas e declaração retirada de portal virtual.

Documentação utilizada como base:

[Analyze text with Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)

1. Antes de tudo, como passo inicial, deve-se ter um resource criado no [Microsoft Azure](https://azure.microsoft.com/) para acesso do [Language Studio](https://language.cognitive.azure.com/).

2. Para acessar, na aba categorias, em AL+Machine Learning pressionar create "Language Service".
##
![Acesso Language studio](https://github.com/vgastaldelli/LABORATORIOAZUREAI900-LANGUAGESTUDIO2024/assets/160192109/e08171f1-efc4-4f28-b761-1d5f0ceb3eee)

 ##
3. Depois de criado o resource, acessar Language Studio e fazer o pareamento.
   
5. Já no Language Studio, para esse projeto, vamos acessar a aba "Classify Text" e selecionar "Analyze sentiment and mine opinions".
##
![image](https://github.com/vgastaldelli/LABORATORIOAZUREAI900-LANGUAGESTUDIO2024/assets/160192109/2af2f311-c37a-40c1-b8a7-f3630156dbe7)


6. Esse será a tela inicial:
##
![Analyze Sentiment and opinion](https://github.com/vgastaldelli/LABORATORIOAZUREAI900-LANGUAGESTUDIO2024/assets/160192109/c03a6d4b-5083-4700-a143-fc7cc7e89da7)
##
**Obs.: Atenção! É de extrema importância se atentar para o idioma do texto que é utilizado. Por isso é sempre bom prestar atenção na opção "Select text language".**

Esse é o lugar onde é mostrado os resultados da análise:
##
![Result](https://github.com/vgastaldelli/LABORATORIOAZUREAI900-LANGUAGESTUDIO2024/assets/160192109/a0a8f086-59d7-40f9-9511-5ec78187fd7c)
##
7. Como primeira análise, estaremos utilizando a seguinte sentença:

   "This food is amazing!"

##
   ![image](https://github.com/vgastaldelli/LABORATORIOAZUREAI900-LANGUAGESTUDIO2024/assets/160192109/cfccaee6-162e-43fd-b5b4-82734b091f73)

Como o próprio programa detectou, essa é uma sentença 99% positiva; 1% neutra e 0% negativa. E o seu target é "food".

8. Podemos utilizar outra frase abaixo:

"Yesterday I was at a restaurant that was terrible".

##
![image](https://github.com/vgastaldelli/LABORATORIOAZUREAI900-LANGUAGESTUDIO2024/assets/160192109/29a39e66-88d3-4669-9713-708630ee13a1)

Como o próprio programa detectou, essa é uma sentença 98% negativa; 1% neutro e 0% positiva. E o seu target é "restaurant".

9. Uma outra sentença interessante é a abaixo:

    "My mom got me a very weird present for my birthday"
##
   ![image](https://github.com/vgastaldelli/LABORATORIOAZUREAI900-LANGUAGESTUDIO2024/assets/160192109/cd691213-59e0-4e6d-8830-1f335fe8e9b2)

   A própria frase acima mostra algo muito interessante: o programa 34% para positivo; 30% neutro e 36% negativo. Ou seja, o programa não conseguiu estabelecer um target nem mesmo definir os sentimentos e opiniões presentes na frase.


