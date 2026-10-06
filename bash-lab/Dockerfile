# Use a base image
FROM ubuntu:latest

# Copy the Bash script into the container
COPY script.sh .

# Make the script executable
RUN chmod +x script.sh

# Run the Bash script when the container starts
CMD ["./script.sh"]

