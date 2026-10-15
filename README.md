# Pip pet assets

This repository stores the editable source and validated ChatGPT Pet sprite sheet for Pip.

- Current version: [`Pip/v1/`](Pip/v1/)
- Final atlas: [`Pip/v1/Pip-spritesheet.png`](Pip/v1/Pip-spritesheet.png)
- Editable base art and row strips: [`Pip/v1/source/`](Pip/v1/source/)
- Previews: [`Pip/v1/previews/`](Pip/v1/previews/)

## Publishing a future version

Keep published versions under `Pip/vN/` so earlier versions remain recoverable. Edit the source art, export a new 1536×2288 PNG atlas with transparent background and 192×208 cells, then run the ChatGPT Pets sprite-sheet validation before uploading it to Work. Update `Pip/README.md` to point to the new version in the same commit. Use a pull request for review when collaborating; the repository owner retains admin access and can push or merge updates.
