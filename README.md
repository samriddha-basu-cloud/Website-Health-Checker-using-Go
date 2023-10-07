<p align="center">
  <img src="https://img.shields.io/github/go-mod/go-version/samriddha-basu-cloud/Website-Health-Checker-using-Go" alt="Go Version">
  <img src="https://img.shields.io/github/license/samriddha-basu-cloud/Website-Health-Checker-using-Go" alt="License">
</p>

# Website Health Checker using Go 🚀

A lightweight command-line tool written in Go to quickly assess the status of websites. Easily check if a website is UP or DOWN with this CLI app.

---

## How it Works

This tool uses the Go `net` package to establish a TCP connection to the specified domain and port. If the connection is successful, it reports that the website is UP along with connection details. If there's an error during the connection attempt, it indicates that the website is DOWN and provides an error message.

## How to Run

1. Clone this repository:
   ```shell
   git clone https://github.com/samriddha-basu-cloud/Website-Health-Checker-using-Go.git
   ```

2. Navigate to the project directory:
   ```shell
   cd Website-Health-Checker-using-Go
   ```

3. Build the Go application:
   ```shell
   go build
   ```

4. Run the application with the `--domain` and optional `--port` flags:
   ```shell
   ./Website-Health-Checker-using-Go --domain example.com --port 80
   ```

## Examples

- Check if Google is UP on default port 80:
  ```shell
  ./Website-Health-Checker-using-Go --domain google.com
  ```

- Check if GitHub is UP on port 443:
  ```shell
  ./Website-Health-Checker-using-Go --domain github.com --port 443
  ```

- Check if a local server (e.g., localhost) is UP on port 8080:
  ```shell
  ./Website-Health-Checker-using-Go --domain localhost --port 8080
  ```

## Open for Contributions

We welcome contributions! If you have ideas for improvements or bug fixes, feel free to open an issue or create a pull request. Your contributions help make this tool better for everyone.

## License

This project is open-source and available under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as you see fit.
