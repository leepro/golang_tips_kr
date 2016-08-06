# Bits and Bytes

* C나 C++의 sizeof와 같은것이 Go에도 있나요?
  * var i int
  * reflect.TypeOf(i).Size() --> 8 bytes
  * unsafe.Sizeof(i) --> 8 bytes
  * strconv.IntSize --> 64 bits
