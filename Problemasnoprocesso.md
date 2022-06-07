# É... E deu ruim!

Ao tentar fazer o push para o repositório remoto, acabou-se criando uma segunda branch (provavelmente porque a branch do repositório remoto se chamava "main" e a do repositório pessoal se chamava "master"). Tentei deletar a branch que eu havia feito o commit do repositório pessoal para depois conseguir dar um pull do servidor remoto e então dar um commit em uma branch única.

Acontece que houve um erro devido aos diferentes históricos e por isso não conseguia dar push e nem pull. Após algum tempo de pesquisa utilizei o comando "git pull origin master --allow-unrelated-histories" que logo resolveu o problema do "pull" trazendo o arquivo "README.md" criado no mesmo momento que o repositório remoto, segui utilizando o push para o repositório remoto e assim pude finalizar o push anterior.



Encerrando o arquivo "Problemasnoprocesso", realizei todos os processos anteriores e realizei o push sem maiores problemas.