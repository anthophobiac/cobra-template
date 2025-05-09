![Cobra CLI Icon](Cobra-Template.png)

# Cobra Template

A minimal template for building command-line tools in Go using:

- [Cobra](https://github.com/spf13/cobra) – for CLI structure
- [fatih/color](https://github.com/fatih/color) – for colourful terminal output

---

### Getting Started

#### 1. Clone the template

```bash
git clone https://github.com/yourusername/cobra-template.git
cd cobra-template
go mod tidy
```

#### 2. Run the CLI
```bash
go run main.go
go run main.go hello # An example command
```

### Project Structure
```
cobra-template/
├── cmd/              # Cobra commands where new ones can be added
├── pkg/logger/       # Logger that uses fatih/color
├── main.go           # Application entrypoint
```
