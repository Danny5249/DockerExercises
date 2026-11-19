# Starting with the image to pull from
FROM ubuntu:24.04


# Copy the script.sh file from this directory 
COPY script.sh .

# Installing curl and permissions to script.
RUN apt-get -y update && apt-get install -y curl
RUN chmod +x script.sh

# Run the script
CMD ["./script.sh"]