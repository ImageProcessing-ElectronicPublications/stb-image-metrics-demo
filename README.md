# [stb-image-metrics](https://github.com/ImageProcessing-ElectronicPublications/stb-image-metrics) demo

This utility compares two graphics files based on metrics.

Demo of [stb-image-metrics](https://github.com/ImageProcessing-ElectronicPublications/stb-image-metrics).

## Metrics

Origin and Compare:

![origin](images/lena.png) ![compare](images/lena.quant444.png)

Metrcics:

```shell
stbimmetrics lena.png lena.quant444.png lena.quant444.psnr.png 
Load: lena.png
image: 256x256:3
Load: lena.quant444.png
image: 256x256:3
type: psnr
metric: 18.663233
Save png: lena.quant444.psnr.png

```

---

RGB mode:

| Name | Image metric | Value | UM |
| --- | --- | --- | --- |
| MSE | ![metric](images/lena.quant444.mse.png) | 0.013604 | 0.208771 |
| PSNR | ![metric](images/lena.quant444.psnr.png) | 18.663233 | 0.470890 |
| SDSNR | ![metric](images/lena.quant444.sdsnr.png) | 13.888971 | 0.454668 |
| Corelation | ![metric](images/lena.quant444.cor.png) | 0.953666 | 0.285007 |
| SSIM | ![metric](images/lena.quant444.ssim.png) | 0.618509 | 0.050606 |
| VIFP1 | ![metric](images/lena.quant444.vifp1.png) | 0.170903 | 0.053111 |
| SMALLFRY | ![metric](images/lena.quant444.smallfry.png) | 83.753342 | 0.341786 |
| SHARPENBAD | ![metric](images/lena.quant444.shbad.png) | 0.389942 | 0.138531 |
| NHW-C | ![metric](images/lena.quant444.nhw-c.png) | 0.145290 | 0.422748 |
| NHW-N | ![metric](images/lena.quant444.nhw-n.png) | 0.072673 | 0.550836 |
| NHW-R | ![metric](images/lena.quant444.nhw-r.png) | 0.116387 | 0.381794 |

---

YCbCr mode:

| Name | Image metric | Value | UM |
| --- | --- | --- | --- |
| MSE | ![metric](images/lena.quant444.mse.y.png) | 0.006030 | 0.255863 |
| PSNR | ![metric](images/lena.quant444.psnr.y.png) | 22.196735 | 0.513536 |
| SDSNR | ![metric](images/lena.quant444.sdsnr.y.png) | 21.873943 | 0.507061 |
| Corelation | ![metric](images/lena.quant444.cor.y.png) | 0.951516 | 0.278486 |
| SSIM | ![metric](images/lena.quant444.ssim.y.png) | 0.608033 | 0.046795 |
| VIFP1 | ![metric](images/lena.quant444.vifp1.y.png) | 0.227644 | 0.094781 |
| SMALLFRY | ![metric](images/lena.quant444.smallfry.y.png) | 85.867256 | 0.385938 |
| SHARPENBAD | ![metric](images/lena.quant444.shbad.y.png) | 0.371371 | 0.125152 |
| NHW-C | ![metric](images/lena.quant444.nhw-c.y.png) | 0.091878 | 0.474065 |
| NHW-N | ![metric](images/lena.quant444.nhw-n.y.png) | 0.075381 | 0.545821 |
| NHW-R | ![metric](images/lena.quant444.nhw-r.y.png) | 0.078292 | 0.421576 |

---

---
