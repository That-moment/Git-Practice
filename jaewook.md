
>   ### 저는 광주소프트웨어마이스터고에 재학중인
>   ## 1학년 4반 **송재욱**입니다!!

__생년월일__
 - 2008.07.28
__mbti__
 - INFJ

[instagram](https://www.instagram.com/haensol_/)

[github](https://github.com/976520)

```css
.dong-gu-ra-mi-12{
    width: 100px;
    height: 100px;
    border-radius: 50%;
    background-image: linear-gradient(200deg, #85C7FF 5%, #4A6BB2 25%, #1F2E48 90%);

    position: absolute;
    top: 310%;
    left: 25%;
}
```
```javascript
function paintGreeting() {
    const username = localStorage.getItem(usernameKey); //username 로드하기
    greeting.innerText = "Hello " + username + "!";
    greeting.classList.remove(hiddenClassName);
}

const savedUsername = localStorage.getItem(usernameKey); //Storage에서 username을 load

if (savedUsername === null) { //유저 정보가 없을 경우
    //form 보이게 
    loginForm.classList.remove(hiddenClassName);
    loginForm.addEventListener("submit", onLoginSubmit); // submit event 발생시 onLoginSubmit 호출
} else {
    paintGreeting();
}
```
