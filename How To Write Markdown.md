# Get Started With Markdown

## Heading:
@ # 1. Show heading 1 for Name of file

@ ## 1.1. Show heading 2

@ ### 1.1.1. Show heading 3

@ #### 1.1.1.1. Show heading 4...

<br>

> Run .md: `Ctrl+K V`
> 
> Convert to .html: `Ctrl+P H`

<br>

## Show lists:

### Ordered List

1. Number1
2. Number2
3. Number3

### Unodered List:

* First1
    - Second1
    - Second2
        + Third1
        + Third2
    - Second3
* First2

### Todo list:

- [ ] todo list
- [x] todo list 2

## Drag and drop images:

![Mew](Mew.png "Mew")

![Or Copy link of Nanon](https://static1.dienanh.net/dienanhnet/202110/8ab3a227-ec95-478d-8ebc-942a8c5670be.jpg) 
Or 
![Nanon en][id]

[id]: https://static1.dienanh.net/dienanhnet/202110/8ab3a227-ec95-478d-8ebc-942a8c5670be.jpg "Nanon"


## Highlight something with:

`Highlight for me`

``Hightlight again``

## Block of code:

```
This is the block of code
```

Show code with syntax highlighting:

``` cpp
//This is my code
int main() {
    cout << "Get Started with Markdown" << endl;
    return 0;
}
```

## Adding link:

[Name link](link)

[Title Noting](https://www.youtube.com/watch?v=Hgucu1ch3mo)

## Horizontal Rules:
___
---
***

## Emphasis:

**Bold text**

__Bold text__

*Italic text*

_Italic text_

~~Strike through~~

Super^super^

Sub<sub>sub</sub>


## Math with Latex:

$$
Superscipt^{Superscript}
$$

$$
Subscript_{Subscript}
$$

$$
Text^S_A
$$

$$
\sqrt{fomula}
$$

$$
\frac{a}{b} \pm \sin x \ge -1 \le 0 ~~~\forall i
$$

$$
\sum_{i=1}^{n} X^3_i
$$


$$
\begin{array}
{rrr}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{array}
$$

## Quotes
> This is my quotes
>> And quotes in quotes

## Tables

| Col1  | Col2          | Col 3     |
| ----- | ------------- | --------- |
| Row 1 | This is row 2 | And Row 3 |

| Col1 Left                    | Col2 Center | Col 3 Right |
| :--------------------------- | :---------: | ----------: |
| And now I want to aligned it |     yes     |          no |

And you can table formater with `Alt Shift F`

