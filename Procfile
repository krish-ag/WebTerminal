web: waitress-serve \
    --listen "*:80" \
    --trusted-proxy '*' \
    --log-untrusted-proxy-headers \
    --clear-untrusted-proxy-headers \
    --threads 4\
    "main.py --address='0.0.0.0' --port=8000"