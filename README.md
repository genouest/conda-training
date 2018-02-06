# conda-training

Conda repository with the same testing environment as [BIOCONDA repository](https://bioconda.github.io).

No upload to anaconda or quai.io repositories.

## Contributing

1. Fork the project
2. Write your recipe
3. Create a Pull Request (PR)

## Test your recipe with CircleCI

You can build and test your recipe in the same environment that bioconda with circleci client.

On your bioconda recipe directory :

`curl -o /usr/local/bin/circleci https://circle-downloads.s3.amazonaws.com/releases/build_agent_wrapper/circleci && chmod +x /usr/local/bin/circleci`

`circleci build`

