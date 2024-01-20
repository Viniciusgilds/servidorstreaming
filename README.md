# Servidor streaming local com NGINX

# Requisitos

- Docker
- OBS

# Tecnologias

- Docker compose
- NGINX

# Executando os comandos 

- 1 Suba um container no terminal do visual code
```
docker-compose up --build
```
- 2 Abra o OBS, vá em Configurações > Transmissão > Servidor
```
rtmp://localhost:1935/live
```
- Inicie a gravação

# Assistindo a transmissão 

- Baixa a extensão HLS no google chrome https://chromewebstore.google.com/detail/native-hls-playback/emnphkkblegpebimobpbekeedfgemhof

```
http://localhost:8081/live/.m3u8
```
