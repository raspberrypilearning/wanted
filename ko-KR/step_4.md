## 이미지 스타일링하기

포스터의 이미지를 멋지게 개선시켜 봅시다.

+ 현재 `<img>` 태그에는 CSS 속성이 없으므로 추가해 보도록 하겠습니다.
    
    아래 CSS 코드를 div 밑에 추가하세요.
    
        img {
        
        }
        
    
    ![스크린샷](images/wanted-img-css.png)

+ 이제 이미지의 CSS 속성을 중괄호 사이에 추가할 수 있습니다.
    
    아래 코드를 CSS 파일의 img 안에 넣어 이미지의 폭을 설정할 수 있습니다:
    
        width: 100px;
        
    
    폭이 100 픽셀이 되도록 이미지의 크기가 변하는 것을 볼 수 있습니다.
    
    ![스크린샷](images/wanted-img-width.png)

+ 아래 코드를 추가하여 이미지에 테두리를 추가할 수 있습니다. 
    
        border: 1px solid black;
        

+ 보시다시피 지금 이미지와 테두리 사이에 공간이 없습니다.
    
    ![스크린샷](images/wanted-img-border.png)
    
    이미지 주위에 아래와 같이 여백을 추가하여 문제를 해결할 수 있습니다. 
    
        padding: 10px;
        
    
    padding은 내용(이 경우에서는, 이미지) 과 경계 사이의 공간을 의미합니다.
    
    ![스크린샷](images/wanted-img-padding.png)
    
    패딩을 `50px`로 변경하면 어떻게 변할까요?