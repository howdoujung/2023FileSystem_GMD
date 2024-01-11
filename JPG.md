JPG(JPEG) 썸네일 정리
---------------
###### JPG와 JPEG는 같은 파일 포맷이다. 기존에 사용하던 형식이 3글자 제한이라 JPG였다가, 현재 제한이 사라져 혼합 사용 중이다.
# JPEG 파일 구조
![0](https://github.com/howdoujung/2023FileSystem_GMD/assets/122142488/f4a2fbee-bba8-4ab7-aa80-03e9cc965130)

SOI(Start Of Image): 파일 확장자를 구분하는 2byte, JPG의 경우 0xFF, 0xC0~0XFE 값을 가진다. 파일 헤더 시그니처. JPG의 경우 FF(0X00) D8(0x01)이다. 
APPn: Offset 기준 0x02 APP0이다. 
