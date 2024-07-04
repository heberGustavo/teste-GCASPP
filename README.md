<h1 align="center">
  CRUD - Funcionários and Filhos
</h1>

<p align="center">
  This is a system to register Funcionarios and Filhos.  The inicial screen is Funcionario register, accessing the menu in item "Filhos" you can do register between Filho and Funcionario.
</p>


</br>
  
<p align="center">
  <a href="#globe_with_meridians-Technologies-and-Concepts-Implemented">Technology</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
   <a href="#gear-Architecture">Architecture</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
   <a href="#round_pushpin-demo">Demo</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#wrench-How-to-use">How to use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-Licence">Licence</a>
</p>

## :globe_with_meridians: Technologies and Concepts Implemented

This project was developed using:

- ASP NET Core MVC 3.1
- Dapper 2.0
- SQL Server
- AutoMapper 11.0.0
- HTML and CSS
- Bootstrap
- jQuery

Concepts/Techniques used in:
- Data Transfer Object [DTO]
- Repository Pattern
- Dependency Injection

## :gear: Architecture

```🌐
src
├── 📂 0- Portal
|   ├── 📂 Controllers
|   ├── 📂 Utils
|   ├── 📂 Views
├── 📂 1- Domain
|   ├── 📂 Business
|   ├── 📂 IBusiness
|   ├── 📂 IRepository
|   ├── 📂 Models
├── 📂 2- Data
|   ├── 📂 EntityData
|   ├── 📂 Repository
├── 📂 3- Utils
|   ├── 📂 Commom
|   ├── 📂 CrossCutting
├── 📂 4- Migration
|   ├── 📂 Scripts

```

## :round_pushpin: Demo
![image](https://github.com/heberGustavo/teste-GCASPP/assets/44476616/57ba94c1-43b2-4a63-9682-ac9bc11cfd2d)


## :wrench: How to use

Clone that application using [Git](https://git-scm.com) and follow the next steps:

```bash
# 1. Clone this repository
$ git clone https://github.com/heberGustavo/teste-GCASPP.git

# 2. Open the project in Visual Studio

# 3. Execute the build

# 4. Change the Connection String. To modify follow this path:
  4.1 - Portal > Teste.Portal > appsettings.json
  4.2 - Create a new database in SQL SERVER
  4.3 - Modify the value to "CONNECTION_STRING" and "CONNECTION_STRING_DEBUG"
  4.4 - Select all items in: Migration > Scripts. Right click, select "Properties", under "Build Action" select "Embedded Resource"

# 5. Run the application

```


## :memo: Licence 
This project is under the MIT license. See the [LICENSE](https://github.com/heberGustavo/teste-GCASPP/blob/main/LICENSE) for more information.


## Autor

| [<img src="https://avatars.githubusercontent.com/u/44476616?v=4" style="max-width: 100%;width: 90px;"><br><sub>Heber Gustavo</sub>](https://github.com/heberGustavo) |
| :---: |
|[Linkedin](https://www.linkedin.com/in/heber-gustavo/)|

