![Apostila de Git e GitHub](https://user-images.githubusercontent.com/69727594/139169656-3b19bfa2-6a3e-4709-974d-ee780e22f38f.png)
## Apostila de GIT e GitHub

Opa, tudo bem?
Resolvi criar essa apostila para ajudar os alunos da turma do #OTechTáOn 🥰

Nela, você vai aprender sobre:
- [🎨 Como personalizar o seu README](#como-personalizar-o-seu-readme)
- [👩🏻‍💻 Como puxar um arquivo para o GIT](#como-puxar-arquivos-do-git-para-o-github)

Espero que goste e que eu consiga te ajudar, estou aceitando feedbacks de melhorias sempre!
#


![Como personalizar o seu README](https://user-images.githubusercontent.com/69727594/139169703-389698a8-c38b-4c5e-b4e7-f47bbbc485be.png)
## Como personalizar o seu README ([🔝 Voltar ao topo](#apostila-de-git-e-github)
Você já deu uma olhada no meu? Se não, clica [nesse link](https://github.com/becabelin) para ver.

E aí? Gostou? Quer aprender a fazer?
Então segue o passo a passo (bem detalhado) abaixo! 😁

### 1. Crie um novo repositório

![Sem título](https://user-images.githubusercontent.com/69727594/139258753-f915f3f3-fda3-4e1f-aa0d-bb8936130d8a.png)


### 2. Na seção de nome do repositório, coloque o SEU nick do GitHub

(Ex: se o seu nome for *fulanodetal*, coloque no repositório o nome *fulanodetal*)
> Você vai saber que escreveu seu nick corretamente quando aparecer esse textinho
   
![image](https://user-images.githubusercontent.com/69727594/139166556-3a1a9860-b4f3-475a-a455-004286cb92f1.png)

### 3. Marque para adicionar o arquivo README

![](https://user-images.githubusercontent.com/69727594/139163865-357a6fbd-3bf2-4c47-b0ab-663150debdb1.png)

### 4. Depois de criado o arquivo, clique no lápis onde eu sinalizei em vermelho para você. Ele vai te levar para a edição do arquivo.

![](https://user-images.githubusercontent.com/69727594/139164296-0ae2426d-ed14-44fd-a9ec-5443607ed1cd.png)

### 5. Escreva o que você quiser! Caso queira deixar **mais personalizado**, tem umas dicas aqui!
> Para mais opções de personalização, recomendo que acesse esse [link](https://docs.github.com/pt/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#headings).

#### - Títulos
Para criar um título, adicione de um a seis símbolos # antes do texto do título. O número de # que você usa vai determinar o tamanho do título.
```
# O título maior
## O segundo maior título
### O terceiro maior título
###### O título menor
```
![image](https://user-images.githubusercontent.com/69727594/139165124-7fc7fb6e-db3b-4974-8e76-d9cc378f7997.png)


#### - Negrito, itálico e outros

| Estilo  |  Sintaxe  |  Exemplo  |  Resultado  |
| :---: | :---: | :---: | :---: |
|  Negrito |  `** **` ou `__ __` |  `**Esse texto está em negrito**` |  **Esse texto está em negrito** |
|  Itálico |  `* *` ou `_ _` |  `*Esse texto está em itálico*` |  *Esse texto está em itálico* |
|  Tachado |  `~~ ~~` |  `~~Esse texto estava errado~~` |  *~~Esse texto estava errado~~* |


#### - Listas
Você pode criar uma lista não ordenada colocando - ou * antes do seu texto.
```
- Batata
- Arroz
- Carne
```

- Batata
- Arroz
- Carne

Para ordenar a lista, coloque um número na frente de cada linha.
```
1. Batata
2. Arroz
3. Carne
```

1. Batata
2. Arroz
3. Carne


#### - Emojis
Você pode adicionar emojis digitando ```:NOMEDOEMOJI:```
> Maaaas, caso você esteja no Windows, pode apertar as teclas *`Windows` + `R`* que vai abrir uma lista de emojis! 🤯


#### - Badges
Provavelmente essa é a parte mais legal e que vocês mais querem fazer, certo?

🤷🏻‍♂️: Rebeca? O que é badge?

Bom, badge é isso:

![](https://user-images.githubusercontent.com/69727594/139167235-6f1ae6d3-c099-4eba-886b-dafa89fcbc21.png)

🤷🏻‍♂️: Uau, muito daora, dá uma colorida legal no README!

Nesse [link](https://github.com/alexandresanlim/Badges4-README.md-Profile) aqui, você vai encontrar **várias badges personalizadas**, tanto de contato como softwares e linguagens de programação.

🤷🏻‍♂️: Ok, mas como colocá-las para aparecer no meu README?

Para mostrar o badge no seu perfil, você precisa entender que ele é uma *imagem*. Você pode simplesmente colar a imagem aqui no código, mas não vai ficar tão legal, né? Para deixar bonitinho e aparecer o *título da imagem* quando você passar o mouse em cima do badge, você pode usar ```title```.

🤷🏻‍♂️: Tá, mas como eu faço tudo isso?

É bem tranquilo, você deve usar o código: ```<img src="SEU-LINK" title="SEU-LINK">``` ou ```![TÍTULO]({SEU-LINK})```, substituindo *SEU-LINK* e *título* pelo link e nome certos, claro.

Aqui vai um exemplo da badge do VS Code:

```<img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code" title="VS Code">```

![](https://user-images.githubusercontent.com/69727594/139168041-c69bb5b1-2d43-4bbf-a20c-10b0c6ff517d.png)

Muito legal, né? Inclusive, como eu já falei antes, no [link](https://github.com/alexandresanlim/Badges4-README.md-Profile) que eu botei acima, tem **muitas outras badges super legais**. Todos os parabéns para o [@alexandresanlim](https://github.com/alexandresanlim) e a galera que ajudou ele! 👏🏻

#
![](https://user-images.githubusercontent.com/69727594/139171071-116e820f-afb8-4466-87f9-93e7326874e9.png)

## Como puxar arquivos do GIT para o GitHub ([🔝 Voltar ao topo](#apostila-de-git-e-github)
Quer puxar um arquivo direto para o GitHub pelo GIT e não sabe como? Siga os passos abaixo!
> Só vale se você criou um arquivo/projeto no seu navegador!

> Ainda não tem o GIT no seu computador? Baixe-o clicando neste [link](https://git-scm.com/downloads). 

### 1. Crie um novo repositório

![Sem título](https://user-images.githubusercontent.com/69727594/139258753-f915f3f3-fda3-4e1f-aa0d-bb8936130d8a.png)

### 2. Coloque o nome do repositório que você desejar (lembre-se de o nome estar escrito corretamente (sem espaços!)

![](https://user-images.githubusercontent.com/69727594/139245751-59012a7b-b2d2-445c-8c73-60189186527e.png)

### 3. Clique em *Create repository*

![](https://user-images.githubusercontent.com/69727594/139245961-35d153d0-3309-4d0f-b341-32144fc2b2ac.png)

### 4. Ao criar um repoositório, essa tela (só que com as suas informações) vai aparecer para você.

![](https://user-images.githubusercontent.com/69727594/139246104-0226a95d-fe3e-4d8d-9a79-e67c222aee8e.png)
> Você pode enviar um arquivo clicando em ```uploading an existing file```, mas que tal tentar usando a linha de comando?

### 5. Abra a pasta/local onde estão os arquivos que você quer mandar para o GIT

![](https://user-images.githubusercontent.com/69727594/139246706-8e5f06bc-e769-4460-8191-66777bc62c51.png)

### 6. Com o botão direito do mouse, clique em qualquer lugar da pasta (exceto nos arquivos) e selecione a opção *Open GIT Bash here*

![](https://user-images.githubusercontent.com/69727594/139247076-5756b640-8a54-4fba-80a8-8f5783e20e4b.png)

> Caso você esteja no Windows 11 e essa opção não apareça para você, ao clicar com o botão direito, clique em *Mostrar mais opções*.
> 
> Agora, se nenhuma opção do GIT aparecer, certifique-se de que você instalou o GIT corretamente.

### 7. Quando você clicar para abrir o GIT Bash, essa tela aparecerá para você (com as suas informações)

![](https://user-images.githubusercontent.com/69727594/139247411-6abaf750-15af-4c07-a9c8-157252f699da.png)

### 8. Digite o comando ```git init``` para iniciar o GIT
> Provavelmente isso aparecerá na sua tela:

![](https://user-images.githubusercontent.com/69727594/139247613-c162cea4-632a-4f1f-9b24-c81b164d3006.png)

### 9. Adicione os arquivos que deseja que entrem no seu repositório
Você pode digitar ```git status``` para saber quais arquivos estão disponíveis para serem comitados
![](https://user-images.githubusercontent.com/69727594/139248740-47f64365-cc7c-431d-ab5b-22bd60d93762.png)

Caso queira adicionar todos os arquivos de uma vez, digite ```git add .```. Se quiser adicionar apenas um, digite ```git add nomedoarquivo``` com o nome do arquivo que você deseja anexar.

No meu caso, eu dei ```git add .``` e adicionei todos de uma vez.

### 10. Agora é a hora de dar o seu commit!
🤷🏻‍♂️: Quê? O que é um commit?

Segundo o nosso pai Wikipedia, commit *refere-se ao processo de tornar permanente um conjunto de alterações, ou seja, de efetivar as alterações*. Traduzindo: o commit permite que você guarde todas as suas alterações naquele momento, ou seja, você consegue guardar o estado do seu repositório.

Digite ```git commit -m```, escreva o seu primeiro commit e dê enter (não se esqueça das aspas!)
Veja como eu escrevi:

![](https://user-images.githubusercontent.com/69727594/139248678-6a41d433-a9fe-4184-ab7b-0b460ecbafaa.png)

### 11. Volte para o GitHub e copie as 3 últimas linhas de comando

![](https://user-images.githubusercontent.com/69727594/139248903-707c2e33-58c8-42dd-8b4b-d241f52baf1c.png)

### 12. Cole as três linhas no seu GIT, dê enter e seja feliz!

![](https://user-images.githubusercontent.com/69727594/139249015-cc445be2-79ca-449d-9a80-47999daa8a96.png)

> Se der algum erro durante o passo a passo para você, certifique-se de que seguiu todos os passos corretamente!

> Caso ainda esteja com erros, me mande uma mensagem, quem sabe eu não posso te ajudar? 😉

### 13. Recarregue sua página no GitHub
Você verá que seus arquivos já estarão dentro do seu repositório do GitHub, eba! 🥳

Agora, já sabe, né? Não se esqueça de praticar, que tal fazer isso com todos os seus arquivos de agora em diante? Quem não pratica, não aprende!


![](https://user-images.githubusercontent.com/69727594/139257471-6da05d16-5eef-4dc6-8234-278ccbc2030d.png)
Espero que você tenha gostado do conteúdo e que eu tenha conseguido te ajudar com o GIT e o GitHub, sério. 🥺

Agradecimentos:
- [Alura](https://www.alura.com.br) e sua equipe de professores, por todo o conhecimento ensinado

Créditos e fontes:
- [GitHub](https://docs.github.com/pt/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists)
- [Badges4-README.md-Profile](https://github.com/alexandresanlim/Badges4-README.md-Profile)
