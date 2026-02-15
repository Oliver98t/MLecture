# MLecture Project

This repository serves as the main entry point for the MLecture project, which is an azure functions (backend) and azure static web apps (frontend) fullstack web app for simplifying note taking. All you need to do is supply a YouTube link to the video and your notes will be created!

Heres a demo running live from Azure:

https://github.com/user-attachments/assets/62451153-ff0f-406b-8dd8-db4c481afafb

## Submodules

- **Backend**: [MLecture_backend](https://github.com/Oliver98t/MLecture_backend)
- **Frontend**: [MLecture_frontend](https://github.com/Oliver98t/MLecture_frontend)

Both the backend and frontend are included as submodules in this repository. Make sure to initialize and update submodules after cloning:

```bash
git submodule update --init --recursive
```

## Project Structure

- `MLecture_backend/` — Contains the backend code (API, database, etc.)
- `MLecture_frontend/` — Contains the frontend code (UI, client app, etc.)

## Cloning the Repository

To clone this repository along with its submodules, use:

```bash
git clone --recurse-submodules https://github.com/Oliver98t/MLecture.git
```

If you already cloned the repository without submodules, run:

```bash
git submodule update --init --recursive
```

## Getting Started

1. Follow the setup instructions in each submodule's README:
   - [MLecture_backend README](https://github.com/Oliver98t/MLecture_backend#readme)
   - [MLecture_frontend README](https://github.com/Oliver98t/MLecture_frontend#readme)

2. Start the backend and frontend as described in their respective documentation.

## Contributing

Please refer to the individual repositories for contribution guidelines.

## License

See the LICENSE files in the respective submodules for license information.
