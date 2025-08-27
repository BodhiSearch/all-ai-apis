# OpenAI Rust Types

[![CI](https://github.com/your-org/openai-rust-types/workflows/CI/badge.svg)](https://github.com/your-org/openai-rust-types/actions)
[![Documentation](https://github.com/your-org/openai-rust-types/workflows/Documentation/badge.svg)](https://github.com/your-org/openai-rust-types/actions)
[![codecov](https://codecov.io/gh/your-org/openai-rust-types/branch/main/graph/badge.svg)](https://codecov.io/gh/your-org/openai-rust-types)

Strongly-typed Rust bindings for the OpenAI API, generated from the official OpenAPI specification.

## Features

- 🔧 **Generated from OpenAPI spec**: Always up-to-date with the latest API changes
- 🦀 **Pure Rust**: No runtime dependencies on other languages
- 🚀 **Fast builds**: Optimized build process with comprehensive caching
- 📚 **Well documented**: Complete API documentation with examples
- 🧪 **Thoroughly tested**: Comprehensive test suite with high coverage

## Development

This project uses a Cargo workspace structure:

- `crates/openai/` - Main OpenAI types library
- `crates/xtask/` - Development utilities and build tools

### Building

```bash
# Build the entire workspace
cargo build --workspace

# Run tests
cargo test --workspace

# Check code formatting and linting
cargo fmt --all -- --check
cargo clippy --workspace --all-targets -- -D warnings
```

### CI/CD

The project includes comprehensive GitHub Actions workflows:

- **CI**: Runs tests, linting, and security audits on every push/PR
- **Documentation**: Builds and deploys docs to GitHub Pages
- **Release**: Automated releases and crate publishing
- **Benchmarks**: Performance tracking over time
- **Cleanup**: Automatic cleanup of old workflow runs

All workflows include intelligent caching to minimize build times.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.