# FLASH Project Page

Source for the project website of **FLASH: Efficient Visuomotor Policy via Sparse Sampling**.

Live site: <https://B1ue-Jay.github.io/FLASH/>

## Structure

```
index.html              entry point
style.css               all styling (CSS variables at the top of the file)
static/images/          figures used on the page (PNG, converted from paper PDFs)
```

## Customising the look

Open `style.css` and edit the variables inside the `:root` block at the top
to change colors, fonts, or layout width without touching the rest of the
file. The brand color is defined as `--primary` (currently `#4E8BC7`,
matching the paper's figure palette).

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
