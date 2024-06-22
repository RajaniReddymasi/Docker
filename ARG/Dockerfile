ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG COURSE
ARG TRAINER
RUN echo "Course is: ${COURSE:-DevOPS}, Trainer is: ${TRAINER:-shiva}"
CMD ["sleep", "100"]