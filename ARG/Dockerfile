ARG version
#docker build -t arg:1.2.0 --build-arg version=9 .
FROM almalinux:${version:-8}
ARG COURSE="Devsecops"\
    TRAINER="Siva"\
    DURATION="150 HRS"
RUN echo "Trainer is:${TRAINER},version is:${version}"
CMD ["sleep","200"]
