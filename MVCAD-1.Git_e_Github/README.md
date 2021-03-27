## Exemplificar o processo de utlização do git-github

![image](https://user-images.githubusercontent.com/60848932/94346796-68526980-0005-11eb-83e0-5e723794006b.png) </br>


### Diferença dos repositorios:
- O repositório local é o que fica na sua máquina. (git) 
- O repositório remoto é o que fica na nuvem (github).</p></br>

![image](https://user-images.githubusercontent.com/60848932/94346763-2de8cc80-0005-11eb-873e-29a04b73e7bd.png) </br>


### Comandos básicos <br>
 
#### Consultar a versão do git pelo git bash: <br>
 ```git --version``` <br>
![image](https://user-images.githubusercontent.com/60848932/94345480-89fb2300-fffc-11ea-8f7e-1fe15393db26.png)

#### Configurar seus dados no Git: <br>
```git config --global user.name <seu nome> ``` <br>
```git config --global user.email <seu e-mail> ``` <br>
![image](https://user-images.githubusercontent.com/60848932/94345509-bc0c8500-fffc-11ea-9b03-b6d091791109.png)

 #### Acessar diretorio do seu projeto:<br>

```mkdir <nome da pasta>```
```touch <nome do arquivo>```
```cd <nome da pasta>```
```ls```
</br> 
* <strong>mkadir 'nome_pasta'</strong> (cria pasta/diretorio) </br> 
* <strong>touch 'nome_arquivo'</strong>  (cria um arquivo) </br> 
* <strong> cd 'caminho'</strong>  (executa uma movimentação entre diretorios) </br> 
* <strong>ls</strong>  (lista os arquivos de um diretorio) </br> 

![image](https://user-images.githubusercontent.com/60848932/94346195-62f32000-0001-11eb-8a78-400a34a9ac53.png) </br> 
![image](https://user-images.githubusercontent.com/60848932/94345800-e52e1500-fffe-11ea-9066-f987a342fd4f.png) </br> 


#### Inicialize o repositório git. <br>

```git init``` </br> 
![image](https://user-images.githubusercontent.com/60848932/94346868-fc243580-0005-11eb-90af-04ef67466d3b.png) </br> 


#### Verifique suas alterações no arquivo <br>

```git status``` </br> 
* <p> <strong>git status</strong>  (consulta o status do diretorio no git) </p>

<br> ![image](https://user-images.githubusercontent.com/60848932/94346895-24139900-0006-11eb-949f-efe1cac5204b.png) </br> 
<strong>obs.:</strong> Os arquivos estão em vermelho porque não foram adicionados no git ainda.

#### Para que o arquivo seja monitorado pelo git

``` git add <nome do arquivo>```
``` git add . <nome do arquivo>```
``` git add -A <nome do arquivo>``` </br> 
* O <strong>'git add arquivo'</strong> adiciona somente o arquivo mensionado.</br> 
* O <strong>'git add .'</strong> e o <strong>'git add -A'</strong> adicionam todos os arquivos do diretorio. </br> 

![image](https://user-images.githubusercontent.com/60848932/94349170-a0af7300-0018-11eb-8be7-7c6e09db4f1a.png) </br>

<strong>obs.:</strong> Quando eu adicionei o arquivo Animes eu usei o <strong>'git add arquivo'</strong> </br> 
E os outros arquivos ainda ficaram faltando, então executei o <strong>'git add .'</strong> </br> 
e todos os que estavam vermelhos foram adicionados e ficaram verdes. </br> 


#### Para gravar suas alterações no arquivo.

``` git commit -m "Inicializando arquivo" ```
ou ```git add . ``` </br> 

![image](https://user-images.githubusercontent.com/60848932/94349474-0b61ae00-001b-11eb-9206-dc3042614094.png) </br> 
<strong>obs.:</strong> E importante realizar o commit, coloque uma mensagem objetiva que deixe claro qual alteração foi feita.   

#### Consultar o log dos commits

```git log ``` </br> 
<strong> 'git log' </strong> é usado para consultar as informações que foram gravadas no commit. </br> 
![image](https://user-images.githubusercontent.com/60848932/94349534-81feab80-001b-11eb-958d-67e5e26ab0f8.png)

#### Crio o arquivo gitignore e adiciolo ele ao meu git

```.gitignore``` </br> 
<p><strong> '.gitignore'</strong>  e um arquivo sem extersão que deve ser criado dentro da pasta do projeto.</br>
Nele é adicionado: os arquivos, modulos e programas, que estão dentro da pasta e não vão ser manipulados pelo git.
Dentro do arquivo, você deve colocar o nome dos arquivos que deseja ignorar  </p> </br>

![image](https://user-images.githubusercontent.com/60848932/94349641-cfc7e380-001c-11eb-940c-0cf20c20e78e.png) 

<p> Depois de criar o arquivo eu volto no meu git bash e adiciono ele:</br> 
Consultei: <strong> o status, adicionei ele, realizei um um commit e consultei o log da gravação. </strong>  </p> </br>

![image](https://user-images.githubusercontent.com/60848932/94349763-0c480f00-001e-11eb-9b70-fd0732af2fd7.png) </br>

![image](https://user-images.githubusercontent.com/60848932/94349933-aa88a480-001f-11eb-9b4a-e48c24e22d09.png)

![image](https://user-images.githubusercontent.com/60848932/94349965-ffc4b600-001f-11eb-9006-82b15720af10.png)

![image](https://user-images.githubusercontent.com/60848932/94350051-cf314c00-0020-11eb-87bc-26be05622215.png)

![image](https://user-images.githubusercontent.com/60848932/94350110-4c5cc100-0021-11eb-8379-2f9e214af41d.png)

![image](https://user-images.githubusercontent.com/60848932/94350171-0eac6800-0022-11eb-9092-3069508c766b.png)

![image](https://user-images.githubusercontent.com/60848932/94350183-33a0db00-0022-11eb-93e1-dabc46fc8451.png)

Meus arquivos foram adicionados no repositorio do github:
![image](https://user-images.githubusercontent.com/60848932/94350255-ea9d5680-0022-11eb-98fa-07ebb7b1144e.png)

Clonar um repositorio di github para a minha maquina:
primeiro eu copio link do repositorio
![image](https://user-images.githubusercontent.com/60848932/94350314-7d3df580-0023-11eb-8139-8c965f801cd9.png)

git clone </br> 
![image](https://user-images.githubusercontent.com/60848932/94350370-0bb27700-0024-11eb-8376-365e47f98eb8.png)


consulto o diretorio para ver se ta tudo igual
![image](https://user-images.githubusercontent.com/60848932/94350390-487e6e00-0024-11eb-83d6-0d164a79a00a.png)


#### Branch

consultar branch
![image](https://user-images.githubusercontent.com/60848932/94350466-f68a1800-0024-11eb-9b0b-61e912eb8b68.png)

criei a branch teste, consulte e acessei ela
![image](https://user-images.githubusercontent.com/60848932/94350579-cbec8f00-0025-11eb-812f-d419f5e3883b.png)

retornei para branch master, apaguei a branch teste e consultei as branch
![image](https://user-images.githubusercontent.com/60848932/94350672-ed01af80-0026-11eb-8005-978f6d6d1985.png)

criei a brach new com o checkout -b e adicioneo os arquivos com git add . consultei o status e execute o commit 
![image](https://user-images.githubusercontent.com/60848932/94350729-6bf6e800-0027-11eb-8453-a7e86a608e1a.png)

#### Branch MASTER MERGING

Retornei para a branch master fiz uma alteração, voltei para a branch new 
![image](https://user-images.githubusercontent.com/60848932/94350965-546d2e80-002a-11eb-96c2-443615c99a96.png)

fiz uma alteraçao na brach new, adcionei e realizei commit
![image](https://user-images.githubusercontent.com/60848932/94351002-aa41d680-002a-11eb-806c-e3201f811af3.png)

Um Merge da brach master com a new
![image](https://user-images.githubusercontent.com/60848932/94351097-99459500-002b-11eb-8d10-7f6208b2ed61.png)

acesso o arquivo e consulto os dados: </br> 
![image](https://user-images.githubusercontent.com/60848932/94351063-4075fc80-002b-11eb-9d6c-6929b49fc38b.png)


Foi revisado o conteudo do arquivo e adicionada a alteração e commitado e depois feita a mesclagem
![image](https://user-images.githubusercontent.com/60848932/94351291-9cda1b80-002d-11eb-87a4-1971ee079213.png)

depois de executar a mesclagem eu executei o commit  e o git push para subir a alteração no github:
![image](https://user-images.githubusercontent.com/60848932/94351348-2a1d7000-002e-11eb-8c27-2fc749068317.png)


