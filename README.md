# LabelTemplateRepository
GitHub labels template for copying

## Prerequisites

 - Requires [Labeler](https://github.com/Zebiano/Labeler)

## Usage

Copy the `labeler_labels.json` file to the file path of `labeler -p`

Run the command:

```bash
labeler -t [ghp_GITHUB_PERSONAL_ACCESS_TOKEN] -o [USER/ORGANISATION] -r [REPOSITORY_NAME] -duf
```

`-d`: Delete all existing labels
`-u`: Upload labels from file

**Optional**
`-f`: Runs headlessly
