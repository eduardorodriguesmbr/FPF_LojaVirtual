# FPF_LojaVirtual
Desafio Loja Virtual

Loja virtual em ASP.NET MVC5 e EF com SQL Server.

# Tecnologias Utilizadas
- A loja virtual foi desenvolvida em c# na plataforma .net com ASP.NET MVC 5;
- Versão do .NET Framewrok: 4.7.2;
- Para persistência foi utilizado ORM Entity Framework 6; 
- Na apresentação da camada Web, as telas foram desenvolvidas no ASP.NET MVC 5 Razor + HTML5, CSS3 com bootstrap + Javascript e JQuery; 
- O banco de dados utilizado foi o SQL Server 2016 Express;


# Instruções de Instalação e uso
- Fazer o download do arquivo dist.rar e descompactar;
- Restaurar a base utilizando o backup "LojaVirtual.bak" ou criar o banco manualmente com o nome: "LojaVirtual" e executar o scritp contido no arquivo: "script-lojavirtual.sql" que encontra-se na raiz do projeto;
- Criar uma novo site no servidor web IIS apontando para os arquivos descompactados;
- Alterar a string de conexão "LojaDbContext" no arquivo Web.Config apontando para o banco criado;
- Subir a instâcia do site;
