Jackeline Mayara Cardoso Saez RA: 1903040    
  
Exemplo comando Clone:  
1 - [print_01] Criando um repositório via interface web;    
2 - [print_02] ls > mostrando diretório vazio;       
3 - git clone https://github.com/jackelinesaez/devops_ac02.git > clonando branch master do repositorio remoto para o repositorio local;     
4 - [print_03] ls > mostrando diretório do projeto e README nele contido.        
    
Exemplo comando Add:    
1 - [print_04] git status > Indicando que houve mudanças nos arquivos da branch master, mas essas alerações não se encontram no staged* apenas no working directory.
*O que é staged? Area temporaria. É basicamente um espaço temporário onde você determina quais mudanças serão commitadas, ou seja, funciona como uma area pre-commit, você adiciona os arquivos para o staging, e quando estiver satisfeito com as alterações efetua um commit;    
2 - [print_05] git add README.md > adiciona as modificações realizadas no arquivo README.md para a area staging;   
3 - [print_06] git status > mostrando que as novas modificações do arquivo README.md já estão na area staging.  
    
Exemplo comando Commit:   
1 - [print_07] git status > verificando repositorio local, onde foi apontado que há arquivos para serem commitados;    
2 - [print_08] git commit -m 'Add novas explicacões sobre os comandos git' > comitando as alterações realizadas no arquivo README.md no repositorio local;  
3 - [print_09] git status > verificando diretorio de trabalho e staging, onde o arquivo README.md não é mais visivel pois o mesmo não possui novas alterações, ou seja, esta atualizado no repositorio local.  
  
Exemplo comando Push:  
1 - [print_10] git status > indicando que o repositorio local possui novas alterações que o remoto não possui;  
2 - [print_11] git push > enviando alterações do aquivo para o repositorio remoto;   
  
Exemplo comando Fetch:  
1 - [print_12] Criando uma branch via interface web;  
*2 - [print_13] git fetch > Atualiza o repositorio local com o repositorio remoto, sem afetar os arquivos locais;    
3 - [print_14] git status > Informa que há um commit no repositorio remoto e para atualizar o local deve usar o git pull.  
  
Exemplo comando Pull:  
1 - [print_15 git pull > Atualiza o repositorio local com o repositorio remoto, afetando os arquivos;  
2 - [print_16] cat README.md > mostra conteudo do arquivo README.md.  
  
Exemplo comando Checkout:  
1 - [print_17] git checkout branch_exemplo > mudando de branch