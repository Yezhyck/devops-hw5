# 🐳 devops-hw5

### 💻 Using console Docker commands: <br><br>

1. Building a Docker image **yezhyck/devops-hw5**:

    ```
    docker build . -t yezhyck/devops-hw5
    ```

2. Running a container **devops-hw5** with cpu(***500MB***) and memory(***1.5***) limits:

    ```
    docker run -d -p 80:80 --memory=500m --cpus=1.5 --name devops-hw5 yezhyck/devops-hw5
    ```

3. Log in to my Docker Hub account **yezhyck**:

    ```
    docker login
    ```

4. Pushing the image **yezhyck/devops-hw5** to my public repository **yezhyck/devops-hw5**:

    ```
    docker push yezhyck/devops-hw5
    ```

<br>

🔗 [My Docker Hub repository](https://hub.docker.com/repository/docker/yezhyck/devops-hw5)