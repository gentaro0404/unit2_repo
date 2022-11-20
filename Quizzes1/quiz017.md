# Quiz017

## Create a function that produces the average word length of the input list

## :program
```.py

def averageLength():
    return sum([len(i.strip()) for i in stringList]) / len(stringList)


stringList = ["Hello", "main"]
print(averageLength())


```

## Fig.1
![](quiz017.png)

##Flowchart:
![](quiz017_flow.JPG)
