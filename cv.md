### [rsschool-cv](https://github.com/MonroeLionel/rsschool-cv/tree/gh-pages "discript")
***


 #### Alex Monroe
***

#### contasct
**Phone:**  +987 654 3213
**E-Mail:** testmail@gmail.com
**Telegram**  @testtelegram
**Discor** testName

***

#### About myself

change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later change later 

***
### Skills
* html & css
* JS TS
* React 
* Git 

#### Code example

 
Coding in function countGrade. function accept 1 parameters scores, it's a number array. Your task is to count the grade distribution of the scores, to return an object like this:
```
{S:888, A:888, B:888, C:888, D:888, X:888}
```
Grading rules:
```
Grade S: Full marks(score=100)
Grade A: score<100 and score>=90
Grade B: score<90 and score>=80
Grade C: score<80 and score>=60
Grade D: score<60 and score>=0
Grade X: score=-1(The cheating guy gets a score like that)
```

```JavaScript
function countGrade(scores) {
  let a = { S: 0, A: 0, B: 0, C: 0, D: 0, X: 0 }
  scores.filter(f => {
    if (f == 100) {
      a = { ...a, S: a.S + 1 }
    } else if (f < 100 & f >= 90) {
      a = { ...a, A: a.A + 1 }
    } else if (f < 90 & f >= 80) {
      a = { ...a, B: a.B + 1 }
    } else if (f < 80 & f >= 60) {
      a = { ...a, C: a.C + 1 }
    } else if (f < 60 & f >= 0) {
      a = { ...a, D: a.D + 1 }
    } else if (f == -1) {
      a = { ...a, X: a.X + 1 }
    }
  })
  return a
}
```


