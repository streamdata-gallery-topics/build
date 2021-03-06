---
name: CircleCI
x-slug: circleci
description: CircleCI???s continuous integration and delivery platform makes it easy
  for teams of all sizes to rapidly build and release quality software at scale.  Build
  for Linux, macOS, and Android, in the cloud or behind your firewall.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
x-kinRank: "8"
x-alexaRank: "15983"
tags: Build
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/apis.md
specificationVersion: "0.14"
apis:
- name: CircleCI Delete Project Username Project Build Cache
  x-api-slug: circleci
  description: Delete project username project build cache.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
  humanURL: http://circleci.com
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/build-cache
  tags: Project, Username, Project, Build, Cache
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuildcache-delete-openapi.md
- name: CircleCI Parameters Project Username Project Build Cache
  x-api-slug: circleci
  description: Parameters project username project build cache.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
  humanURL: http://circleci.com
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/build-cache
  tags: Parameters, Project, Username, Project, Build, Cache
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuildcache-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuildcache-parameters-openapi.md
- name: CircleCI Get Project Username Project Build Num
  x-api-slug: circleci
  description: |-
    Full details for a single build. The response includes all of the fields from the build summary.
    This is also the payload for the [notification webhooks](/docs/configuration/#notify), in which case this object is the value to a key named 'payload'.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
  humanURL: http://circleci.com
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}
  tags: Project, Username, Project, Build, Num
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-num-get-openapi.md
- name: CircleCI Parameters Project Username Project Build Num
  x-api-slug: circleci
  description: Parameters project username project build num.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
  humanURL: http://circleci.com
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}
  tags: Parameters, Project, Username, Project, Build, Num
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-num-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-num-parameters-openapi.md
- name: CircleCI Get Project Username Project Build Num Artifacts
  x-api-slug: circleci
  description: Get project username project build num artifacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
  humanURL: http://circleci.com
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/artifacts
  tags: Project, Username, Project, Build, Num, Artifacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-numartifacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-numartifacts-get-openapi.md
- name: CircleCI Parameters Project Username Project Build Num Artifacts
  x-api-slug: circleci
  description: Parameters project username project build num artifacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
  humanURL: http://circleci.com
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/artifacts
  tags: Parameters, Project, Username, Project, Build, Num, Artifacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-numartifacts-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-numartifacts-parameters-openapi.md
- name: CircleCI Parameters Project Username Project Build Num Cancel
  x-api-slug: circleci
  description: Parameters project username project build num cancel.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
  humanURL: http://circleci.com
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/cancel
  tags: Parameters, Project, Username, Project, Build, Num, Cancel
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-numcancel-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-numcancel-parameters-openapi.md
- name: CircleCI Add Project Username Project Build Num Cancel
  x-api-slug: circleci
  description: Cancels the build, returns a summary of the build.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
  humanURL: http://circleci.com
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/cancel
  tags: Project, Username, Project, Build, Num, Cancel
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-numcancel-post-openapi.md
- name: CircleCI Parameters Project Username Project Build Num Retry
  x-api-slug: circleci
  description: Parameters project username project build num retry.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
  humanURL: http://circleci.com
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/retry
  tags: Parameters, Project, Username, Project, Build, Num, Retry
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-numretry-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-numretry-parameters-openapi.md
- name: CircleCI Add Project Username Project Build Num Retry
  x-api-slug: circleci
  description: Retries the build, returns a summary of the new build.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
  humanURL: http://circleci.com
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/retry
  tags: Project, Username, Project, Build, Num, Retry
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-numretry-post-openapi.md
- name: CircleCI Get Project Username Project Build Num Tests
  x-api-slug: circleci
  description: |-
    Provides test metadata for a build
    Note: [Learn how to set up your builds to collect test metadata](https://circleci.com/docs/test-metadata/)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
  humanURL: http://circleci.com
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/tests
  tags: Project, Username, Project, Build, Num, Tests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-numtests-get-openapi.md
- name: CircleCI Parameters Project Username Project Build Num Tests
  x-api-slug: circleci
  description: Parameters project username project build num tests.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
  humanURL: http://circleci.com
  baseURL: https://circleci.com//api/v1//project/{username}/{project}/{build_num}/tests
  tags: Parameters, Project, Username, Project, Build, Num, Tests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-numtests-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/projectusernameprojectbuild-numtests-parameters-openapi.md
- name: CircleCI Get Recent Builds
  x-api-slug: circleci
  description: Build summary for each of the last 30 recent builds, ordered by build_num.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
  humanURL: http://circleci.com
  baseURL: https://circleci.com//api/v1//recent-builds
  tags: Recent, Builds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/recentbuilds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/recentbuilds-get-openapi.md
- name: CircleCI
  x-api-slug: circleci
  description: CircleCI???s continuous integration and delivery platform makes it
    easy for teams of all sizes to rapidly build and release quality software at scale.  Build
    for Linux, macOS, and Android, in the cloud or behind your firewall.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28120-circleci.jpg
  humanURL: http://circleci.com
  baseURL: https://circleci.com//api/v1
  tags: Build
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/build/master/_listings/circleci/openapi.md
x-common:
- type: x-blog
  url: https://circleci.com/blog/
- type: x-blog-rss
  url: https://circleci.com/blog/feed.xml
- type: x-case-studies
  url: https://circleci.com/customers/
- type: x-change-log
  url: https://circleci.com/changelog/
- type: x-contact-form
  url: https://circleci.com/contact/
- type: x-crunchbase
  url: https://crunchbase.com/organization/circle-ci
- type: x-documentation
  url: https://circleci.com/docs/
- type: x-email
  url: press@circleci.com
- type: x-email
  url: billing@circleci.com
- type: x-email
  url: privacy@circleci.com
- type: x-email
  url: sayhi@circleci.com
- type: x-github
  url: https://github.com/circleci
- type: x-linkedin
  url: https://www.linkedin.com/company/circleci
- type: x-pricing
  url: https://circleci.com/pricing/
- type: x-privacy-policy
  url: https://circleci.com/privacy/
- type: x-selfservice-registration
  url: https://circleci.com/signup/
- type: x-status
  url: https://status.circleci.com/
- type: x-support
  url: https://support.circleci.com/hc/en-us
- type: x-terms-of-service
  url: https://circleci.com/terms-of-service/
- type: x-twitter
  url: https://twitter.com/circleci
- type: x-website
  url: http://circleci.com
- type: x-website
  url: https://circleci.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---