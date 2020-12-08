## Aplicação Docker com Flask

### Executar

1. Ative o ambiente virtual criado com o poetry (se não tiver, crie).
   ```
   *No meu caso:
   
   . /home/gustavo/.cache/pypoetry/virtualenvs/flaskapp-nrfaz5QK-py3.8/bin/activate
   ```
2. Instalar o requirements:
   ```
   pip install -r requirements.txt
   ```

2. Construa a imagem a partir do dockerfile.

3. Para executa-lá basta ir até o ícone do docker, clicar em "image", procurar pelo nome da aplicação, e posteriormente clicar com direito em "run" na aplicação.

4. Volte no terminal e execute a aplicação python com o comando:
    ```
    *python app.py
    ```
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- https://docs.github.com/pt/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax -->

<!-- Anotações -->

<!-- Comando utilizado para exportar os requirements:
<!-- poetry export -f requirements.txt --output requirements.txt

<!-- Dúvidas -->

<!--
1.Uma vez construido a porta não pode ser mais alterada?
2.Tem uma forma mais fácil de acessar o ambiente virtual criado pelo poetry?
3.O poetry realmentre cria o ambiente virtual (a partir do virtualenv)?
4.O que exatamente o poetry faz?
5.Quando meu docker cai 0.0.0.0 o 127.0.0.1 assume a aplicação?
-->
