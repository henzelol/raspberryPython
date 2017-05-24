Linux – Raspberry

Comandos:

PS 

Comando utilizado para ver quais processos estão sendo executados no computador, também mostra qual usuário executou o programa;

	Opções:

	- a Mostra os processos criados por você e de outros usuários do sistema;
	- x Mostra processos que não são controlados pelo terminal;
	- u Mostra o nome de usuário que iniciou o processo e hora em que o processo foi iniciado;
	- m Mostra a memória ocupada por cada processo em execução;
	- f Mostra a árvore de execução de comandos (comandos que são chamados por outros comandos);
	- e Mostra variáveis de ambiente no momento da inicialização do processo;
 	- w Mostra a continuação da linha atual na próxima linha ao invés de cortar o restante que não couber na tela.

TOP
	
Mostra os programas em execução ativos, parados, tempo usado na CPU, detalhes sobre o uso da memória RAM, Swap, disponibilidade para execução de programas no sistema.

	Opções:
	
	-d [tempo] Atualiza a tela após o [tempo] (em segundos);
	-s Diz ao top para ser executado em modo seguro;
	- i Inicia o top ignorando o tempo de processos zumbis;
	- c Mostra a linha de comando ao invés do nome do programa;

Teclas úteis:

	- espaço – Atualiza imediatamente a tela;
	- CTRL +L – Apaga e atualiza a tela;
	- h – Mostra a tela de ajuda do programa. (Pode ser usado com qualquer comando ex: top h);
	- i – Ignora o tempo ocioso de processos zumbis;
	- q – Sai do programa;
	- k – Finaliza um processo (semelhante ao comando kill);
	- n – Muda o número de linhas mostradas na tela, se 0 for especificado, ser[a usada toda a tela para listagem de processos;

JOBS

Comando para mostrar os processos que estão parados ou rodando em segundo plano. Processos em segundo plano são iniciados usando o símbolo “&” no final da linha de comando.

MKDIR

Comando utilizado para criar um diretório (Ex: mkdir pasta01)

RMDIR
	
Comando utilizado para remover um diretório (Ex: rmdir pasta01)

TOUCH

Comando utilizado para criar um arquivo (Ex: touch app.py veja que nesse exemplo a terminação em .py cria um arquivo de texto de extensão py referente a linguagem de programação Python)

CD

	Comando que permite ao usuário trocar de diretório (Ex: cd .. após executado leva o usuário ao diretório acima do diretório atual. Ex: cd desktop/ acessa o diretório desktop)

LS

	Comando que lista o conteúdo do diretório atual.
