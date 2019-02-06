# Green Leafy Herbs Classifier

When I go to the supermarket, I oftern feel confused when buying green leafy culinary herbs - they all look the same to me. I had to put a lot of effort into learnig how to recognize spinach. I can't afford to spend additional time and effort to learn other herbs. To make my life less miserable, I decided to call for the power of deep learning to the rescue. Let's make a neural net help me tell apart various culinary herbs.


Because I live in China, I will limit my classifier to herbs commonly available at vegetable markets in Beijing. Some of them don't have English names.

## Supported Leafy Greens

| ﻿Class 	|  Chinese 	|     Pinyin    	|      English     	|           Note          	|
|:-----:	|:--------:	|:-------------:	|:----------------:	|:-----------------------:	|
|     1 	| 白菜     	| bái cài       	| Chinese cabbage  	|                         	|
|     2 	| 菠菜     	| bō cài        	| spinach          	|                         	|
|     3 	| 菜心     	| cài xīn       	| choy sum         	|                         	|
|     4 	| 儿菜     	| ér cài        	|        ---       	|                         	|
|     5 	| 盖菜     	| gài cài       	| leaf mustard     	|                         	|
|     6 	| 芥蓝     	| jiè lán       	| Chinese broccoli 	|                         	|
|     7 	| 蒿子杆   	| hāo zǐ gān    	| Tricolor daisy   	|                         	|
|     8 	| 黄心菜   	| huáng xīn cài 	|        ---       	|                         	|
|     9 	| 茴香     	| huí xiāng     	| fennel           	|                         	|
|    10 	| 鸡毛菜   	| jī máo cài    	|        ---       	|                         	|
|    11 	| 韭菜     	| jiǔ cài       	| garlic chives    	|                         	|
|    12 	| 空心菜   	| kōng xīn cài  	| water spinach    	| same as 蕹菜 (wèng cài) 	|
|    13 	| 快菜     	| kuài cài      	|        ---       	|                         	|
|    14 	| 苦菊     	| kǔ jú         	| endive           	|                         	|
|    15 	| 芦笋     	| lú sǔn        	| asparagus        	|                         	|
|    16 	| 芹菜     	| qín cài xīn   	| celery           	|                         	|
|    17 	| 蒜黄     	| suàn huáng    	|        ---       	|                         	|
|    18 	| 蒜苔     	| suàn tái      	| garlic shoots    	|                         	|
|    19 	| 茼蒿菜   	| tóng hāo cài  	| crown daisy      	|                         	|
|    20 	| 豌豆苗   	| wān dòu miáo  	| pea shoots       	|                         	|
|    21 	| 莴苣     	| wō jù         	| lettuce          	|                         	|
|    22 	| 香菜     	| xiāng cài     	| cilantro         	|                         	|
|    23 	| 香芹     	| xiāng qín     	| parsley          	|                         	|
|    24 	| 小白菜   	| xiǎo bái cài  	| bok choy         	|                         	|
|    25 	| 西洋菜   	| xī yáng cài   	| watercress       	|                         	|
|    26 	| 叶生菜   	| yè shēng cài  	| lettuce          	|                         	|
|    27 	| 油菜     	| yóu cài       	| oilseed rape     	|                         	|
|    28 	| 羽衣甘蓝 	| yǔ yī gān lán 	| kale             	|                         	|
|    29 	| 竹笋     	| zhú sǔn       	| bamboo shoot     	|                         	|
