FROM busybox

## All in entrypoint
# ENTRYPOINT ["ping", "localhost"]

## Entrypoint and CMD
# ENTRYPOINT ["ping"]
# CMD [ "localhost" ]

## Entrypoint and CMD
# ENTRYPOINT ["ping"]
# ENV ENDPOINT=localhost
# CMD [ "${ENDPOINT}" ]

## CMD with ENV variable
ENV ENDPOINT=localhost
CMD ping ${ENDPOINT}
