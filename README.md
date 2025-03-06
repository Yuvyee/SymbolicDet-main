# From Objects to Events: Unlocking Complex Visual Understanding in Object Detectors via LLM-guided Symbolic Reasoning

![License](https://img.shields.io/badge/license-MIT-blue)


## 🚀 Usage

### Running the SymbolicDet Framework

You can run the framework either using the Python script directly or using the provided bash script:

#### Using Bash Script (Recommended)

```bash
# Give execution permission
chmod +x run_sr.sh

# Set API key (required for LLM functionality)
# Option 1: Using environment variable
export SR_API_KEY="your_api_key"

# Option 2: Using command line argument
./run_sr.sh -k "your_api_key"

# Run with default settings (LLM enabled)
./run_sr.sh

# Run without LLM assistance
./run_sr.sh --no-llm

# Run with custom config file
./run_sr.sh -c path/to/config.yaml

# Run with multiple options
./run_sr.sh --no-llm -c path/to/config.yaml
./run_sr.sh -k "your_api_key" -c path/to/config.yaml
```

#### Script Options:
- `-h, --help`: Show help information
- `--no-llm`: Disable LLM functionality
- `-c, --config <path>`: Specify configuration file path
- `-k, --api-key <key>`: Set API key (can also be set via SR_API_KEY environment variable)

#### Requirements:

- Python 3.7+
- Required packages: see `requirements.txt`
- API key for LLM service (when using LLM functionality)

## ✏️ Citation

If you find our paper and code useful in your research, please consider giving a star ⭐ and citation 📝:

```
[wait for update]
```
