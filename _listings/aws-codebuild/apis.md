---
name: AWS CodeBuild
x-slug: aws-codebuild
description: AWS CodeBuild is a fully managed build service that compiles source code,
  runs tests, and produces software packages that are ready to deploy. With CodeBuild,
  you don&rsquo;t need to provision, manage, and scale your own build servers. CodeBuild
  scales continuously and processes multiple builds concurrently, so your builds are
  not left waiting in a queue. You can get started quickly by using prepackaged build
  environments, or you can create custom build environments that use your own build
  tools. With CodeBuild, you are charged by the minute for the compute resources you
  use.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Build
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/aws-codebuild/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CodeBuild API Batch Get Builds
  x-api-slug: aws-codebuild-api
  description: Gets information about one or more builds.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: ://///?Action=BatchGetBuilds
  tags: Builds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/aws-codebuild/actionbatchgetbuilds-get-openapi.md
- name: AWS CodeBuild API List Builds
  x-api-slug: aws-codebuild-api
  description: Gets a list of build IDs, with each build ID representing a single
    build.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: ://///?Action=ListBuilds
  tags: Builds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/aws-codebuild/actionlistbuilds-get-openapi.md
- name: AWS CodeBuild API List Builds For Project
  x-api-slug: aws-codebuild-api
  description: Gets a list of build IDs for the specified build project, with each
    build ID representing a single build.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: ://///?Action=ListBuildsForProject
  tags: Project Builds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/aws-codebuild/actionlistbuildsforproject-get-openapi.md
- name: AWS CodeBuild API Start Build
  x-api-slug: aws-codebuild-api
  description: Starts running a build.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: ://///?Action=StartBuild
  tags: Builds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/aws-codebuild/actionstartbuild-get-openapi.md
- name: AWS CodeBuild API Stop Build
  x-api-slug: aws-codebuild-api
  description: Attempts to stop running a build.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: ://///?Action=StopBuild
  tags: Builds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/aws-codebuild/actionstopbuild-get-openapi.md
- name: AWS CodeBuild API
  x-api-slug: aws-codebuild-api
  description: AWS CodeBuild is a fully managed build service that compiles source
    code, runs tests, and produces software packages that are ready to deploy. With
    CodeBuild, you don&rsquo;t need to provision, manage, and scale your own build
    servers. CodeBuild scales continuously and processes multiple builds concurrently,
    so your builds are not left waiting in a queue. You can get started quickly by
    using prepackaged build environments, or you can create custom build environments
    that use your own build tools. With CodeBuild, you are charged by the minute for
    the compute resources you use.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/code-build-console-icon.png
  humanURL: https://aws.amazon.com/codebuild/
  baseURL: :///
  tags: Build
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/aws-codebuild/openapi.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/codebuild/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/codebuild/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/codebuild/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/codebuild/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/codebuild/pricing/
- type: x-website
  url: https://aws.amazon.com/codebuild/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---