ARG VARIANT=8.0
FROM mcr.microsoft.com/dotnet/sdk:${VARIANT}

ENV PATH $PATH:/home/vscode/.dotnet:/home/vscode/.dotnet/tools

RUN dotnet workload install wasm-tools