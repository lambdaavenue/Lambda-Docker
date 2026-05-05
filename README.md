build dockerfile: docker build -t lambda .

run lambda full node + electrumx: sudo docker run -it -p 50012:50012 --name lambda-container lambda /bin/bash
