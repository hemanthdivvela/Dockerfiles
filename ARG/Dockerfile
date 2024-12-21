ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG COURSE=Docker
ARG TRAINER=Hemanth
ENV Duration=120HR
ARG Duration=${DURATION}
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}}, Duration is ${DURATION}}"
CMD [ "sleep", "100" ]
