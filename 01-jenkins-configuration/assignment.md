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
  path: ?cmd=cat+%2Fvar%2Flib%2Fjenkins%2Fsecrets%2FinitialAdminPassword&workdir=%2F
- id: vn0yeactvqcy
  title: Jenkins
  type: service
  hostname: jenkins1
  path: /
  port: 8080
  new_window: true
- id: vxzv5ibpxkzh
  title: test
  type: terminal
  hostname: jenkins1
- id: vodxr5rri3bw
  title: Akash
  type: terminal
  hostname: jenkins1
  path: ?workdir=%2F
- id: 8t5dgnoncxuy
  title: custom file
  type: code
  hostname: jenkins1
  path: /root/sl/test
difficulty: ""
timelimit: 0
lab_config:
  default_layout_sidebar_size: 0
enhanced_loading: null
---
## Credentials

Get Password from terminall

## Redirecting to Browser Tab

Clicking the Jenkins tab beside the Credentials tab will take you to the Jenkins login page.

[[ Instruqt-Var key="myip" hostname="jenkins1" ]]


![imagename](https://play.instruqt.com/assets/tracks/gs4avgczrh2s/067b864bf9437fbcae255afa7b5f62c1/assets/output.png)
