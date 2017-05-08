<p align="center">
<img src="http://up.mackenzie.br/fileadmin/CONFIGURACOES/SITES/UP_MACKENZIE/Resources/Public/Icons/Touch/196.png" width="140px">
</p>

# O que é o Macklabs Organizational System
É um sistema que tem como objetivo organizar todas as informações de equipamentos e tarefas do suporte técnico acadêmico do mackenzie, entre algumas funcionalidades, estão:
* Organização de Ativos.
* Manutenção de Ativos.
* Salas livres para estudo em laboratorios.
* Empréstimo de ativos
* Softwares
* Informações dos técnicos e dos laboratorios de informatica

`Ultima atualização: 08/05/2017`

## Infraestrutura e desenvolvimento
Será desenvolvido apartir de um Hyper-v com windows server 2012, com a intenção de compartilhar ela em algum servidor fisico e linkar o dominio já criado para esse servidor, agilizando o desenvolvimento.
* <strong>Dominio disponibilizado</strong>: macklabs.mackenzie.br;
* <strong>Desenvolvimento Front-End</strong>: Bootstrap 3;
* <strong>Desenvolvimento Back-end</strong>: Framework Ruby on Rails 5;
* <strong>Database</strong>: MySql;
* <strong>Servidores</strong>: Puma/Ngnix;
* <strong>Repositório</strong>: https://Jairodrigues@gitlab.com/Jairodrigues/macklabs_organizational_system.git
* <strong>Gems</strong>: Devise, Cancancan, Rails Admin

`Ultima atualização: 08/05/2017`

## Metodologia de Trabalho
O Desenvolvimento desse software segue as boas práticas de desenvolvimento com Scrum, agilizando processos e entregando conteúdo no menor tempo possivel. Seguindo o cronograma:
* Reuniões de Sprint : Reunião para definia a proxima funcionalidade a ser implementada, realizada 15 em 15 dias.
* Reuniões de Review: Realizada no final da implementação de cada funcionalidade.
* Link do Trello para acompanhamento : https://trello.com/b/jKsn2ETX/macklabs-organizational-system
* App BrandStorming : http://realtimeboard.com

`Ultima atualização: 08/05/2017`

## Prototipação
Para a prototipação de cada funcionalidade, será utilizada as seguintes ferramentas:
* Prototipação : https://wireframepro.mockflow.com/view/Db37db74eae7f4594e8ed5aa166b98727
* Usabilidade : http://marvelapp.com
* modelagem bd: http://dbdesigner.net/designer/schema/87396

`Ultima atualização: 08/05/2017`

## Página de Teste
Página criada para testes e acompanhamento de novas features.
* (https://mosystem.herokuapp.com) : Locada em www.heroku.com

`Ultima atualização: 08/05/2017`

#### Para criar o ambiente para o desenvolvimento, use o Docker:

Pre-requisite: Install and set up [docker](https://docs.docker.com/engine/installation/) on your machine.

`Ultima atualização: 08/05/2017`

### Docker
Siga as orientações da documentação no link abaixo para configurar o ambiente ruby on rails.

[![Doctor.Docker](https://d207aa93qlcgug.cloudfront.net/1.95.5.qa/img/nav/docker-logo-loggedout.png)](https://hub.docker.com/_/rails/)

<strong> Caso tenha alguma dúvida, veja esse video:</strong>
* http://onebitcode.com/page/2/

`Ultima atualização: 08/05/2017`

### Para clonar o projeto para seu computador, use o git:
Clone and Macklabs Organizational System:

```
> git clone https://Jairodrigues@gitlab.com/Jairodrigues/macklabs_organizational_system.git
> cd macklabs_organizational_system
> git init
> git add .

```
`Ultima atualização: 08/05/2017`

### Equipe
Caso queira participar, entre em contato com um dos participantes do projeto:
* Paulo - Product Owner
* Jairo - Scrum master
* Everton - Developer

`Ultima atualização: 08/05/2017`
