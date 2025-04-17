# SQLite-e-DB-Browser
Instalação SQLite e DB Browser no Windows 10

------------------------------------------------------------------------------------------------------------------------------------------

SQLite: https://sqlite.org/index.html  
Na seção Download baixe as verões mais recente dos seguintes arquivos, "sqlite-dll" e "sqlite-tools" que sejam compatíveis com o seu\ sistema operacional. Estarei baixando as seguintes versões:\

"sqlite-dll-win-x64-3490100.zip"\
"sqlite-tools-win-x64-3490100"\

Extraia o arquivo "sqlite-dll-win-x64-3490100.zip", que vai conter o seguinte:\
  "sqlite3.def" e "sqlite3.dll"\

Extraia para dentro de uma pasta os arquivos do "sqlite-tools-win-x64-3490100", sendo eles:\
  "sqldiff", "sqlite3", "sqlite3_analyzer" e "sqlite3_rsync"\

Agora dentro dessa mesma pasta cole os arquivos extraidos do "sqlite-dll-win-x64-3490100.zip".\
A pasta contém agora:\
  sqldiff\
  sqlite3.def\
  sqlite3.dll\
  sqlite3\
  sqlite3_analyzer\
  sqlite3_rsync\

Renomeie essa pasta para "sqlite3", recorte e coloque dentro do diretório Windows(C:)\

Copie o caminho da pasta para colocar dentro das variáveis de sistema, nesse caso o caminho é C:\sqlite3\

Digite no menu iniciar ----> Editar as variáveis de ambiente do sistema\
Na aba "Avançado", abra a opção "Variáveis de Ambiente..."\
Na nova janela que abriu, vá na parte inferior, onde diz "Variáveis do sistema" e selecione "Path", depois selecione a opção "Editar"\
Agora selecione a opção "NOVO" e cole na linha o caminho da pasta sqlite3 que já havia sido copiado anteriormente e pressione a tecla Enter, só ir fechando as janelas clicando em "OK".\

Abra o prompt de comando, digite sqlite3 e pressione Enter para testar a instalação, vai aparecer uma mensagem informando a versão instalada do SQLite.\

OK, instalação efetuada com sucesso, se acontecer algum erro, volte a sequência de passos e tente novamente.\

Próximo passo, instalar o DB Browser.\

------------------------------------------------------------------------------------------------------------------------------------------

DB Browser: https://sqlitebrowser.org/\
Na seção Download baixe a versão mais recente do programa, que seja compatível com o seu sistema operacional. Estarei baixando o instalador, versão:\

"DB.Browser.for.SQLite-v3.13.1-win64"\

Execute o arquivo, avançando nas opções de instalação, ao chegar na aba "Shortcuts" selecione apenas a caixa "Desktop" para "DB Browser (SQLite)".\

Ok, mais uma instalação finalizada com sucesso, se acontecer algum erro, volte a sequência de passos novamente.\
