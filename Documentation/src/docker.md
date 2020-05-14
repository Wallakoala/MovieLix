# Docker Cheatsheet

- List images:

  ```sh
  $ docker image ls
  ```

- List containers:

  ```sh
  $ docker container ls
  ```

- Pull an image:

  ```sh
  $ docker pull my_repository/image:tag
  ```

- Run an image:

  ```sh
  $ docker run 8080:8080 my_image
  ```

- Stop a container:

  ```sh
  $ docker stop my_container
  ```
