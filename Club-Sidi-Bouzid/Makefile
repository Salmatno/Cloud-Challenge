.PHONY: build deploy-infra deploy-site

build:
    sam build

deploy-infra:
    sam build && sam deploy

deploy-site:
    aws s3 sync ./resume-site s3://salma-tanaoui-website