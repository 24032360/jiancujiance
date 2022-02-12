```bash
tree jiancujiance/
jiancujiance/
├── __init__.py
├── negative_data
│   ├── __init__.py
│   └── original
│       ├── __init__.py
│       └── README.md
├── positive_data
│   ├── __init__.py
│   └── original
│       ├── __init__.py
│       └── README.md
├── README.md
└── xml
    └── __init__.py
```
positive_data 目录:  
    original 放最原始的图片, 这些图片我们需要剪切成20*20的尺寸.  
    剪好的图片就放在这层文件夹(positive_data)里面.  
negative_data 目录:  
    这里是用来训练的照片,训练的时候opencv从在这个文件夹的照片中找出\  
positive_data里剪切好的20*20的照片,然后进行学习.    
