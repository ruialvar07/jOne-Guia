#Estrutura

##Base de dados
<table>
    <tr>
        <td style="width:150px"><img src="../img/structure/1.png" style="width: 130px"></td>
        <td>A base de dados administrativa e financeira (ao longo do país) está baseada nesta versão. Sendo o **SONHO** um sistema *ADT* ('*Admission-discharge-transfer*'), e onde começa todo o processo informático do utente, tivemos que criar uma estrutura que nos permitisse obter os dados. Neste momento, existe um utilizador nesta base de dados, onde criamos '*jobs*' (pois não foi permitida a criação de '*triggers*') e '*procedures*' para transferir dados para tabelas auxiliares, para, depois, ser possível, a informação ser transferida.
      </td>
    </tr>
</table>
<table>
    <tr>
        <td style="width:150px"><img src="../img/structure/2.png" style="width: 130px"></td>
        <td>É nesta versão que está a base de dados que persiste toda a informação do **jOne**. Toda a estrutura (de determinado momento) - objectos como utilizador, tabelas, funções, views, sequencias (...) - foram importados para a instância existente no **CHLC**. Apenas as tabelas que permitem a integração e funcionamento das funcionalidades do cliente foram preenchidas.</td>
    </tr>
</table>
<table>
    <tr>
        <td style="width:150px"><img src="../img/structure/3.png" style="width: 130px"></td>
        <td>Esta versão de base de dados existe por dois motivos: **Reporting Services** e **Mirth**. É necessário para guardar e disponibilizar os relatórios consultados pelo Gestor, e, para guardar as mensagens trocadas pelo integrador.</td>
    </tr>
</table>
##Integrador
<table>
    <tr>
        <td style="width:150px"><img src="../img/structure/4.png" style="width: 130px"></td>
        <td>Apesar da existência de múltiplos canais no **CHSJ**, que permitem a comunicação entre variados sistemas de informação, no **CHLC** apenas existe canais com dois propósitos: manter os dados atualizados com o **SONHO** e enviar o pdf resultante de cada triagem para o **HP-HCIS**.
        </td>
    </tr>
</table>
##Serviços
<table>
    <tr>
        <td style="width:150px"><img src="../img/structure/5.png" style="width: 130px"></td>
        <td>É nesta tecnologia que está baseado todo o nosso "*negócio*". Ligações a base de dados, ligação a integrador, disponibilização de métodos e objectos para os clientes... passa tudo por esta camada. O uso da linguagem **C#** e da **Framework 4.0** permite-nos performance em todas as ligações e criação de objectos.</td>
    </tr>
</table>
<table>
    <tr>
        <td style="width:150px"><img src="../img/structure/6.png" style="width: 130px"></td>
        <td>A função do célebre **IIS** é disponibilizar os serviços e aplicações que são desenvolvidos. Permite-nos cofigurar e controlar as ligações à camada de base de dados e ao cliente, de uma forma fiável e performante. Em **CHLC** vão estar alojadas quatro aplicações, duas para o **jOne**, uma para o integrador e este site.</td>
    </tr>
</table>
##Clientes
<table>
    <tr>
        <td style="width:150px"><img src="../img/structure/7.png" style="width: 130px"></td>
        <td>É nesta tecnologia que está desenvolvido o cliente que os profissionais do **CHLC** vão trabalhar. O grande valor desta tecnologia é o poder na camada de apresentação, o uso de **C#** e do **XAML** permitiu-nos proporcionar uma boa experiência aos utilizadores. No entanto, está limitada ao sistema operativo **WINDOWS**, e, a existência de muitas máquinas **XP** no SNS impede de usarmos todo o potencial da ferramenta. A distribuição do software é feita por **Click-Once** que permite facilidade na construção das builds e gestão de updates. </td>
    </tr>
</table>
<table>
    <tr>
        <td style="width:150px"><img src="../img/structure/8.png" style="width: 130px"></td>
        <td>Apesar de ser uma tecnologia antiga, permite-nos elaborar e apresentar documentos aos nossos gestores, de uma forma a que estão habituados. A existência de outros projectos no **CHSJ** que usam esta tecnologia, facilitou o trabalho, por exemplo, dos nossos administradores de sistemas.</td>
    </tr>
</table>
<table>
    <tr>
        <td style="width:150px"><img src="../img/structure/9.png" style="width: 130px"></td>
        <td>Devido às limitações que encontramos a nível tecnológico no **SNS**, e, por razões estratégicas, estamos a migrar e implementar novas funcionalidades para um cliente aplicativo web. Com a crescente utilização, melhoria gráfica e a existência de frameworks excelentes como o Angular, achamos o momento certo para acrescentar algo mais ao jOne e seus utilizadores.</td>
        <td style="width:150px"><img src="../img/structure/10.png" style="width: 130px"></td>
    </tr>
</table>