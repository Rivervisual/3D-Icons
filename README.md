# Pinterest Media Repo

This folder is ready to become a public GitHub repository for Pinterest media hosting.

## Steps

1. Create a new public GitHub repository.
2. Copy the contents of this folder into that repository.
3. Commit and push to your default branch, usually `main`.
4. Run `fill_pinterest_csv_from_github.py` from the main project folder to generate final Pinterest CSV files with raw GitHub image URLs.

## Notes

- Pinterest needs direct image URLs, not GitHub page URLs.
- The script will use `raw.githubusercontent.com`.
- Keep this repository public, or Pinterest will not be able to fetch the images.
