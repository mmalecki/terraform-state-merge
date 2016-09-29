# terraform-state-merge
Merge any number of Terraform state files into one.

## Installation
```sh
npm -g install terraform-state-merge
```

## Usage
```
terraform-state-merge <tfstate-file> <tfstate-file> [<tfstate-file> [...]]
```

`terraform-state-merge` always assumes the latest state has the most accurate
information.
