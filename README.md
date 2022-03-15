<h3 align="center">
  <a href="https://git-scm.com/">Node.Js - Npm </a>: Apêndice de NPM
</h3>

<p align="center">
  <a href="https://github.com/BrunoAchon/Node.Npm/issues">
    <img src="https://img.shields.io/github/issues/BrunoAchon/Node.Npm" /> 
  </a>
    
  <a href="https://github.com/BrunoAchon/Node.Npm/network/members">
    <img src="https://img.shields.io/github/forks/BrunoAchon/Node.Npm" /> 
  </a>
    
  <a href="https://github.com/BrunoAchon/Node.Npm/stargazers">
    <img src="https://img.shields.io/github/stars/BrunoAchon/Node.Npm" /> 
  </a>
  
   <a href="https://github.com/BrunoAchon/Node.Npm/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/BrunoAchon/Node.Npm" /> 
  </a>
</p>

<table>
  
  <tr>
    <th>Comando:</th>
    <th>Descrição:</th>
  </tr>
 
  <tr>
    <td>mkdir "nome-da-pasta-do-projeto"</td>
    <td>(terminal) - Criar pasta para o projeto</td>
  </tr>

  <tr>
    <td>cls</td>
    <td>(terminal / node) - Limpar o terminal</td>
  </tr>

  <tr>
    <td>ls</td>
    <td>(terminal / node) - Listar conteúdos da pasta</td>
  </tr>

  <tr>
    <td>rm "nome-do-arquivo"</td>
    <td>(terminal / node) - Excluir arquivo</td>
  </tr>

  <tr>
    <td>cd ..</td>
    <td>(terminal / node) - Regride uma pasta</td>
  </tr>

  <tr>
    <td>cd "nome-da-pasta"</td>
    <td>(terminal / node) - Abre a pasta indicada</td>
  </tr>

  <tr>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td>npm</td>
    <td><a href="https://www.npmjs.com/">Site Oficial</a></td>
  </tr>       
  

  <tr>
    <td>npm -v</td>
    <td>Verificar a versão do npm.</td>
  </tr>
  
  <tr>
    <td>npm --version</td>
    <td>Verificar a versão do npm.</td>
  </tr>

  <tr>
    <td>npm get</td>
    <td>Verificar todas as keys que estão configuradas para o npm init</td>
  </tr>

  <tr>
    <td>npm config set init-Author-name "Nome-do-Autor-do-projeto"</td>
    <td>Configurar o autor do projeto.</td>
  </tr>

  <tr>
    <td>npm config set init-Author-url "URL-do-Autor-do-projeto"</td>
    <td>Configurar a pagina do autor do projeto.</td>
  </tr>

  <tr>
    <td>npm config set init-email "email-do-Autor-do-projeto"</td>
    <td>Configurar o email do projeto.</td>
  </tr>

  <tr>
    <td>npm config set init-licence "licença-do-projeto"</td>
    <td>Configurar a Licença do projeto. <a href="https://docs.github.com/pt/enterprise-server@3.1/rest/reference/licenses#get-all-commonly-used-licenses">Ver todas as licenças</a></td>
  </tr>

  <tr>
    <td>npm config </td>
    <td><a href="https://docs.npmjs.com/cli/v8/using-npm/config">Ver toda a documentação do npm config</a></td>
  </tr>

  <tr>
    <td>npm config delete "key"</td>
    <td>Deletar uma configuração (exemplo: author, init-Author-url)</td>
  </tr>

  <tr>
    <td>npm init</td>
    <td>Configurar pacote inicial do projeto (package.json)</td>
  </tr>

  <tr>
    <td>npm init -y / npm init --yes</td>
    <td>Configurar pacote inicial do projeto no modo Default</td>
  </tr>

  <tr>
    <td>npm i / npm install</td>
    <td>Instalar dependências do projeto</td>
  </tr>
  
  <tr>
    <td>npm i "Nome_da_Dependencia"</td>
    <td>Instalar uma dependência específica ao projeto</td>
  </tr>

  <tr>
    <td>npm i "Nome_da_Dependencia"@lasted</td>
    <td>Instalar uma dependência específica ao projeto com a ultima atualização de pacote.</td>
  </tr>

  <tr>
    <td>npm i "Nome_da_Dependencia" -g</td>
    <td>Instalar uma dependência específica ao projeto de forma global</td>
  </tr>

  <tr>
    <td>npm i "Nome_da_Dependencia" --no-save</td>
    <td>Instalar uma dependência ao projeto sem vincula-la ao package.json</td>
  </tr>

  <tr>
    <td>npm list / ls</td>
    <td>Listar toda a arvode de dependências do projeto - inclusive as de cada dependência</td>
  </tr> 

  <tr>
    <td>npm list -g</td>
    <td>Listar toda a arvode de dependências globais - inclusive as de cada dependência</td>
  </tr> 
  
  <tr>
    <td>npm list --depth=0</td>
    <td>Listar todas as dependências do projeto - somente as raizes </td>
  </tr> 

  <tr>
    <td>npm list -g --depth=0</td>
    <td>Listar todas as dependências globais - somente as raizes </td>
  </tr> 

  <tr>
    <td>npm link "Nome_da_Dependencia"</td>
    <td>Linka ao projeto alguma dependência que estiver instalada de forma global</td>
  </tr> 

  <tr>
    <td>npm remove "Nome_da_Dependencia"</td>
    <td>Remove ao projeto alguma dependência que estiver instalada</td>
  </tr>

  <tr>
    <td>npm remove "Nome_da_Dependencia" -g</td>
    <td>Remove ao projeto alguma dependência que estiver instalada de forma global</td>
  </tr>  

  <tr>
    <td>npm prune</td>
    <td>remove as dependências do projeto que não estão sendo utilizadas</td>
  </tr>

  <tr>
    <td>npm search "alguma-busca"</td>
    <td>Pesquisa nas libs qualquer biblioteca que tenha qualquer referência ao digitado (exemplo: react, ajax, etc)</td>
  </tr>

  <tr>
    <td>npm outdated</td>
    <td>Faz uma varredura em todas as dependências que estão desatualizadas</td>
  </tr>  

  <tr>
    <td>npm updated</td>
    <td>Atualiza a versão de todas as dependências do projeto</td>
  </tr>    

  <tr>
    <td>npm updated</td>
    <td>Atualiza a versão de todas as dependências do projeto</td>
  </tr> 

  <tr>
    <td>npm cashe verify</td>
    <td>Verificar os arquivos de Cashe do sistema (consumo, caminho, etc)</td>
  </tr>  

  <tr>
    <td>npm cashe clean --force</td>
    <td>Limpar os arquivos de Cashe do sistema</td>
  </tr>   

  <tr>
    <td>npm cashe clean --force</td>
    <td>Limpar os arquivos de Cashe do sistema</td>
  </tr>    

  <tr>
    <td>npm audit</td>
    <td>Realizar auditoria de vulnerabilidades</td>
  </tr>  

  <tr>
    <td>npm audit fix</td>
    <td>(Tenta) arrumar as vulnerabilidades do projeto - não corrige pacotes que irão quebrar o projeto</td>
  </tr>  

  <tr>
    <td>npm audit fix --force</td>
    <td>Arrumar as vulnerabilidades do projeto - Força a correção pacotes que poderão quebrar o projeto</td>
  </tr>  

  <tr>
    <td>npm view "Nome-da-Dependência"</td>
    <td>Exibe todas as informações da dependência informada</td>
  </tr> 

  <tr>
    <td>npm docs "Nome-da-Dependência"</td>
    <td>Exibe a documentação do site oficial da dependência informada (exemplo: axios, react, express)</td>
  </tr>   

  <tr>
    <td>npm home "Nome-da-Dependência"</td>
    <td>Exibe ao site oficial da dependência informada (exemplo: axios, react, express)</td>
  </tr>   

  <tr>
    <td>npm dedup</td>
    <td>Remove a duplicidade de Dependências, <a href="https://docs.npmjs.com/cli/v8/commands/npm-dedupe">Dedup</a></td>
  </tr>       

  <tr>
    <td>npm run</td>
    <td>Listar os scripts de iniciação</td>
  </tr> 

  <tr>
    <td>npm start</td>
    <td>Inicia o projeto usando o "run start"</td>
  </tr> 
  
  <tr>
    <td>node index.js</td>
    <td>Inicia uma aplicação</td>
  </tr> 
</table>

