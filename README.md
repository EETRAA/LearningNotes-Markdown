# LearningNotes-Markdown
Snippets


# hi
> q
> 
> ==gsydhhxbx== <br>
> fubudbduu

---
***

- [ ] nice
    - [ ] checkbox 1
    - [ ] checkbox 2
- 1. 1
- 2. 2
- 3. 3
    - 3.3.1
    - 3.3.2

_italic_

__bold__

***bold&italic***

~~Strikethrough~~


> 1. [愛情](#aiqing)
> 2. [成長](#chengzhang)
> 3. [可愛](#keai)

<hr>
<span id = "aiqing" style = "color:tomato;font-size:24">愛情</span>
<hr>


[XXXX](#jump)
<span id = "jump" style = "color:red"> hello world</span>
![hi](https://shared.ydstatic.com/images/favicon.ico)

[mermaidmarkdown辅助](https://mermaid-js.github.io/)


### ==以下是流程图==
```
graph TB
%%comments like this
    0000[Before Christ?]
    1833[1983年首次发现半导体现象]
    1904[1904年电子管]
    1947[1947年第一块晶体管诞生]
    1952[1952年TEXAS INSTRUMENTS KICKED IN]
    1957[1957仙童半导体创立]
    
           0000
    0000-->1833
    1833-->1904
    1904-->1947
    1947-->1957
    subgraph one
    one1-->one2
    end
    subgraph two
    two1-->two2
    end
```

### ==以下是时序图==

```
sequenceDiagram
    participant John
    participant Alice
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!


```
### ==以下是甘特图==
```
gantt
       dateFormat  YYYY-MM-DD
       title Adding GANTT diagram functionality to mermaid

       section A section
       Completed task            :done,    des1, 2014-01-06,2014-01-08
       Active task               :active,  des2, 2014-01-09, 3d
       Future task               :         des3, after des2, 5d
       Future task2              :         des4, after des3, 5d

       section Critical tasks
       Completed task in the critical line :crit, done, 2014-01-06,24h
       Implement parser and jison          :crit, done, after des1, 2d
       Create tests for parser             :crit, active, 3d
       Future task in critical line        :crit, 5d
       Create tests for renderer           :2d
       Add to mermaid                      :1d

       section Documentation
       Describe gantt syntax               :active, a1, after des1, 3d
       Add gantt diagram to demo page      :after a1  , 20h
       Add another diagram to demo page    :doc1, after a1  , 48h

       section Last section
       Describe gantt syntax               :after doc1, 3d
       Add gantt diagram to demo page      :20h
       Add another diagram to demo page    :48h```
