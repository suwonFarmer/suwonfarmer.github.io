## github 페이지 사용 방법 학습중

### 댓글
댓글기능은 어느정도 학습 후에 어떤 것을 사용 할 지 고르자
- _config.yml의 defaults에서 comments: true 하고 
- 사용하려는 comment 플러그인을 세팅 해야 한다. 
- utterances를 쓰자 - github id가 없으면 댓글을 못달지만 댓글 많이 달려봐야 관리만 귀찮아진다.
{: .notice--info}


### 폰트
폰트는 카페24 고운밤 폰트가 괜찮아 보인다.
assets/css/main.scss에 설정하면 되는 듯?


```css
// "Cafe24Oneprettynight"
@font-face {
    font-family: 'Cafe24Oneprettynight';
    src: 
        local('Cafe24Oneprettynight'),
        url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_twelve@1.1/Cafe24Oneprettynight.woff') 
        format('woff');
    font-weight: normal;
    font-style: normal;
}
```

