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

* ![metric](images/lena.quant444.mse.png) MSE: 0.013604, UM: -1.218735
* ![metric](images/lena.quant444.psnr.png) PSNR: 18.663233, UM: -1.317894
* ![metric](images/lena.quant444.smallfry.png) SMALLFRY: 83.753342, UM -0.653625
* ![metric](images/lena.quant444.shbad.png) SHARPENBAD: -0.213132, UM: -0.575435
* ![metric](images/lena.quant444.cor.png) Corelation: 0.953666, UM: -0.644979
* ![metric](images/lena.quant444.nhw-n.png) NHW-N: 0.072673, UM: 0.144120
* ![metric](images/lena.quant444.nhw-c.png) NHW-C: 0.145290, UM: -0.042954
* ![metric](images/lena.quant444.nhw-r.png) NHW-R: 0.116387, UM: -0.109872

---

YCbCr mode:

* ![metric](images/lena.quant444.mse.y.png) MSE: 0.006030, UM: 0.422970
* ![metric](images/lena.quant444.psnr.y.png) PSNR: 22.196735, UM: -0.887525
* ![metric](images/lena.quant444.smallfry.y.png) SMALLFRY: 85.867256, UM: -0.495716
* ![metric](images/lena.quant444.shbad.y.png) SHARPENBAD: -0.242864, UM: -0.619439
* ![metric](images/lena.quant444.cor.y.png) Corelation: 0.951516, UM: -0.664542
* ![metric](images/lena.quant444.nhw-n.y.png) NHW-N: 0.075381, UM: 0.133249
* ![metric](images/lena.quant444.nhw-c.y.png) NHW-C: 0.091878, UM: 0.067151
* ![metric](images/lena.quant444.nhw-r.y.png) NHW-R: 0.078292, UM: -0.004621


---

---
