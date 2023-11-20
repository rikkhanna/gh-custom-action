FROM node:bullseye-slim
COPY print_values.sh /app/print_values.sh
RUN chmod +x /app/print_values.sh && \
    apt-get -y update && \
    apt-get install -y bash git curl jq
ENTRYPOINT ["/app/print_values.sh"]
