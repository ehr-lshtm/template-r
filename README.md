# EHR group template for R Projects

## Purpose

This is a template for projects using R and RStudio. [Click here](https://github.com/ehr-lshtm/template-r/generate) to use this template. This will allow you to initiate a new project either in the EHR organisation or on your private Github. We recommend that you keep the repository setting as Private for work in progress, and ask someone from the group to review the repo before making it public. When you have initiated a new project, replace the text in this README with a description of your project. 

## Untracked files

Repositories should only contain non-disclosive files, that is, code without file paths and summary statistics. This template is set up so only files that are safe to upload to Github, such as code, are uploaded by default. This means all files ending in `.csv`, all Stata output, and all files in the `data/` and `paths/` folders (except README) are untracked, i.e. they will not be uploaded to GitHub. Edit the `.gitignore` file to ignore or allow (with `!`) specific files or file types. 

## New to git? 

If you are using git or Github for the first time [placeholder - do we link some training resources?]. If you have any questions, post them the "github" channel on the EHR slack. 

## File tree
We recommend that you use this file structure as the `.gitignore` is set up to ignore specific folders. You can add subfolders as needed, for example for different types of outputs (logs, images, tables), or remove folders that are not used. 

```
template-r/
├── codelists/
│   ├── README.md
│   ├── codelist_1.csv
│   └── codelist_1_metadata.txt
├── data/
│   ├── README.md
│   ├── cleaned_data_1.csv (untracked)
│   └── cleaned_data_2.csv (untracked)
├── docs/
│   ├── README.md
│   ├── document1.docx
│   ├── document1.html
│   └── document1.Rmd
├── paths/
│   ├── README.md
│   └── paths.R (untracked)
├── R/
│   ├── README.md
│   └── functions.R
├── results/
│   ├── README.md
│   └── result_1.csv
├── r-template.Rproj
└── README.md
```
