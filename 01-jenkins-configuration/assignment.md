---
slug: jenkins-configuration
id: va48u2tnabgu
type: challenge
title: Jenkins Configuration
notes:
- type: text
  contents: '![jenkins.png](https://play.instruqt.com/assets/tracks/gs4avgczrh2s/58ebe9d8084ae33ca01946707302d110/assets/jenkins.png)'
- type: image
  url: https://images.app.goo.gl/BCsRJFeBGvkcK7hw7
tabs:
- id: brourtrpwaca
  title: credentials
  type: terminal
  hostname: jenkins1
  workdir: /
  cmd: cat /var/lib/jenkins/secrets/initialAdminPassword
- id: vn0yeactvqcy
  title: Jenkins
  type: service
  hostname: jenkins1
  path: /
  port: 8080
- id: vxzv5ibpxkzh
  title: test
  type: terminal
  hostname: jenkins1
- id: vodxr5rri3bw
  title: Akash
  type: terminal
  hostname: jenkins1
  workdir: /
- title: sdssds
  type: terminal
  hostname: jenkins1
  workdir: /
difficulty: ""
timelimit: 0
lab_config:
  default_layout_sidebar_size: 0
---
## Credentials

Get Password from terminall

## Redirecting to Browser Tab

Clicking the Jenkins tab beside the Credentials tab will take you to the Jenkins login page.



