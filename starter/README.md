# CD12352 - Infrastructure as Code Project Solution
# [Nam Nguyen]

## Spin up instructions
./create.sh [stackName1] network.yml network-parameters.json
./create.sh [stackName2] udagram.yml udagram-parameters.json

## Update instructions
./update.sh [stackName1] network.yml network-parameters.json
./update.sh [stackName2] udagram.yml udagram-parameters.json

## Tear down instructions
./delete.sh [stackName1] network.yml
./delete.sh [stackName2] udagram.yml

## Other considerations
Load Balancer DNS: 	http://udagr-WebAp-8I8BQX7O22NB-773021301.us-east-1.elb.amazonaws.com