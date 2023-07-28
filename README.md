# ocr scan from png file to txt file on/of cli

> s. FROM_HERE.md first please
> [convert jpeg to png see here my other github project](https://github.com/MathiasStadler/convert_gif_to_png.git)

***Attention : For ocr scan must the site in the picture landscape upright***

## simple process in terminal/cli

> fix this

```bash
convert sample_page_one.png -rotate 90 sample_page_one_rotate.png
```

> - **convert_gif_to_png** s. hit above
> - **output** Name of output txt file
> - **300** dpi image resolution of scan

```bash
tesseract ~/convert_gif_to_png/sample_page_one_rotate.png output --dpi 300
```
