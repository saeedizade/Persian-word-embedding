# 100d persian word embedding

## 1 unzip the files

## 2 example :

```
f = open('persian 100d word2vec.txt',encoding = 'utf8').readlines()
f = [[i.split('\t')[0],i.split('\t')[1].split(' ')] for i in f]
Dictionary = {}
for row in f:
    vec = [float(j) for j in row[1]]
    Dictionary[row[0]] = vec
Dictionary['سلام']

out : 
[0.17522548,
 1.0479571,
 -0.55577207,
 0.66442466,
 -0.41004157,
 -0.15076892,
 -0.44955105,
 -0.6388785,
 0.04511049,
 1.7739859
 ...
 ]
```
