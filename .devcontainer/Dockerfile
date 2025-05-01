FROM mcr.microsoft.com/devcontainers/go:1-1.24-bookworm

RUN curl https://www.cisco.com/security/pki/certs/ciscoumbrellaroot.pem \
    -o /usr/local/share/ca-certificates/Cisco_Umbrella_Root_CA.crt \
    && update-ca-certificates
