# Healthcare AI Examples - Data Repository

Sample datasets and embeddings for [microsoft/healthcareai-examples](https://github.com/microsoft/healthcareai-examples).

## Prerequisites

This repository uses [Git LFS (Large File Storage)](https://git-lfs.github.com/) to manage large medical imaging files and datasets.

### Installing Git LFS

**Windows:**

Download installer from https://git-lfs.github.com/ or using Chocolatey:

```powershell
choco install git-lfs
```

**macOS:**

Download installer from https://git-lfs.github.com/ or using Homebrew:

```bash
# Using Homebrew
brew install git-lfs
```

**Linux (Ubuntu/Debian):**
```bash
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
sudo apt-get install git-lfs
```

**Linux (Fedora/RHEL):**
```bash
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.rpm.sh | sudo bash
sudo yum install git-lfs
```

After installation, initialize Git LFS:
```bash
git lfs install
```

## Usage

Clone this repository alongside the main examples repository:

```bash
git clone https://github.com/microsoft/healthcareai-examples-data.git
```

The example notebooks in [microsoft/healthcareai-examples](https://github.com/microsoft/healthcareai-examples) reference these datasets.

### Already Cloned Without Git LFS?

If you cloned the repository before installing Git LFS, you'll need to fetch the actual files:

```bash
cd healthcareai-examples-data
git lfs install
git lfs pull
```

This will download all the large files that were previously stored as LFS pointers.

## License

See [LICENSE](LICENSE) file for details.
