# Git Clone

`git clone https://github.com/nigel-sys/Blockchain_Project.git`

# Add .env file from the zip file

Include the .env file from the code zip

# Docker pull

`docker pull nigieuno/x21179158:blockchain`

## Run the curl command

ETH Transfer:

`curl --header "Content-Type: application/json" --request POST --data '{"address":"0xac4FafdA6A3A6B48b4cDC2a896acf8D104C81d6C", "amount":"0.05"}' http://localhost:8090/eth`

Token Transfer:

`curl --header "Content-Type: application/json" --request POST --data '{"address":"0xac4FafdA6A3A6B48b4cDC2a896acf8D104C81d6C"}' http://localhost:8090/token`
