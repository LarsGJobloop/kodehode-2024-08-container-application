# Relational Database (Postgresql)

## Run Locally

> [!IMPORTANT]
> This repository makes use of container technologies and
> single node container orchestration. Requisites are:
>
> - **MacOS:** [Orbstack](https://orbstack.dev/)
> - **Windows:** [Docker Desktop](https://docs.docker.com/desktop/install/windows-install/)
> - **Linux:**
>   - [Docker](https://docs.docker.com/desktop/install/linux/)
>   - [Podman](https://podman.io/docs/installation#installing-on-linux)

1. Clone the repository

   ```sh
   git
   ```

2. Start the application stack
   ```sh
   docker compose up
   ```

## Technologies

- [ASP .NET Core](https://learn.microsoft.com/en-us/aspnet/core/introduction-to-aspnet-core?view=aspnetcore-8.0)
- [Postgresql](https://www.postgresql.org/)
- [pgAdmin](https://www.pgadmin.org/)

- [Container Technology (Docker)](https://docs.docker.com/get-started/docker-overview/)
- [Container Orchestration (Docker Compose)](https://docs.docker.com/compose/)

> [!IMPORTANT]
> This repository makes use of [Nix](). For non-Nix users you can ignore
> the following files
>
> - `.envrc`
> - `flake.lock`
> - `flake.nix`

- [Nix](https://nixos.org/)
- [Direnv](https://direnv.net/)
