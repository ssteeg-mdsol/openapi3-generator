# Deprecation notice

This repository is no longer maintained, and has been replaced by https://github.com/mdsol/openapi3-generator.


# Generate PDFs from a OpenAPI v3 file

## Requirements

* NodeJS v7.6+
  * On Mac, use [Brew](https://brew.sh/) - `brew install node`
  * Otherwise, install from the [NodeJS downloads page](https://nodejs.org/en/)


## Usage

Clone the repository:

```sh
git clone https://github.com/ssteeg-mdsol/openapi3-generator.git
```

And execute the script giving the path to the OpenAPI file you want to render:

```sh
cd openapi3-generator
npm install
./run.sh <path_to_your_openapi>.yaml
```

A release number can also be passed as a parameter, which will be displayed on the title page.
```sh
./run.sh <path_to_your_openapi>.yaml <release_number>
```


## Update the script

From time to time, small improvements to the script may be added. To get the latest changes, run the following command in the `openapi3-generator` directory:
```sh
git pull origin master
```
