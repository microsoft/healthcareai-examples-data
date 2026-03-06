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

## Data Attribution

- **TCGA-GBM**  
  Scarpace, L., Mikkelsen, T., Cha, S., Rao, S., Tekchandani, S., Gutman, D., Saltz, J. H., Erickson, B. J., Pedano, N., Flanders, A. E., Barnholtz-Sloan, J., Ostrom, Q., Barboriak, D., & Pierce, L. J. (2016). *The Cancer Genome Atlas Glioblastoma Multiforme Collection (TCGA-GBM)* (Version 5) [Data set]. The Cancer Imaging Archive. <https://doi.org/10.7937/K9/TCIA.2016.RNYFUYE9>

- **TCGA-LGG**  
  Pedano, N., Flanders, A. E., Scarpace, L., Mikkelsen, T., Eschbacher, J. M., Hermes, B., Sisneros, V., Barnholtz-Sloan, J., & Ostrom, Q. (2016). *The Cancer Genome Atlas Low Grade Glioma Collection (TCGA-LGG)* (Version 3) [Data set]. The Cancer Imaging Archive. <https://doi.org/10.7937/K9/TCIA.2016.L4LTD3TK>

## License

See [LICENSE](LICENSE) file for details.
