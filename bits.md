# Bits and Bytes

* C나 C++의 sizeof와 같은 것이 Go에도 있나요?
  * var i int
  * reflect.TypeOf(i).Size() --> 8 bytes
  * unsafe.Sizeof(i) --> 8 bytes
  * strconv.IntSize --> 64 bits

* Python의 bin()함수 처럼 정수를 2진수 문자열 표현으로 보고 싶은데요?
  * strconv.FormatInt(value, 2)
  * fmt.Printf("%b", value)

---

* Author: DongWoo Lee
* Email: leepro+golangtips@gmail.com
