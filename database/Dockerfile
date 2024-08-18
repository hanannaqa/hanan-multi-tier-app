# Use the official PostgreSQL image as the base
FROM postgres:latest

# Set environment variables
ENV POSTGRES_USER=hanan
ENV POSTGRES_PASSWORD=1234hanan
ENV POSTGRES_DB=hanan_db

# Expose the PostgreSQL port
EXPOSE 5432
# Mount a volume for persistent data storage
VOLUME /var/lib/postgresql/data
# Start PostgreSQL
CMD ["postgres"]
