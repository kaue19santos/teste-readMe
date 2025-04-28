# PD EAD

## 📝 Descrição

PD EAD é uma plataforma de Ensino a Distância, onde alunos podem assistir a cursos online, realizar avaliações, emitir certificados de conclusão, enquanto professores cadastram e gerenciam seus próprios cursos.

## ⚙️ Como Instalar e Executar
### 🚀 Instalando o Angular CLI
Versão recomendada: 17
O Angular CLI é necessário para o gerenciamento do projeto Angular. Para verificar a versão instalada, execute:
```bash
ng version
```
Ou instale o Angular CLI com o comando:
```bash
npm install -g @angular/cli@17
```
### 💻 Clonando o Projeto e o Executando

Passo 1: Clonar o Repositório
Para clonar o repositório em seu diretório local, execute:
```bash
git clone https://github.com/kaue19santos/teste-readMe.git 
```
<!-- LEMBRAR DE TROCAR LINK ACIMA -->
Passo 2: Navegar para o Diretório do Projeto

Acesse o diretório clonado:
```bash
cd pdEad
```
Passo 3: Executar o projeto em modo de desenvolvimento

Execute:
```bash
ng serve
```
Acesse no navegador:
```bash
http://localhost:4200
```
## 🛠️ Dependências Necessárias
Antes de iniciar o projeto, é necessário ter as seguintes dependências instaladas em sua máquina:

### 🔧 Instalar o Node.js
Certifique-se de estar usando a versão correta do Node.js especificada pelo projeto (18 ou superior), garantindo compatibilidade e funcionamento adequado. Em sistemas Windows, a execução do comando npm install pode exigir privilégios administrativos para evitar erros de instalação. Se necessário, abra o terminal com permissões de administrador.
Para verificar a versão do Node.js instalada, execute:
```bash
node -v
```
Para instalar as dependências execute o comando a seguir na pasta do projeto:
```bash
npm install
```
## 🔨 Comandos

### Build do Projeto

Para criar a versão de produção do seu projeto, execute o seguinte comando:

```bash
ng build --prod
```
Esse comando irá compilar o projeto e gerar uma versão otimizada para produção na pasta dist/.
### 📂 Acessando o Build
Após a execução do comando de build, os arquivos gerados estarão localizados na pasta dist/ dentro do seu diretório do projeto.

Para verificar se o build foi realizado com sucesso, você pode acessar a pasta e garantir que os arquivos estão presentes:

```bash
cd dist/
```
Essa pasta conterá todos os arquivos prontos para serem hospedados em um servidor de produção.

Caso queira rodar o projeto em modo de desenvolvimento para testar localmente antes do build final, execute:

```bash
ng serve
```
E acesse <http://localhost:4200> no seu navegador.

### 🛠️ Criando Componentes
Para criar um componente no Angular, você pode usar o Angular CLI com o comando `ng generate component` ou `ng g c`. O comando criará automaticamente os arquivos necessários e atualizará o módulo onde o componente será declarado.

Exemplo para criar um componente chamado `meu-componente`:

```bash
ng generate component meu-componente
```
Ou com a versão abreviada do comando:
```bash
ng g c meu-componente
```
Isso criará uma pasta meu-componente com os seguintes arquivos:

**meu-componente.component.ts:** o arquivo TypeScript do componente.

**meu-componente.component.html:** o arquivo de template HTML.

**meu-componente.component.css:** o arquivo de estilos do componente.

**meu-componente.component.spec.ts:** o arquivo de testes unitários para o componente.

### 🔧 Criando Serviços
Para criar um serviço no Angular, use o comando ng generate service ou ng g s. O serviço será criado e registrado no providers do módulo.

Exemplo para criar um serviço chamado meu-servico:

```bash
ng generate service meu-servico
```
Ou com a versão abreviada do comando:
```bash
ng g s meu-servico
```
Isso criará um arquivo meu-servico.service.ts que conterá a lógica do serviço, e o serviço será automaticamente injetado no módulo principal da aplicação, permitindo que você o utilize em outros componentes.

## Estrutura básica do projeto
![Estrutura básica](estrutura_basica.png)
### Estrutura de Pastas

- **components/**  
  Contém todos os componentes visuais reutilizáveis da aplicação. Cada componente representa uma parte da interface de usuário, como botões, cards, formulários, etc.

- **configs/**  
  Armazena arquivos de configuração da aplicação, como constantes, tokens, URLs de API, temas, entre outros valores que podem ser reutilizados globalmente.

- **models/**  
  Contém as interfaces e classes que definem a estrutura dos dados utilizados na aplicação (ex: User, Product, Response, etc). Facilita a tipagem e a manutenção do código.

- **router/**  
  Responsável por definir e organizar as rotas da aplicação. Pode incluir o arquivo de roteamento principal ou rotas específicas agrupadas por módulo ou funcionalidade.

- **services/**  
  Armazena os serviços responsáveis pela lógica de negócio e comunicação com APIs. São usados para buscar, enviar ou manipular dados no backend.

- **utils/**  
  Contém funções utilitárias ou helpers genéricos que podem ser reutilizados em várias partes do sistema, como formatações de data, máscaras, validações, etc.

## Versão do Angular utilizada
- **Angular 17.3.12:** Esta versão do Angular foi escolhida por suas melhorias em performance, segurança e escalabilidade, atendendo às demandas do projeto.
![Ícone do Angular](icon_angular.svg)




