# Principais Comandos



> | Comando                                             | Ação                                                         |
> | --------------------------------------------------- | ------------------------------------------------------------ |
> | ls                                                  | listar diretórios                                            |
> | cd diretórioalvo                                    | vai para um subdiretório                                     |
> | mkdir nomediretório                                 | cria um novo diretório                                       |
> | cd ..                                               | sobe 1 nivel no diretório                                    |
> | touch nomedoarquivo.extensãodoarquivo               | cria um arquivo *ex: touch readme.md cria um arquivo com extensão md nomeado readme* |
> | git mv arquivoalvo.md ./LocalAlvoDa Mudanca/        | move o arquivo alvo para o ./diretórioalvo *obs: diretório e arquivo devem estar no mesmo nível vide "./" anterior ao localalvodamudanca* |
> | git mv NomeAntigo Nomenovo                          | Altera o nome de arquivo                                     |
> | git config --global user.email "IndicarOEmail"      | faz login? necessário confirmar se está correto              |
> | git add *                                           | adiciona algo                                                |
> | git status                                          | útil para saber se há algum arquivo não trackeado            |
> | git add *                                           | add tudo que ainda não foi commitado/trackeado para ser comitado no prox comando |
> | git commit -m                                       | commita o que foi dado anteriormente no git add              |
> | git remote add origin https://enderecodorepositorio | pegar o endereço do repositório no github e colar no comando para mandar o repositório do servidor local para servidor remoto (github) |
> | git remote -v                                       | -lista todos repositórios remotos apontados no reopsitório   |
> | git push origin master                              | empurra o arquivo para o repositorio remoto observar se é *(master)* ou *(main)* |
> | git pull origin master                              | puxa os arquivos do diretório remoto para o diretório local  |
> |                                                     |                                                              |
> |                                                     |                                                              |
> |                                                     |                                                              |
> |                                                     |                                                              |

**Para baixar todo um diretório do github para a maquina**

```
vai no diretório que deseja clonar, copia a url pelo retangulo verde "Code>Https..."> git clone https:...> entrar no repositório clonado git ls> entrar na pasta git cd nomedapasta>fazer as alterações necessárias nos arquivos desejados. 
```

**Mandar arquivos que foram alterados** 

alteração de arquivo> `git status` !-verifica os arquivos alterados obs: aparece em vermelho-!> `git add*` !-Adc tudo que apareceu em vermelho para ser commitado-! > `git status` !-mostra os arquivos marcados para ser subido obs:aparece em verde-!> `git add commit - "comentárioaqui"` !-sobe os arquivos-! 
++++para mandar essas alterações para o repositório remoto é necessário fazer ainda o git push origin master

**Alterar nome de pasta ou arquivo**
`mv ./nomeantigodapasta ./novonomedapasta` o Comando deve ser executado 1 nivel acima da pasta alvo pois a pasta é renomeada  no mesmo local

**alterações de email e user**
`git config --global --unset user.mail`  !- para deletar o email que estava configurado-!
`git config --global --unset user.nickname` !-deletar user que estava configurado-!
`git config --global --unset user.mail "novoemail"` !-adicionar novo email-"
`git config --global user.nickname "novouser"` !-adicionar um user-!

> 