# UITClass

UITClass is a Python project built with FastAPI and managed with Poetry. It provides a simple API for locating places based on their names.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/aasifshahzad/uitclass.git
   cd uitclass
   ```

2. Install dependencies using Poetry:

   ```bash
   poetry install
   ```

## Usage

Run the application using Uvicorn:

```bash
poetry run uvicorn uitclass.main:app --reload
```

The API will be available at `http://localhost:8000`.

## Endpoints

- **GET /**: Returns a greeting message.
- **GET /location/{name}**: Retrieves the location details for the specified name.

## Dependencies

- Python 3.12
- FastAPI 0.110.0
- Uvicorn 0.27.1 (with standard extras)

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.