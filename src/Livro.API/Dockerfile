FROM microsoft/dotnet:latest

ENV DOTNET_CLI_TELEMETRY_OPTOUT 1

RUN mkdir -p /app/Livro.API
COPY . /app/Livro.API
WORKDIR /app/Livro.API

EXPOSE 5000/tcp

RUN ["dotnet", "restore"]
ENTRYPOINT ["dotnet", "run", "-p", "project.json", "web"]
