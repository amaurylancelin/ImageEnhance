# ImageEnhance
A Python programme using a Deep Learning model to enhance an image.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the requirements to run the python programme.

```bash
pip install -r requirements.txt
```

Download the model called EDSR_x3.pb [here](https://github.com/Saafke/EDSR_Tensorflow/tree/master/models) and put it in the folder called ```code```.

## Usage

When you're in the folder code, run the following code :

```bash
python3 main.py -r input_path [-e ouputname]
```
where :
```
    -r : define the input path, ex. test.jpg\n
    -e : define the output name, ex. testUpscaled.jpg (optional)
```
## License

[[1]](https://openaccess.thecvf.com/content_cvpr_2017_workshops/w12/papers/Lim_Enhanced_Deep_Residual_CVPR_2017_paper.pdf) Bee Lim, Sanghyun Son, Heewon Kim, Seungjun Nah, and Kyoung Mu Lee, "Enhanced Deep Residual Networks for Single Image Super-Resolution," 2nd NTIRE: New Trends in Image Restoration and Enhancement workshop and challenge on image super-resolution in conjunction with CVPR 2017. 
