# OCR-Yolov5-SwinIR-SVTR
OCR(Korean)


## Run demo

- Requirement
```
!python3 -m pip install paddlepaddle-gpu
!pip install "paddleocr>=2.0.1"
!pip install --upgrade PyYAML --ignore-installed
!pip install -r requirements.txt
```

- Run demo.py
```
!python3 demo.py --image_dir='/content/test_img/' --rec_algorithm='SVTR' --rec_image_shape='3,64,256' --rec_char_dict_path='./korean_dict.txt'
```
- Result : The result will be saved in './results'



Reference
---------------------------------------------------------------------
- https://github.com/jingyunliang/swinir
- https://github.com/PaddlePaddle/PaddleOCR
- https://github.com/aqntks/Easy-Yolo-OCR
