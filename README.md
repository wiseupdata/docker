<a href="https://github.com/wiseupdata/wiseupdata">
  <img align="left" alt="Wise Up Data's Instagram" width="22px" src="https://raw.githubusercontent.com/wiseupdata/wiseupdata/main/assets/instagram.png" />   
</a> 
<a href="https://github.com/wiseupdata/wiseupdata">
  <img align="left" alt="wise Up Data's Discord" width="22px" src="https://raw.githubusercontent.com/wiseupdata/wiseupdata/main/assets/discord.png" />
</a>
<a href="https://github.com/wiseupdata/wiseupdata">
  <img align="left" alt="wise Up Data | Twitter" width="22px" src="https://raw.githubusercontent.com/wiseupdata/wiseupdata/main/assets/twitter.png" />
</a>
<a href="https://github.com/wiseupdata/wiseupdata">
  <img align="left" alt="wise Up Data's LinkedIN" width="22px" src="https://raw.githubusercontent.com/wiseupdata/wiseupdata/main/assets/linkedin.png" />
</a>

![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fwiseupdata%2Fdocker&countColor=%2337d67a&style=flat)
![license](https://img.shields.io/github/license/wiseupdata/docker)

---
<a name="readme-top"></a>


<a href="https://github.com/wiseupdata/wiseupdata">
<img align="left" alt="Docker image" src="https://raw.githubusercontent.com/wiseupdata/docker/main/assets/imgs/docker.png" width="100" />
</a>

<h1>
docker Utils
</h1>
Useful commands to handle docker 🚀. <br>
Shell commands tested 🎯: <br>

- Ubuntu 
- Wsl2 with Windows 11 
- compatible with all Ubuntu and Debian


<br>

## ☄️ Basic commands.

<details>
<summary>
  Run a container image in the terminal 🌱 [click]
</summary>

```bash
docker run -it --name python --rm wiseupdata/python:3.10 bash
```
> * it - Interactive Terminal.
> * rm - Delete the container after the use.
> * name - Name for the container
> * bash - Command to be executed 
</details>


<details>
<summary>
  Run a container image in the terminal, force 🪚 [click]
</summary>

```bash
docker run -it --entrypoint /bin/bash airflow
```
</details>


<details>
<summary>
  List all containers 🖍️ [click]
</summary>

```bash
docker ps -a
```

> * ps - list active containers.
> * a - list also not active containers.
</details>


<details>
<summary>
  Delete all containers ☠️ [click]
</summary>

```bash
docker rm $(docker ps -a -q) -f
```
</details>

<details>
<summary>
  List all Images 📀 [click]
</summary>

```bash
docker image ls -a
```
</details>

<details>
<summary>
  Delete all Images 💥 [click]
</summary>

```bash
docker image rm  $(docker image ls -a ) -f
```
</details>

<details>
<summary>
  build a image 💿 [click]
</summary>

```bash
docker build -t airflow ./versions/2.6.1 --no-cache
```
</details>

<br>
<br>

# References 🌍 🗄️

1. [Wise Up Data](https://github.com/wiseupdata)
1. [Emojis](https://github.com/wiseupdata/emojis)


<br><br>
---

#### Maintainer 🤗 👨‍💻

Sivio Liborio

📧 silvio.liborio@wiseupdata.com

<a href="https://www.linkedin.com/in/silvio-de-melo-liborio">silvio-de-melo-liborio <img align="left" alt="LinkedIN" width="18px" src="https://raw.githubusercontent.com/wiseupdata/wsl-latest/main/assets/linkedin.svg" />
</a>
