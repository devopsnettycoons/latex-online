# How to build updated image

`git clone https://github.com/aslushnikov/latex-online`

Move "Dockerfile-updated" inside latex-online  

`docker build -t "fairlyai/latex-online:latest" -f Dockerfile-updated .`
