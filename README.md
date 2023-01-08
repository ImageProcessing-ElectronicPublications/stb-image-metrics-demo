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

* ![metric](images/lena.quant444.mse.png) MSE: 0.013604
* ![metric](images/lena.quant444.psnr.png) PSNR: 18.663233
* ![metric](images/lena.quant444.nhw-n.png) NHW-N: 0.072673
* ![metric](images/lena.quant444.nhw-c.png) NHW-C: 0.145290
* ![metric](images/lena.quant444.nhw-r.png) NHW-R: 0.116387

---

YCbCr mode:

* ![metric](images/lena.quant444.mse.y.png) MSE: 0.006030
* ![metric](images/lena.quant444.psnr.y.png) PSNR: 22.196735
* ![metric](images/lena.quant444.nhw-n.y.png) NHW-N: 0.075381
* ![metric](images/lena.quant444.nhw-c.y.png) NHW-C: 0.091878
* ![metric](images/lena.quant444.nhw-r.y.png) NHW-R: 0.078292

---

---
