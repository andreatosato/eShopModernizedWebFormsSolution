FROM mcr.microsoft.com/dotnet/framework/aspnet:4.7.2-windowsservercore-ltsc2016
ARG source
COPY . /inetpub/wwwroot
WORKDIR /inetpub/wwwroot
EXPOSE 80
COPY ${source:-obj/Docker/publish} .
