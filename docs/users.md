#Utilização jOne

###Autenticação
<table>
    <tr>
        <td><img src="../img/users/login/1.png"></td>
    </tr>
</table>
Esta é a janela de abertura do **jOne**. A autenticação é feita pela *Active Directory* (AD), e é necessário introduzir as credencias correspondente ao utilizador.
Caso não seja possível concretizar a autenticação, o sistema retorna uma mensagem por baixo das caixas de texto.

Quando a aplicação é iniciada por vários utilizadores (no mesmo utilizador do sistema operativo) é mantida uma lista horizontal dos últimos utilizadores autenticados.
<table>
    <tr>
        <td><img src="../img/users/login/2.png"></td>
    </tr>
</table>
Existe um botão - "*Mudar a palavra-passe*", cujo intuito é possibilitar ao utilizador uma forma mais rápida de mudar as suas credenciais.
###Barra de tarefas
É na barra de tarefas que o utilizador tem acesso a cada módulo e funcionalidade existente no **jOne**. Cada tipo/perfil de utilizador tem acesso a determinados módulos e funcionalidades.
####Programador
<img src="../img/users/taskbar/1.png">

Por curiosidade é disponibilizado o aspecto da taskbar do perfil de utilizador que tem acesso a todas as funcionalidades.

####Gestor de utilizadores
<img src="../img/users/taskbar/2.png">

Na barra de tarefas, o gestor de utilizadores tem acesso ao módulo correspondente a preferências e funcionalidades transversais a todos os perfis.

####Chefe de serviço ou Gestor
<img src="../img/users/taskbar/3.png">

Na barra de tarefas, o gestor tem acesso ao módulo correspondente ao acesso a relatórios, preferências,  pesquisa de utentes e funcionalidades transversais a todos os perfis.

####Enfermeiro triador
<img src="../img/users/taskbar/4.png">

Na barra de tarefas, o enfermeiro tem acesso ao módulo correspondente ao acesso a lista de triagem, preferências, pesquisa de utentes e funcionalidades transversais a todos os perfis.

###Menu do utilizador
<img src="../img/users/taskbar/5.png">

Todos os utilizadores têm acesso a este menu, justificando a breve explicação de cada item, excetuando "Terminar sessão", cuja função é voltar ao menu de autenticação (logout).

#####O meu perfil
<img src="../img/users/taskbar/6.png">

Nesta janela, o utilizador pode verificar e alterar dados relativos à sua identificação no **jOne**.
#####Sugestões
<img src="../img/users/taskbar/7.png">

O utilizador tem a oportunidade de visualizar, comentar e avaliar sugestões feitas por outros os utilizadores de uma forma categorizada.
<img src="../img/users/taskbar/8.png"></td>

Também pode enviar as suas sugestões através do botão "*Nova Sugestão*". Estaremos atentos, e disponíveis para melhorar a utilização do **jOne**.

#####Favoritos
<img src="../img/users/taskbar/9.png">

Sob a forma de menu, e, quem tem acesso a *cartões*, pode adicionar "*Favoritos*" de forma a aceder à informação clínica de uma forma mais rápida. O utilizador tem a oportunidade de agrupar os seus *cartões*.

#####Páginas Web
<img src="../img/users/taskbar/10.png">

É possível dar acesso a uma lista de hiperligações. Este é o exemplo do que existe no **CHSJ**.

#####Contactos
<img src="../img/users/taskbar/11.png">

É possível dar acesso a uma lista de contactos. Este é o exemplo do que existe no **CHSJ**.

#####Notícias
<img src="../img/users/taskbar/12.png">

Periodicamente, existe a necessidade de passar informação noticiosa aos nossos utilizadores. Esta é a área de leitura de notícias que pretendemos que cheguem aos utiilzadores **jOne**.

####Calendário
<img src="../img/users/taskbar/13.png">

Muitas das tarefas dos nossos utilizadores depende do calendário. Nesta área é possível consultar as datas importantes, e adicionar notas diárias.

###Pesquisa
<img src="../img/users/taskbar/14.png">

Esta é uma funcionalidade que varia conforme o perfil que o utilizador tiver. Alguns, não têm acesso, outros só fazem pesquisa dos utilizadores nas listas abertas, outros retornam *cartões de processo* e outros *cartões de episódio*.
A pesquisa pode ser feita por número (números identificativos do utente) ou nome.

<img src="../img/users/taskbar/15.png">

Se o utilizador tiver acesso à *pesquisa avançada*, a resposta à pesquisa é uma lista, e ao seleccionar um item, gerará um *cartão* no *desktop*.

<img src="../img/users/taskbar/16.png">

Caso seja necessário limitar a pesquisa (por nome), poderá limitar os resultados por um período de idades.

##Técnico de Informática
###Criação ou alteração de utilizadores

Para o técnico proceder à manutenção de utilizadores, tem acesso ao módulo de preferências. Sendo que apenas a pesquisa por número mecanográfico será essencial, pois as outras funcionalidades são para acesso dos programadores.

<img src="../img/users/admin/1.png">

A pesquisa por número mecanográfico, retorna dados do utilizador do **jOne** ou da **AD** (caso o utilizador não exista no **jOne**).

