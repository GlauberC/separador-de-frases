# separador-de-frases
Separa textos em inglês de sua tradução, para que cada frase fique lado a lado em uma tabela(cada coluna será um idioma).  
Ao clicar na frase automaticamente o a frase será copiada(e também mudará de cor) para que possa ser colada onde o usuário quiser.
---
## Como usar ?
1. Abra o código em seu editor de texto ou ide.
2. Encontre a tag **\<p id="texto1"\>** e insira o texto, antes do seu fechamento. Você pode inserir o texto de duas maneiras.
    * Insira apenas o texto em inglês e na tag **\<p id="texto2"\>** insira o texto em português
    ```
      <p id="texto1">
        Your text here
	   </p>
      <p id="texto2">	
        Seu texto aqui
	  </p>
    ```
    * Insira as frases apenas no **\<p id="texto1"\>** de forma alternada (primeiro inglês e depois português). O **\<p id="texto2"\>** pode ser ignorado
     ```
      <p id="texto1">
        Your text here
        Seu texto aqui
	   </p>

    ```
#### Obs: O separador procurará ! ? e . Portando para que funcione, é necessário que ambos os textos estejam com a mesma pontuação, caso contrário o programa apresentará inconsistências.
3. Baseado na sua escolhe de como colocou o texto,  escolha o botão equivalente. 
    * Textos separados caso tenha usado **\<p id="texto1"\>** e **\<p id="texto2"\>**
    * Textos juntos caso tenha alternado as frases usando apenas o **\<p id="texto1"\>**
4. Para que a frase seja copiada, basta clicar. Haverá um mudança de cor para informar ao usuário que ele clicou nessa frase. 
---
## Exemplo

![alt text](https://github.com/GlauberC/separador-de-frases/blob/master/Exemplo.png)
---
## Dicas de uso
Esse programa foi feito exclusivamente para adicionar frases no Anki. Caso não conheça essa ferramenta acesse https://pt.wikipedia.org/wiki/Anki .
