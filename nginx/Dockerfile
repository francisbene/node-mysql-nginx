# Use a imagem base do Nginx
FROM nginx:latest

# Copie o arquivo de configuração personalizado para o contêiner
COPY html /usr/share/nginx/html

# Comando para iniciar o Nginx quando o contêiner for iniciado
ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD ["nginx", "-g", "daemon off;"]

