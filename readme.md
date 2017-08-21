# ROC FRAMEWORK<br>
![ROC LOGO](logo.jpg)<br>
ROC é um framework que possibilita uma ampla organização em seu projeto. Feita com Stylus, CSS e usando conceitos de organização do Atomic Design ela é tudo aquilo que o desenvolvedor web precisava sem mais e nem menos, tudo na medida certa! Sua estrutura é separada em diversos arquivos que seguem a metodologia do Atomic Design e mantendo uma boa semântica em seu projeto. Se você ainda não sabe sobre está metodologia do Atomic Design é basicamente este exemplo abaixo:
<br>

#### Atomic Design Metodologia
<ol>
    <li>Átomos</li>
    <li>Moléculas</li>
    <li>Organismos</li>
    <li>Templates</li>
    <li>Páginas</li>
</ol><br>
#### Como usar?
<br>
Para usar é bem simples em sua página insira os códigos da base da index.html localizada na pasta RocBase e logo depois é só incrementar seu estilo na pagina.css. O framework tem um arquivo core em stylus que pega todos as folhas de estilo da página e compilando em um unico só arquivo chamado ROC.css, isso faz com que o seu projeto ande na linha na questão organização veja abaixo como é a estrutura.
<br>
<pre>
    @import'atomos.css';//Não modificar
    @import'moleculas.css';//Não modificar
    @import'organismo.css';//Não modificar
    @import'modelo.css';//Não modificar
    @import'pagina.css';//Editar
</pre>
<br>
Lembrando que este framework vem com apenas o necessário para seu projeto! No framework você pode encontrar alguns boxes, botões, sistema de grid, formulários e mídias responsivas. Fora isso você já tem um esquema de organização já modulado de mídias queryes mais usadas atualmente no mercado.    

