### Primeiro Teste de Git.

* **git init**: Initialized empyt Git Repository;
* **git add**: Mandar os arquivos para a área de steyding(Tradução: Guiando);
* **git status**: mostra quais arquivos foram identificados;
* **git commit -m "Texto"**: salva os arquivos e atualiza o status, mostrando que não tem nenhum commit;
* **git branch -M "main"**: Troca de nomeclatura master para main; 
* **git remote add origin** https://github.com/usuário/nome-do-repositorio.git;
* **git push -u origin main**: push do repositório local para o repositório do GitHub;
* **git push origin main** é usado quando o repositório já estiver ativo no GitHub e ele repõe o novo commit, não será necessario o "-u" depois que já foi utilizado o **push -u origin main** na primeira vez. 

### Conceito de Branch.

* **git checkout -b "Nome do seu Branch"**: Criando uma nova Branch, ou seja, saindo da Branch atual "main" para a branch que for criada, qualquer alteração que houver não será main alterado na branch "main", mas será alterado na branch nova.