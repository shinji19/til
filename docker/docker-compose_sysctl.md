# docker-composeでsysctlを変更する

    sysctls:
      - net.ipv4.tcp_keepalive_intvl=10
      - net.ipv4.tcp_keepalive_probes=4
      - net.ipv4.tcp_keepalive_time=10
