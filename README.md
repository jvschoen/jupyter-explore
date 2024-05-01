# Getting Started
> Prerequisites (Free):
> * **git**: https://github.com/git-guides/install-git
> * **Docker Desktop**: https://www.docker.com/products/docker-desktop/
> * **GitHub Account**: https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github



* **Linux/Mac (Or GitBash)**
> Can run above in GitBash if in Windows.
> Install make via installing [chocolatey](https://chocolatey.org/install),
> and installing make via `choco install make`

    Run following commands in terminal/powershell:

    ```sh
    make build
    make run
    ```

* **Windows**

    ```sh
    docker compose build
    docker compose up
    ```

You will be instructed in the terminal to go to [http://127.0.0.1:8888/lab]

This will open up a jupyter lab instance in your browser.

All work yo udo in the `notebooks` directory in the browser will show in the host (local) directory `notebooks`

