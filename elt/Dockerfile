FROM python:3.8-slim

# Install specific version of PostgreSQL client tools
RUN apt-get update && apt-get install -y postgresql-client

# Copy the ELT script 
COPY elt_script.py .

# Set the default command to run the ELT script
CMD ["python", "elt_script.py"]