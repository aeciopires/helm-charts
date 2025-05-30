# CHANGELOG for `victoria-metrics-common` helm-chart

## Next release

- TODO

## 0.0.42

**Release date:** 19 Mar 2025

![Helm: v3](https://img.shields.io/badge/Helm-v3.14%2B-informational?color=informational&logo=helm&link=https%3A%2F%2Fgithub.com%2Fhelm%2Fhelm%2Freleases%2Ftag%2Fv3.14.0)

- Support custom case for list empty argument.

## 0.0.41

**Release date:** 02 Mar 2025

![Helm: v3](https://img.shields.io/badge/Helm-v3.14%2B-informational?color=informational&logo=helm&link=https%3A%2F%2Fgithub.com%2Fhelm%2Fhelm%2Freleases%2Ftag%2Fv3.14.0)

- add noEnterprise flag to disable `-enterprise` image suffix

## 0.0.40

**Release date:** 02 Mar 2025

![Helm: v3](https://img.shields.io/badge/Helm-v3.14%2B-informational?color=informational&logo=helm&link=https%3A%2F%2Fgithub.com%2Fhelm%2Fhelm%2Freleases%2Ftag%2Fv3.14.0)

- Support managed components license path for proper enterprise images rendering

## 0.0.39

**Release date:** 05 Feb 2025

![Helm: v3](https://img.shields.io/badge/Helm-v3.14%2B-informational?color=informational&logo=helm&link=https%3A%2F%2Fgithub.com%2Fhelm%2Fhelm%2Freleases%2Ftag%2Fv3.14.0)

- Fix overwrite per service empty registry

## 0.0.38

**Release date:** 04 Feb 2025

![Helm: v3](https://img.shields.io/badge/Helm-v3.14%2B-informational?color=informational&logo=helm&link=https%3A%2F%2Fgithub.com%2Fhelm%2Fhelm%2Freleases%2Ftag%2Fv3.14.0)

- Fixed minor securityContext template typo

## 0.0.37

**Release date:** 06 Jan 2025

![Helm: v3](https://img.shields.io/badge/Helm-v3.14%2B-informational?color=informational&logo=helm&link=https%3A%2F%2Fgithub.com%2Fhelm%2Fhelm%2Freleases%2Ftag%2Fv3.14.0)

- quote collection values in arguments

## 0.0.36

**Release date:** 24 Dec 2024

![Helm: v3](https://img.shields.io/badge/Helm-v3.14%2B-informational?color=informational&logo=helm&link=https%3A%2F%2Fgithub.com%2Fhelm%2Fhelm%2Freleases%2Ftag%2Fv3.14.0)

- Exclude markdown files from package
- Unset empty registry in `vm.image` template to fix global registry propagation

## 0.0.35

**Release date:** 2024-12-17

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- fixed tls in common templates. See [this issue](https://github.com/VictoriaMetrics/helm-charts/issues/1874)

## 0.0.34

**Release date:** 2024-12-11

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- moved helm chart requirement to a common template

## 0.0.33

**Release date:** 2024-11-28

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- use container port instead of service one in `vm.host` template, while appIdx is defined
- expect tls extraArg parameter as boolean value

## 0.0.32

**Release date:** 2024-11-25

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- removed suffix, that starts with `@sha` from app version label. see [this issue](https://github.com/VictoriaMetrics/helm-charts/issues/1801).

## 0.0.31

**Release date:** 2024-11-21

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- fixed minor typo in vm.labels

## 0.0.30

**Release date:** 2024-11-21

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- support template rendering in `vm.app.name` template

## 0.0.29

**Release date:** 2024-11-19

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Allow lookup in context root for `vm.url`, `vm.host` templates

## 0.0.28

**Release date:** 2024-11-14

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Allow lookup in context root for `vm.url`, `vm.host` templates

## 0.0.27

**Release date:** 2024-11-14

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- fail fullname templates if data for appKey is not found
- find by appKey in Values and context root

## 0.0.26

**Release date:** 2024-11-14

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- do not append key only if it's passed to a template

## 0.0.25

**Release date:** 2024-11-12

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- fixed adding suffix for `vm.plain.fullname`

## 0.0.24

**Release date:** 2024-11-12

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Disabled impact of `<component>.name` on resource name to avoid confusion
- Fixed `vm.app.name` template for appCtx that contains slice

## 0.0.23

**Release date:** 2024-11-08

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- fix: context cleanup

## 0.0.22

**Release date:** 2024-11-08

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Removed unused cases from `vm.fullname`

## 0.0.21

**Release date:** 2024-11-07

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Added ability to disable name truncation
- Truncate `/` from `vm.url` output

## 0.0.20

**Release date:** 2024-11-06

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Fixed boolean args rendering

## 0.0.19

**Release date:** 2024-11-04

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- TODO

## 0.0.18

**Release date:** 2024-10-29

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- vm.managed.fullname template modify prefixes

## 0.0.17

**Release date:** 2024-10-25

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Added vm.podLabels template
- Do no append default `<component>` prefix/suffix when `<component>.fullnameOverride` set

## 0.0.16

**Release date:** 2024-10-15

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Allow extract name prefix from app level fullnameOverride property

## 0.0.15

**Release date:** 2024-10-11

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Display compatibility error message

## 0.0.14

**Release date:** 2024-10-04

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Fixed openshift compatibility templates

## 0.0.13

**Release date:** 2024-09-16

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Do not use image variant if custom image tag is set in `vm.image` template
- Support multiple license flag styles, which are different for vmanomaly and other services

## 0.0.12

**Release date:** 2024-09-16

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Add enterprise to existing variant if enterprise enabled
- Added `vm.enterprise.disabled` template to check if enterprise license is disabled
- Use `service.servicePort` as a port source if flag is not set in `vm.url`

## 0.0.11

**Release date:** 2024-09-11

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Added ability to pass extra prefix for `vm.managed.fullname`

## 0.0.10

**Release date:** 2024-09-10

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Fixed protocol extraction with TLS enabled
- Typo fixes
- use appkey as `app` label by default
- support multiple service naming styles for `vm.service`

## 0.0.9

**Release date:** 2024-09-02

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Allow `appKey` argument to be a list to support deeply nested objects
- Added `vm.namespace`, which returns `namespaceOverride` or `global.namespaceOverride` or `Release.Namespace` as a default
- Added `vm.managed.fullname`, which returns default fullname prefixed by `appKey`
- Added `vm.plain.fullname`, which returns default fullname suffixed by `appKey`

## 0.0.8

**Release date:** 2024-08-29

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Added `vm.service` for unified service name generation
- Added `vm.url` to construct service base url
- Added `vm.name` for chart name
- Added `vm.fullname` which is actively used in resource name construction
- Added `vm.chart` to construct chart name label value
- Added `vm.labels` for common labels
- Added `vm.sa` for service account name
- Added `vm.release` for release name
- Added `vm.selectorLabels` for common selector labels

## 0.0.7

**Release date:** 2024-08-27

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Support short and long args flags in `vm.args`
- Updated `vm.enterprise.only` error message

## 0.0.6

**Release date:** 2024-08-27

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Changed structure of `vm.args` template output
- Removed `eula` support

## 0.0.5

**Release date:** 2024-08-26

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Fixed `vm.enterprise.only` template to check if at least one of both global.licence.eula and .Values.license.eula are defined
- Convert `vm.args` bool `true` values to flags without values

## 0.0.4

**Release date:** 2024-08-26

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Updated `vm.probe.*` templates to remove Helm 3.14 restriction.
- Added `vm.args` template for cmd args generation

## 0.0.3

**Release date:** 2024-08-25

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Moved license templates from other charts `vm.license.volume`, `vm.license.mount`, `vm.license.flag`
- Moved `vm.compatibility.renderSecurityContext` template
- Fixed a case, when null is passed to a `.Values.global`. See [this issue](https://github.com/VictoriaMetrics/helm-charts/issues/1296)

## 0.0.2

**Release date:** 2024-08-23

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Added `vm.port.from.flag` template to extract port from cmd flag listen address.

## 0.0.1

**Release date:** 2024-08-15

![Helm: v3](https://img.shields.io/static/v1?label=Helm&message=v3&color=informational&logo=helm)

- Added `vm.enterprise.only` template to fail rendering if required license arguments weren't set.
- Added `vm.image` template that introduces common chart logic of how to build image name from application variables.
- Added `vm.ingress.port` template to render properly ingress port configuration depending on args type.
- Added `vm.probe.*` templates to render probes params consistently across all templates.
