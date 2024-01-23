# ArchMind

Objetivo: Conseguir separar diferentes audios de pessoas em clusters, sendo cada cluster todos os audios daquela pessoa.

Esse projeto tem 3 variações.

1ª - Utilizar um algoritmo de aprendizado constrativo, e em cima da representação, aplicar um algoritmo de clustering por densidade.

2ª - Caso haja algum label, conseguir fazer apenas com um algoritmo de cluster.

3ª - Algoritmo de verificação facial, transformando o audio em imagem e tentar distinguir como uma "digital / face ID" de quem fala.

## Hipóteses:

1- É possivel usar CNN para classificar as imagens do espectograma do audio ? (3)

2- Redes Recorrentes seriam uma boa opção para lidar com esse problema ?

## Requisitos:
### FFmpeg (opcional)
Será necessario instalar em sua maquina o FFmpeg, ele é um programa de computador que grava, converte e cria stream de áudio e vídeo em diversos formatos. E será necessário para conseguir automatizar a conversão dos audios em .ogg e outros formatos para o formato padrão .wav 

#### Ubuntu
```bash
sudo apt-get install ffmpeg
```
or

```bash
sudo apt install ffmpeg
```
#### Windows
[Download FFmpeg](https://ffmpeg.org/download.html)

#### Fedora:

```bash
sudo dnf install ffmpeg
```

#### CentOS/RHEL:

```bash
sudo yum install ffmpeg
```

#### Arch Linux:

```bash
sudo pacman -S ffmpeg
```

## Referencias

HILLESHEIN, Henrique. Desenvolvimento de um Sistema de Reconhecimento de Locutor Utilizando Aprendizado de Máquina. 2018. Trabalho de Conclusão de Curso (Graduação) – Engenharia de Telecomunicações, Instituto Federal de Santa
Catarina, Praia Comprida. Disponível em: <https://github.com/DehPython/ArchMind/files/13999286/TCC290_Henrique_Hilleshein.pdf>. Acesso em: 19/01/2024. Observação: Documento totalmente lido, com relevante impacto no estudo realizado.
