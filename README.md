# Docker Image Template


> **Warning**:
> This is a template document. Remember to **remove** all text in _italics_ and **update** Dockerfile, REPO_NAME, REGISTRY variables and links/badges to the acual name of your GitHub repository!!!

<!--- Pick Cloud provider Badge -->
<!---![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white) -->
<!---![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) -->
<!---![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) -->
<!---![Snowflake](https://img.shields.io/badge/-SNOWFLAKE-249edc?style=for-the-badge&logo=snowflake&logoColor=white) -->
<!---![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white) -->

<!--- DockerHub Badges -->
<!--- Replace repository name -->
![Docker Image Version (latest by date)](https://img.shields.io/docker/v/getindata/docker-image-template?arch=amd64&logo=docker&sort=date&style=for-the-badge)
![Docker Image Size (latest by date)](https://img.shields.io/docker/image-size/getindata/docker-image-template?logo=docker&sort=date&style=for-the-badge)
![Docker Pulls](https://img.shields.io/docker/pulls/getindata/docker-image-template?logo=docker&style=for-the-badge)

<!--- Build Badges -->
<!--- Replace repository name -->
[![build test scan docker images](https://github.com/getindata/docker-image-template/actions/workflows/pr_opened.yml/badge.svg)](https://github.com/getindata/docker-image-template/actions/workflows/pr_opened.yml)
[![create new release with changelog](https://github.com/getindata/docker-image-template/actions/workflows/release.yml/badge.svg)](https://github.com/getindata/docker-image-template/actions/workflows/release.yml)

<!--- Replace repository name -->
![Docker](https://badgen.net/badge/icon/docker?icon=docker&label)
![License](https://badgen.net/github/license/getindata/docker-image-template/)
![Release](https://badgen.net/github/release/getindata/docker-image-template/)

<p align="center">
  <img height="150" src="https://getindata.com/img/logo.svg">
  <h3 align="center">We help companies turn their data into assets</h3>
</p>

---
## _How to use this template:_
* _use this template -> create a new repository_
* _update Dockerfile and its dependencies in [app](./app) folder_
* _create new repository in your docker registry (by default: gcr.io/getindata-images-public/app)_
* _adjust variables `REGISTRY_*` in [.github/workflows/*.yml](./.github/workflows) based on https://github.com/marketplace/actions/docker-login#usage_
* _create github secret `REGISTRY_PASSWORD` with password value with read&write permissions for your docker registry_
* _push your changes as pull request into main/master branch_
* _label your changes as `release/major` `release/minor` `release/patch` based on the desired release update_
* _once pull request will be merged, it will trigger new release with new image tagged with symantic version available in changelog_

_Brief Description of Docker Image:_

* _What it does_
* _What technologies it uses_

## USAGE

_Example usage of the Dockerfile_

```shell
docker run --rm app:v1.0.0
```

## NOTES

_Additional information that should be made public, for ex. how to solve known issues, additional descriptions/suggestions_

## EXAMPLES

- [app](app)

## CONTRIBUTING

Contributions are very welcomed!

Start by reviewing [contribution guide](CONTRIBUTING.md) and our [code of conduct](CODE_OF_CONDUCT.md).

After that, start coding and ship your changes by creating a new PR.

## LICENSE

Apache 2 Licensed. See [LICENSE](LICENSE) for full details.

## AUTHORS

<!--- Replace repository name -->
<a href="https://github.com/getindata/REPO_NAME/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=getindata/REPO_NAME" />
</a>

Made with [contrib.rocks](https://contrib.rocks)
