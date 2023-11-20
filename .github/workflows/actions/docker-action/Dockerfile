FROM node:bullseye-slim
COPY entrypoint.sh /app/entrypoint.sh
RUN chmod +x /app/entrypoint.sh && \
    apt-get -y update && \
    apt-get install -y bash git curl jq
ENTRYPOINT ["/app/print_values.sh"]
