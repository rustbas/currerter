# Currenter

Simple currency converter.

# Initialization

## DockerHub

You can pull it from DockerHub:
```console
foo@bar:~$ docker run --rm -d -p 8000:80 wtukatyr/currenter:latest
```

## Manual building

1. Clone the repository:
    ```console
    foo@bar:~$ git clone https://github.com/rustbas/currenter.git
    foo@bar:~$ cd currenter
    ```
2. Build the docker image:
    ```console
    foo@bar:~/currenter$ docker build -t currenter .
    ```
3. Run the docker container:
    ```console
    foo@bar:~/currenter$ docker run --rm -d -p 8000:80 currenter:latest
    ```

# Usage

1. Open `localhost:8000` in your browser
2. Choose currencies
3. Insert amount 
4. Click `Submit`

# TODO

1. [ ] Change `sqlite` to `postgreql`
2. [ ] Add button to update the database
3. [ ] Add frontend
4. [ ] Add more currencies
5. [ ] Refactor database workflow
