# ES2022 - 實作8: 零基礎Python快速入門與實作

## Lab 8-1 零基礎Python快速入門與實作, 1/2

![image](https://user-images.githubusercontent.com/89304181/200157003-7c00aee1-78e6-4f36-b99a-a0f8a336562d.png)

## Lab 8-2 零基礎Python快速入門與實作, 2/2

![image](https://user-images.githubusercontent.com/89304181/200156984-755a4e57-869c-4c7a-a4bc-e125f32a498f.png)

## Lab 8-3 建立新的Colab Notebook (e.g., Filename: ShowPhoto.ipynb), 用Python來Show一下圖像

### Show Tiger

![image](https://user-images.githubusercontent.com/89304181/201507640-fc086b08-83f1-44bb-866e-428dfcdee656.png)

### Show Dog

![image](https://user-images.githubusercontent.com/89304181/201507653-abc17990-9595-49ed-910c-4f867a392b73.png)

## Show VNU Logo

![image](https://user-images.githubusercontent.com/89304181/201507683-ab13d659-e2ba-4bde-a125-73cdd5993a2c.png)

## Reference Code

```python
print('*** Done by %s at ' % ts3,today, type(today))

# 實作: 請由以上的選項自選一個來試試

# 你的程式

image_name = 'vnu' 
images_for_test_map = {
    "tiger": "https://upload.wikimedia.org/wikipedia/commons/b/b0/Bengal_tiger_%28Panthera_tigris_tigris%29_female_3_crop.jpg",
    "bus": "https://upload.wikimedia.org/wikipedia/commons/6/63/LT_471_%28LTZ_1471%29_Arriva_London_New_Routemaster_%2819522859218%29.jpg",
    "car": "https://upload.wikimedia.org/wikipedia/commons/4/49/2013-2016_Toyota_Corolla_%28ZRE172R%29_SX_sedan_%282018-09-17%29_01.jpg",
    "cat": "https://upload.wikimedia.org/wikipedia/commons/4/4d/Cat_November_2010-1a.jpg",
    "dog": "https://upload.wikimedia.org/wikipedia/commons/archive/a/a9/20090914031557%21Saluki_dog_breed.jpg",
    "apple": "https://upload.wikimedia.org/wikipedia/commons/1/15/Red_Apple.jpg",
    "turtle": "https://upload.wikimedia.org/wikipedia/commons/8/80/Turtle_golfina_escobilla_oaxaca_mexico_claudio_giovenzana_2010.jpg",
    "flamingo": "https://upload.wikimedia.org/wikipedia/commons/b/b8/James_Flamingos_MC.jpg",
    "piano": "https://upload.wikimedia.org/wikipedia/commons/d/da/Steinway_%26_Sons_upright_piano%2C_model_K-132%2C_manufactured_at_Steinway%27s_factory_in_Hamburg%2C_Germany.png",
    "honeycomb": "https://upload.wikimedia.org/wikipedia/commons/f/f7/Honey_comb.jpg",
    "teapot": "https://upload.wikimedia.org/wikipedia/commons/4/44/Black_tea_pot_cropped.jpg",
    "vnu":"https://upload.wikimedia.org/wikipedia/zh/thumb/f/fd/Vanung_University_logo.svg/1200px-Vanung_University_logo.svg.png"
}

img_url = images_for_test_map[image_name]
image, original_image = load_image(img_url, image_size, dynamic_size, max_dynamic_size)

show_image(image, 'Scaled image')


```
