# Livro.API - ASP.NET Core 1.0 Server

API criada para trabalho da disciplina Arquitetura de Backend e Microsserviços do curso de pós graduação em Arquitetura de Software Distribuído PUC Minas.

## Run

Linux/OS X:

```
sh build.sh
```

Windows:

```
build.bat
```

## Run in Docker

```
cd src/Livro.API
docker build -t Livro.API .
docker run -p 5000:5000 Livro.API
```
