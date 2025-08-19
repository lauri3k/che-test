FROM ubuntu:latest

RUN useradd -u 1234 -G root -d /home/user --shell /bin/bash -m user
USER 1234
CMD ["tail", "-f", "/dev/null"]