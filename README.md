# gugong

`gugong` is an accessible data library for The Fobidden City located in Beijing, China.
The location of The Forbidden City is now called The Palace Museum.

While "The Fobidden City" might be more commonly known from the western world, the other name "GuGong", or literally translated as "The Past Palace", is more commonly used domestically in China. It's a shorter two-character-term "故宫" than the 3-character-term "紫禁城". The other possible reason might be today it's called "The Palace Museum", with the Chinese name as "故宫博物院". So it's just easy to call the first part of the name ommitting the word "musuem".

This library is built with historic facts and grounds collected from various open resources. It could be used as learning and educational purposes.

## Background

2020 is the 600 anniversity of the establishment of The Fobidden City. Besides,
it's a good timing to revisit the 600 years of history of the Ming and Qing dynasty together with The Fobidden City as part of the celebration.

## Install

If you have PIP, install the package with the one liner.

```shell
$ pip install gugong
...
```

## How to use the library

### Import the library

```python
In [1]: from gugong import GuGong

In [2]: gg = GuGong()

In [3]: gg.name
Out[3]: '故宫'

```

### Check the data in the library

```python
In [4]: for place in gg.places:
   ...:     print(place.name, place.arch_type)
午门 0
神武门 0
东华门 0
西华门 0
太和门 0
...

In [5]: for empire in gg.empires:
    ...:     print(empire.epoch_name, empire.temple_name)
    ...:
永乐 明成祖
洪熙 明仁宗
宣德 明宣宗
正统 明英宗
景泰 明景帝
成化 明宪宗
弘治 明孝宗
正德 明武宗
嘉靖 明世宗
隆庆 明穆宗
万历 明神宗
泰昌 明光宗
天启 明熹宗
崇祯 明思宗
福临 清世祖
康熙 清圣祖
雍正 清世宗
乾隆 清高宗
嘉庆 清仁宗
道光 清宣宗
咸丰 清文宗
同治 清穆宗
光绪 清德宗
宣统 清宣统皇帝
```

## TODO

* Simple Q&A
  * How to promounce some place or name in the Palace Museum
  * When is this built?
  * Who is this?
* External Interfaces
  * To Baidu for more smartness about knowledge?
  * To Amap for more smartness about geography

## Contact

If you find any mistake of inaccuracy in the data, please simply file an issue in GitHub.

If you have any concern on data infringement, please reach out to the author on the email saphires@163.com .
