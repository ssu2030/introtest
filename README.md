# ssu2030.github.io
https://ssu2030.github.io

## Dongho Lee's github io

##### 개요
React로 만드는 자기소개서의 ProtoType이다.

##### 구현
[`jekyll`](https://nachwon.github.io/jekyllblog/)를 이용한 Template 수정 - 2021.11.05 <br>
`React`를 이용한 자기소개 page 구현 시작 - 2021.11.08

##### 참고
- 원작페이지: [vszhub.github.io/not-pure-poole/](vszhub.github.io/not-pure-poole/)
- [원작 git Repository](https://github.com/vszhub/not-pure-poole)
- [License](https://github.com/vszhub/not-pure-poole/blob/master/LICENSE.md) - MIT License

##### 수정사항
- Page build failure error on github
  - Your site is using the `relative_permalinks` configuration option.
  - 해결법: `relative_permalinks` 삭제하면됨

##### [React로 github.io로 연동하는법](https://www.hohyeonmoon.com/blog/react-js-github-pages-deploy/)
- react 페이지를 github io에서 hosting
- 문제점
  - remote를 하고 push하는 단계에서 제대로 push가 제대로 동작하지 않음
``` shell
remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
fatal: Authentication failed for 'https://github.com/ssu2030/ssu2030.github.io.git/'
```
- 해결방법: [Github push token 해결법](https://hyeo-noo.tistory.com/184)
- github은 gitlab과 다르게 ssh-key 관리 방법이 다르다. 따라서 현재 github.io에 만 ssh-key 
