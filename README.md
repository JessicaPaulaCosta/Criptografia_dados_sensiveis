# Criptografia de Dados Sensiveis

Desenvolvimento de uma query em python com Jupyter Notebook


Protósito: criptografar e descriptografar credenciais de acessos como: API, Bancos de Dados, aplicações WEb, entre outros.


Processos:  
Criptografa a informação contida no arquivo raiz do projeto "minhaSenha.txt" e grava em um outro arquivo "encryptPWD.txt" Gera uma chave e grava em um outro arquivo "refkey.txt" 

Agora é possível excluir o arquivo "minhaSenha.txt" com a senha e trabalhar ou compartilhar o projeto somente com o arquivo criptografado, em uma comunicação mais segura.  


Descriptografia : Ler a minhaSenha criptografada e armazena em 2 variáveis (usuário e senha)    


Bibliotecas: pip install cryptography  Automação: O projeto tem uma pequena automação para startar o jupyter notebook. Basta clicar no arquivo "Clique aqui" que o programa inicializa. Saiba mais em: https://github.com/JessicaPaulaCosta/Automacao_Start_Jupyter_Notebook
