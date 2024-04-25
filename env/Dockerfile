FROM bitnami/kubectl
USER root
WORKDIR /home
ENV GROUP ""
COPY JUPYTER /home/
COPY run.sh /home/
EXPOSE 5810 5811 5812
ENTRYPOINT ["bash", "run.sh"]
