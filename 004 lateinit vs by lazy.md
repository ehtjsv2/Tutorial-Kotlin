### lateinit이란?
> * 나중에 초기화 해야할 경우
> * String만 가능

### by lazy란?
> * 어떤 연산의 결과를 초기값으로 하고싶어서 초기값을 나중에 해야할 경우 사용


#### 예시
```kotlin
lateinit var inputValue : String
val x : Int by lazy { inputValue.length }
inputValue = "Initialized!"
println(x)
출처: https://holika.tistory.com/entry/내-맘대로-정리한-Kotlin-lateinit과-by-lazy의-차이점 [Uing? Uing!!:티스토리]
```
