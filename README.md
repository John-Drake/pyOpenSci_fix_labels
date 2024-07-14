# pyOpenSci_fix_labels
Solution to pull request asking for method to fix labels

# How to Implement:
- Delete and rename labels as specified in jupyter notebook. 
- Copy .github/workflows/label-sync.yml workflow into workflow folder of project
- Run workflow

# Notes
- Uses script from `https://github.com/EndBug/label-sync`
- Workflow script based on `https://github.com/EndBug/label-sync/blob/main/.github/workflows/labels.yml` with permissions added and location of labels changed. 
