	- If the substring does not occur in the string, then it will output -1.

1. findKeyword("She's my sister", "sister", 0);
| Iteration | pns | before | after |
|:---------:|:---:|:------:|:-----:|
|     1     |  9  |   " "  | " "   |
|           |     |        |       |
|           |     |        |       |

2. findKeyword("Brother Tom is helpful", "brother", 0);
| Iteration | pns | before | after |
|:---------:|:---:|:------:|:-----:|
|     1     |  0  |   " "  |  " "  |
|           |     |        |       |
|           |     |        |       |

3. findKeyword("I can't catch wild cats.", "cat", 0);
| Iteration | pns | before | after |
|:---------:|:---:|:------:|:-----:|
|     1     |  8  |   " "  |  "C"  |
|     2     |  19 |   " "  |  "S"  |
|     3     |  -1 |        |       |

4. findKeyword("I know nothing about snow plows.", "no", 0);
| Iteration | pns | before | after |
|:---------:|:---:|:------:|:-----:|
|     1     |  3  |   "k"  |  "w"  |
|     2     |  7  |   " "  |  "t"  |
|     3     |  22 |   "s"  |  "w"  |
|     4     |  -1 |        |       |