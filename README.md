# Automação de relatorio de fechamento da Ibovespa e do dolar

<p align="center">Projeto realizado durante bootcamp da <a href="https://www.youtube.com/@varos-programacao">Varos 🤖</a></p>

---

### Tecnologias
- [Python](https://www.python.org/) 🐍
- [JupterNotebook (anaconda3)](https://www.anaconda.com/) 🪐

---

### Dependências
- pandas
   ```pip install pandas```
- matplotlib
   ```pip install matplotlib```
- yfinance
   ```pip install yfinance```
- mplcyberpunk
   ```pip install mplcyberpunk```
- python-dotenv
   ```pip install python-dotenv```
---

### modo de usar
1. Instale as dependências
1. Configure seu email através do seu ambiente de desenvolvimento:
   1. Crie um arquivo com o nome ```.env``` no mesmo local do script
   1. No arquivo crie a variável email atribuindo o seu email. Ex: ```email="seu email"```
   1. Faça o mesmo para a senha atribuindo para a variável password sua senha (Caso use o gmail é necessário usar uma senha de apps)
1. Configure o endereço que recebera o email de acordo com sua preferencia, dentro do programa, na parte de envio do email
1. Após todos os passos basta executar o programa

---

### Resumo
O programa consiste em pegar os dados do Ibovespa e do Dolar através do yahoo finance, trata-los e relatar por e-mail<br>
de forma dinâmica e automatizada a rentabilidade anual, mensal e diária.
