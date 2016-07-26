# revealgo-docker

Run the [revealgo](https://github.com/yusukebe/revealgo) in a docker container.

# Usage

~~~~
cd your_slide_directory
docker run -it --rm -p 3000 -v `pwd`:/revealgo xmisao/revealgo test.md
~~~~
