FROM gliderlabs/consul-agent:0.7.5
ADD ./config /config/
ENTRYPOINT ["/bin/consul", "agent", "-server", "-config-dir=/config"]
