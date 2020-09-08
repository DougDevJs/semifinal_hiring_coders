<h1>README SEMIFINAL HIRING CODERS</h1>

<h2>Iniciando o projeto com submódulos do git hub:</h2>

<p>Após clonar o repositório principal: </p>
<ul>
    <li>Executem no terminal o comando: <b>git submodule init</b> (Este comando irá iniciar as configurações necessárias para trabalhar com os submódulos)</li>
    <li>Executem no terminal o comando: <b>git submodule update</b> (Esse comando irá carregar toda a configuração necessária, caso tenha feito alterações em seus submódulos.)</li>
</ul>
<br/>
<p>Atualizar a dependência:</p>
<ul>
    <li>Acesse a pasta do submódulo: <b>cd/[nome do diretório]</b></li>
    <li>Execute <b>git checkout sua_branch</b> (Ex: git checkout master), para ir para sua branch ou criar outra branch.</li>
    <li>Execute <b>git pull remote sua_branch</b> (Ex: git pull origin master), para atualizar sua branch em caso de mudanças não contabilizadas.</li>
</ul>
<br/>
<p><b>Evitem efetuar push no repositório principal, desta maneira evitamos que problemas em um projeto prejudiquem o outro.</b></p>
