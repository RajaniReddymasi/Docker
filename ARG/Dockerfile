ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG COURSE=Docker
ARG TRAINER=rajani
ARG DURATION=120HRS
ENV DURATION=${DURATION}
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}"
CMD ["sleep", "100"]