# ansible-dev
A repo to develop, test and run ansible playbooks

- IP array:

    ec2instance = [
    "54.172.245.229",
    "100.25.134.223",
    "100.26.158.166",
    "100.25.104.137",
    ]

[0] of the array is the control node, the rest are conventional servers

# Configure control node (ubuntu)
sudo apt update
sudo apt install ansible