<img src="../img/users/admin/2.png">

Sendo Criação/Edição de utilizador, deve-se preencher os campos necessários e válidos.
Após *categorizar* o utilizador a criar, não será possível alterar (a *categoria*).
Os perfis a dar são correspondentes à categoria que desempenham. No caso do **CHLC**:

* Enfermeiro: *Enfermeiro Urgência Pediatrica*
* Chefe de serviço/Gestor: *Acesso Reports*
* Técnico de informática: *Técnico Informática*

##Enfermeiro triador
O '*workflow*' de trabalho do enfermeiro triador é feito da esquerda para a direita. Começa, à esquerda com a **lista do utentes** que ainda não foram triados, passando pelo **cartão de triagem** e a **lista de trabalho**, à direita.
###Lista
A lista de utentes (à esquerda) é alimentada pelas admissões realizadas pelos administrativos da urgência pediátrica.
É possível ordenar a lista, agrupar e filtrar a lista. O filtro é relativo à escolha da vista "*Ver todos*", sendo que, estando desmarcada ver-se-ão os utentes por triar (excepto se estiverem no *desktop/lista de trabalho de alguém)*; e, no CHLC, *todos* serão os utentes que estão por triar e que ainda não tiveram alta hospitalar (administrativa - SONHO).

Além disso, na área de pesquisa é possível seleccionar utentes que estejam na lista (desde que já esteja carregada).
<img src="../img/users/triage/2.png">

###Cartões
Após arrastar o utente da *lista de utentes* é criado um *cartão* que terá o aspecto da imagem seguinte.
E terá acesso ao *menu do utente* (sobre a foto), aos *dados biográficos*, *processo*, *triagem* e *avaliações*.

<img src="../img/users/triage/3.png">

Após a triagem o *cartão* fica com a cor e data da triagem:

<img src="../img/users/triage/4.png">

Caso o enfermeiro faça uma *pesquisa avançada*, o *cartão* terá o seguinte aspecto (só não tem acesso à *triagem*, e ao *abandono* da parte do utente no episódio):
<img src="../img/users/triage/5.png">

###Lista de trabalho

Após as tarefas realizadas com o *cartão* o enfermeiro pode/deve manter na sua *lista de trabalho*, arrastando o *cartão* para a direita. Sendo que, o *cartão de triagem* passa para *Altas* assim que houver alta administrativa (e permanecendo lá por um período de tempo).
<img src="../img/users/triage/6.png">
###Áreas do cartão
> Falta acrescentar o menu do utente

####Dados Biográficos
Esta *área do cartão* disponibiliza ao enfermeiro informação sobre dados administrativos significativos. O *jOne* utiliza dodos do *Registo Nacional de Utentes*, caso esteja disponível, para completar os dados.
<img src="../img/users/triage/7.png">

####Processo
Será permitido ao enfermeiro ver os dados que foram registados nas triagens de cada episódio de urgência pediátrica que o utente teve. Basta fazer a selecção do episódio na lista à esquerda.
<img src="../img/users/triage/8.png">
####Avaliações
É possível ver os registos de sinais vitais, de forma tabelada, que foram inseridos ao longo do processo do utente.
<img src="../img/users/triage/16.png">

###Processo de triagem
O processo de triagem vai ter formação específica ao enfermeiro, assim, apenas vou disponibilizar as imagens e algumas observações.

<img src="../img/users/triage/9.png">
<img src="../img/users/triage/10.png">
<img src="../img/users/triage/11.png">
<img src="../img/users/triage/12.png">
<img src="../img/users/triage/13.png">
<img src="../img/users/triage/14.png">
<img src="../img/users/triage/15.png">
No fim do processo de triagem, pode haver uma impressão, que exige "ida à base de dados" para obter as triagens anteriores, e a instalação do "XPS Viewer" (ver Instalação - Pré requisitos).

##Gestor
###Relatórios
Um dos módulos que o gestor tem acesso é o dos relatórios. Este módulo é composto por uma lista à esquerda, que conforme a seleção, mostra o relatório pretendido; e, à direita, será, possivelmente, pedido o preenchimento de parâmetros. Esta funcionalidade exige comunicação e acesso ao serviço de Reporting Services.
<img src="../img/users/manager/1.png">
###Preferências de triagem
O gestor consegue editar os fluxogramas e discriminadores da triagem, tendo em **ATENÇÃO** que todas as mudanças feitas e guardadas afectam **imediatamente** a triagem.

<img src="../img/users/manager/2.png">

A edição permite:
* adicionar fluxogramas
* alterar a descrição de cada fluxograma;
* alterar a ordem entre os fluxograma;
* adicionar discriminadores a fluxogramas;
* editar discriminadores;
* alterar a ordem, dentro da cor (confirmar)

> !Funcionalidade com pouco uso, aconselha-se guardar em cada alteração, e esperar pela janela de confirmação

<img src="../img/users/manager/3.png">

###Cartão processo
Caso o gestor faça uma *pesquisa avançada*, o *cartão* terá o seguinte aspecto (ver detalhes nas *áreas do cartão* do enfermeiro):

<img src="../img/users/triage/5.png">