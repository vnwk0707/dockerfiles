ARG version
FROM almalinux:${version:-9}
ENV course="Devops with AWS" \
    trainer="venkat" \
    duration="120HRS"
#here user1 is key, someuser is default value
ARG USERNAME=Chowdary    
RUN echo "Hello User: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]