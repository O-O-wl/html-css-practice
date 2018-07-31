```css
@media(max-width:800px)
{
  #grid{
    display:block;
  }
  nav{
    border: none;
  }
}
```
**반응형 웹**을 만들기 위해서 **mediaQuery** 를 공부해야한다 .

```css
#grid{
  display: grid;
  grid-template-columns:   150px 1fr; //,를 써서는 안된다.
}
```

**ID selecter**를 사용하였고 , grid방식을 사용하였다. 그리드를 사용하기위해서는 원하는 요소들을 div 객체로 묶어주어야 하고,
**grid-template-columns:   150px 1fr**각각의 요소의 갯수만큼의 크기를 할당해주어야 한다.
