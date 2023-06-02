# sass 사용안함 scss를 사용함. scss --> 샤스라고 읽음. 🍍

# 🍻확장프로그램 깔기 ⬇ 

![image](https://github.com/myunzzhang/sass/assets/129017008/a8fbc53e-ac44-45ef-8f8b-f09ba5a20511)


# 🍻scss 컴파일 ⬇

![image](https://github.com/myunzzhang/sass/assets/129017008/76232ffa-03d1-4bd1-b446-bd06478964f9)


# 🍻css 위치 변경 ⬇

![image](https://github.com/myunzzhang/sass/assets/129017008/fb1c48dd-6a2d-40f1-aa69-2b7d49a7fe59)


# 🍻savePath:null이면 scss파일과 같은 위치에 style.css가 생긴다

![image](https://github.com/myunzzhang/sass/assets/129017008/76dacc50-50d5-4bba-a905-9bcc2ed2f848)


# 🍻~은 style.css를 의미 ⬇

![image](https://github.com/myunzzhang/sass/assets/129017008/79205e7e-3faf-445a-bf77-abd05948e518)


# 🍻scss파일이 있는 폴더의 상위요소에 생성 ⬇

![image](https://github.com/myunzzhang/sass/assets/129017008/46016930-7fd0-4d5f-990f-da456e7178e3)




--------------------------------------------------------------------------




# 🍻주석만들기 ⬇
## //주석은 css에 컴파인 x
##  /* */ 주석은 css에 컴파인 o

![image](https://github.com/myunzzhang/sass/assets/129017008/e4a76bd7-75b3-4181-bc7c-0bbf693fd731)




--------------------------------------------------------------------------




# 🍻변수만들기 --> $로 시작함, (영문, 숫자, -, _)만 사용할 수 있음. 숫자로 시작할 수 없음⬇

![image](https://github.com/myunzzhang/sass/assets/129017008/8f09d322-0f59-4faf-892d-3c25399a3d27)




--------------------------------------------------------------------------




# 🍻Partials(파샬)
--관련된것끼리 묶어서 분리 / 소스에 반복되는 부분들을 분리 분산시켜 모듈화 시키는 기능 

  * partials의 파일명은 _로 시작하며
  * 불러들일때는 @import '파일명',  이때 파일명에 _는 포함시키지 않고, 확장명도 포함시키지 않는다. 

💢 Scss는 _로 시작하는 파일은 컴파일하지 않는다.

![image](https://github.com/myunzzhang/sass/assets/129017008/a605d617-371b-4aca-93e0-cd738dce866d)




--------------------------------------------------------------------------




# @import --> 변수가 중복될 때 아래의 것이 적용된다. 

![image](https://github.com/myunzzhang/sass/assets/129017008/626659e6-2c30-4680-82d4-bf3bb8c94465)



# ⁉️ use --> 변수이름이 같을 때 에러발생, @use를 사용할때는 앞에 파일명을 추가해서 파일명.변수명

![image](https://github.com/myunzzhang/sass/assets/129017008/5e382de7-cde3-42cd-b4ae-e64148ccbcc2)


# 🦖 as 뒤에 별명을 붙여서 사용할 수 있다.

![image](https://github.com/myunzzhang/sass/assets/129017008/00b193ab-3b94-466e-9c72-9b5d35e347af)

 
# 🍳 @forward는 파샬을 묶어줌 (잘 사용하지 않음), style.scss에서는 _index.scss를 호출하여 

![image](https://github.com/myunzzhang/sass/assets/129017008/e4d9dee8-8a0a-47ca-81fd-29ee57f33373)


# 🍻 *(와일드카드)를 붙이면 이름을 생략할 수 있음

![image](https://github.com/myunzzhang/sass/assets/129017008/16105c52-9bc0-4887-9e85-2e20c9293184)



# 전역변수와 지역변수

![image](https://github.com/myunzzhang/sass/assets/129017008/c0d0a05e-8225-4b50-9470-1c84a2c25978)

# 보간법

![image](https://github.com/myunzzhang/sass/assets/129017008/b8637522-ce4b-4cd9-b5de-a09706664bbe)

