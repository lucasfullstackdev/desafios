
# Teste prático

Desenvolvedor Full Stack: Pleno

O propósito deste teste prático é avaliar suas habilidades com programação, sua capacidade de abstração, isto é, compreender a necessidade real do cliente e propor a solução que mais se adeque.

## Sobre

Realizar integração com a api pública [api de localidades](https://servicodados.ibge.gov.br/api/docs/localidades) do [IBGE](https://www.ibge.gov.br/)

Você é desenvolvedor pleno da empresa Jelly. Em uma das aplicações surgiu a necessidade de saber dados demográficos. Sua demanda é fazer uma api para  a integração com a api de localidades do ibge para servir à aplicação.

## Pontos importantes

Leve em consideração que os dados sobre cep dificilmente possuem alterações. Dito isso, fica a pergunta: **"existe alguma maneira de otimizar as consultas?"**

## Funcionalidades
- Listagem de:
	- Distritos
		- Todos
		- Distritos por UF
		- Distritos por município
	- Municípios:
		- Todos
		- Municípios por UF
		- Município por identificador

## Detalhes da aplicação

Desenvolver uma api intermediária para a realização de consultas dos municípios e distritos.

Pontos a considerar:
	- Otimização de consultas futuras
	- Tempo de processamento de consultas grandes

## Tecnologias

Utilize as tecnologias com as quais você possui maior aptidão e que ao seu ver mais se adequam ao projeto proposto.

Algumas das tecnologias com as quais trabalhamos:
- [PHP](https://www.php.net/)
- [Laravel](https://laravel.com/)
- [CodeIgniter](https://codeigniter.com/)
- [C#](https://docs.microsoft.com/pt-br/dotnet/csharp/)

## Setup

Tenha em mente que iremos testar sua aplicação com a equipe de produto da Jelly. Para isso, é fundamental que possamos subir a aplicação desenvolvida em qualquer máquina (independente da configuração).

Utilize:
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- [Dockerfile](https://docs.docker.com/engine/reference/builder/#:~:text=A%20Dockerfile%20is%20a%20text,can%20use%20in%20a%20Dockerfile%20.)
- [Variáveis de ambiente](https://www.botecodigital.dev.br/php/variaveis-de-ambiente-env-no-php/)

Caso utilize Laravel:
- [Laradock](https://laradock.io/)


## Detalhes da avalição

Crie um repositório público em seu github e envie para o e-mail: lucas.fullstack.dev@gmail.com

Duração: 3 dias
Avaliaremos (não necessariamente nesta ordem):

- Lógica
- Boas práticas de programação
- Versionamento utilizando git ([git workflow](https://pingback.com/desenvbr/git-workflow-o-que-e-e-seus-principais-tipos))
- Seu domínio sobre a ferramenta/tecnologia

Para que você seja melhor avaliado tenha em mente que este é apenas um MVP (Minimun viable product) não se preocupe tanto com o polimento, o foco deve ser na compreensão e resolução do problema seguindo boas práticas.

## Pontos que poderão lhe favorecer

- Arquitetura proposta
- Boa comunicação
- [PSR's](https://www.php-fig.org/psr/) (caso utilize PHP)
- Utilização de [migrations](https://medium.com/@joelrodrigues/o-que-s%C3%A3o-database-migrations-f817448870a2)
- Utilização de algum framework







