# fiction_generator
> Fiction generator with Tensorflow.
> 模仿王小波的风格的小说生成器

![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg) ![PRsWelcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg) ![PythonVersion](https://img.shields.io/pypi/pyversions/Django.svg)

## Dependences

* Tensorflow 1.5
* Jieba 0.39
* Python 3.6
* Pre-trained word vectors
  * 下载预训练的中文词向量 [wiki.zh.vec](https://github.com/facebookresearch/fastText/blob/master/pretrained-vectors.md) 到根目录

## Usage

### Training:

```sh
python main.py
```

### Inference:

```sh
python main.py --seed "the_seed_sentence"
```

## Examples

```
----- diversity: 0.2
----- Generating with seed: "那一天我二十一岁"
那一天我二十一岁。　　那天和陈清扬在，有了捆巴西的撵得明白，我就一头，我就这样被我的一个，他说，还说，交待材料最有的。我说：我的工具，我的腰，我说，这样刺激性。她还说
，我把看过后，一股红晕了。她他们和我就像，回到了。我父亲是我就，有他的许可，我的腰变得的脱都，只掸回来。你就这样是：我在看法，可是她进穿着急匆匆，和了也可以去了。　　
陈清扬说，当时她总穿着干的事的偷鸡摸狗，感觉。我拿张清扬。结论到了犯罪的这不折不扣牛，眼睛都背了一身，但是她说，我们：不怎么，她看那么住了。　　陈清扬说，她到我在我搞
了，告诉我的腰很，但是他说，不怕，你说她是破鞋。当然的我也活，我说，这样刺激性。她还说，我把看过后，一股红晕了。她他们和我自己。后来她用破鞋，吃不上了她说，她说，也这
么。我请，要这么有了。我的陈清扬出不眼睛冲。我说，她说，她说，她说，她说，碰上他也说，交待材料最有的。我说：我的腰和尚。隔了心硬。屁股久久的一个。我们说，女人还有。把
我和骂我和陈清扬的章风。风从所有色胆包天。色胆包天她色胆包天看看，她走开了我的样子，他丝毫是不着，，她脸上快，罗小四领街子越坎；她还自己来。我们爬了我们。　　倒退农场
又很交待材料的要什么也对不折不扣。后来后又没给了，但是没有在向做，

----- diversity: 0.5
----- Generating with seed: "那一天我二十一岁"
那一天我二十一岁。　　罗素在陈清扬在第二次在人称做受过了打死。她说我原本钱起鱼我也什么。但是她忽然。　　人保组了像这么解释，这样，让说，在在我的许可，我说，要这么怀疑
了。　　后来斗争要来陈清扬，她是她在她的样子，她又她的许可，我说，怎么刺激性。谈到了还说，交待材料。我想爱了我们去了。但是有孩子地来。但是我在一声，提了了脸。她说，她
进了很这么。但是我还是。我说：不行了出来的我们都这样的那都这样。我说她，就有了，我们有儿老爹干的事，捆成她依旧，我听：　　那天下午天色了鱼了一万元，再就那么口气，本书
每个。喜欢了我拿了。　　陈清扬说，有时候我身上房门，陈清扬叫斗笠绳夺，然后后军代表，身上挂了她分开的。她脸上之前拉遗忘的我写，要我妈，做我妈，她说，交待材料最有的。，
领导她的交待材料最有的。我说我借了，但是他总是。我还过去，就有一只白。她告诉我我们也不回头，如果他看说呸掉了，但是有我的腰，有孩子有在那里解释，而她说，暴露他。汽车。
只有人到了我们。　　我和陈清扬出章风。风从，色胆包天，色胆包天，色胆包天，色胆包天，我的我可以这种，他又来了。这种和个军民共建服务员上破开水，如果是本人也不理解。那因
为她根本干我，但是这件了。我还组织，就不会牛角，她就不知想起：你们，而且她进穿着急匆匆，和了也和了

----- diversity: 1.0
----- Generating with seed: "那一天我二十一岁"
那一天我二十一岁和房子和一个在重温的陈清扬在二三队后，农场后，那在了那很这，但是她脸上。有说这的。那时节有他紧紧的。我和云南，重温里起来，我们是因为了同　后来还是人这
些解释，这是之间使，因此弃暗投明了红色差。后来她说也不坏，几乎打开我没有人，头发黑他去到山上去。后来她用自己有相同。我和后腰又阿伧，二是，色胆包天看看，她走开了好了，
有像你和交待，也不人家都当场了，所以凑我，但是材料。我们我们胡说八道陈清扬，她也我从她去了。　　陈清扬说，我天资了一切她去。我可以快了。我的陈清扬像不失去；他说，人说
上儿女小说要说，要我和我的破鞋。　　我在云南还重温，这也不凶恶，说也竹板，忽然模样的的。和尚了一切要这样病。可以乳头干疼了。　　1喂什么东西的事。她不是这种有着。我把
证明她不是破鞋，说了在山上之感了一　　1、什么等正“闪过了鱼。她半截那一个人，她去找，什么队长是可以又不知，但是部流进又是我都又很多材料，她不离开了。和了蓑衣就是队。
山上上山上也以后。但是挣了。孽就是破鞋：，倒去了我们，我说她也这件了。还要摔还稀烂，禁不住发红，她了能我，人保组非常的郭死，马上我和挣扎梳成，而在了几千亩，她说她三闷
儿，回到眼睛无知，，到了军民共建，我就向天明去，有大家人我们去了奸。像有这样够着，那些材料人说了，就
```

```
----- diversity: 0.2
----- Generating with seed: "小和尚"
小和尚）　　我和陈清扬在，她的很在我搞了，但是她说，我们：不怎么算不上了，几乎我们斗争了，陈清扬说，她到我在更散弹枪，就如了。我和陈清扬拉去，爬了衬衣。这件，他们来装
好，乳房她去一层梳成，乳房不有她说，交待材料的说，而且思想就是应该。积极向上，使是这样住了，有一回我们友谊。她说：别忙，我把不大无知，包括她脸上！。她到山上去，我们都
是知道，度过了起来。等到我死，她说，她说，她说，碰上他也说，交待材料。我说：别忙？不会队来，为此人从来像了。我听了什么。我说她也更一把。还说我是碰上，你对她的破鞋，你
说她的破鞋。当然的我也活那件事，但是她也没有一个：，却干什么也不是破鞋，这样多半可到。我和陈清扬在章风。

----- diversity: 0.5
----- Generating with seed: "小和尚"
小和尚）　　我和陈清扬在房子，陈清扬则刘大爹很身上，把我死了衣服。我在清平找了一声，就让四野、鱼，就到手吃！我我，而且总说很不坏，回到南面里。我们，大家都这样病了奸。
当然有不能会了。我的后腰，他追了猪场，几乎那时我，人到了我的我，但是我是一声，提了了我写，这样就是这样解释，而没人考大学椅子，我承不承认，后来当地农场，飞到我的样子，
我搞了打针，提了了现象的各种。我说：别忙老婊子。上午陈清扬说，她说我三闷儿，要说了。这种的个着，这我是她女儿了。对了一些借给我，我还队里，我就向我之陈清扬的不着了。我
在十五找我，我把我的许可够了。　　陈清扬说，那一刻我到了回到裤子，然后我正取烟来，回下身的好。假如当初本书了。　　陈清扬说，她到我在陈清扬的刘大爹。风从，色胆包天，色
胆包天，色胆包天，色胆包天，色胆包天，天地间，天地间，天地间，天地间，天地间，天地间，天地间，天地间，天地间，天地间，天地间，天地间，天地间，天地间，天地间，天地间，
天地间，天地间，天地间，天地间，天地间，天地间，天地间，天地间，天地间地枪毙，她脸上之前她说我。我说了这篇，几乎我从来，我听了这篇，几乎那时就没有知道我过生日，有陈清
扬始终绿，我身上眼睛，也耷拉我狂吻，，她叫我之了，有一回。而且她不存在她很，我准备有没有学校的是。我听了自己，也对她的一个香喷喷，捆成难当不少去的她身上一样。

----- diversity: 1.0
----- Generating with seed: "小和尚"
小和尚，　　我写我没长时间了，可是，就好从，后来我总我的草房，我听了这篇。他就说我们去了。令郎好像有孩子后面，我自己是猜都，告诉我破鞋去出来。　　在美国时陈清扬屁股一
事，她也朝我们之了，我听：是承认在儿女都揍，这样可以不是把看了。只你贼说，也可以。后来的个人，我的他们够了。坏分子去看了很多材料，最后他说这交待材料。副本一个人这些，
东西上既凶恶。她说道一听的一样。那时是哭的，也他在她的黄金时代后了怪叫学，已经的其中不能的。交待我有我火把。脐窝了她来。她有这种抵触情绪迸捣了。　　陈清扬说，是清平我
赶街，到她说，我也在她脸上的山上。我说：怎么，我已经快了学，屁股说我，对真是做不多，的承认了儿女的是不一样。还她又，有孩子。一位有重大。还有了儿女到，孽了很被我的但是
这件得不一样。我只好她不理解：　　她在这么还没，我和陈清扬的章风。风从所有色胆包天，色胆包天，色胆包天，色胆包天，她地讨厌，所以如陈清扬和了说，晚上夜里搞。　　2哇。
拿了到我，但是像叫说，我和不肯去我，但是没有本书了。而且，还这些东西，不像就死不这种。但是现在也是一个香喷喷，捆成睾九不少去，抽完到处可能，我也感冒，她就站找自己被，
那里能X光了。　　陈清扬说，她到我的我爸爸。知道了她怎么她清白，也这样随时随地，恬不知耻
```

## Model

![model](assets/model.png)

![graph](assets/graph.png)

## Licence

MIT License
