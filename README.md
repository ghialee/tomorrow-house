#오늘의 집

###1. GNB

-로그안을 하지 않은 경우

```html
<div class="button-group">
  <button
    class="gnb-icon-button is-search lg-hidden"
    type="button"
    aria-label="검색하기"
  >
    <i class="ic-search"></i>
  </button>
  <a
    class="gnb-icon-button is-cart"
    href="/"
    aria-label="장바구니로 페이지로 이동"
  >
    <i class="ic-cart"></i>
    <!-- <strong class="badge">5</strong> -->
  </a>

  <div class="gnb-auth sm-hidden">
    <a href="/">로그인</a>
    <a href="/">회원가입</a>
  </div>
</div>
```

-로그안을 한 경우

```html
<div class="button-group">
  <button
    class="gnb-icon-button is-search lg-hidden"
    type="button"
    aria-label="검색하기"
  >
    <i class="ic-search"></i>
  </button>

  <a
    href="/"
    class="sm-hidden gnb-icon-button"
    aria-label="스크랩북 페이지로 이동"
  >
    <i class="ic-bookmark"></i>
  </a>

  <a
    href="/"
    class="sm-hidden gnb-icon-button"
    aria-label="내 소식 페이지로 이동"
  >
    <i class="ic-bell"></i>
  </a>

  <a
    class="gnb-icon-button is-cart"
    href="/"
    aria-label="장바구니로 페이지로 이동"
  >
    <i class="ic-cart"></i>
    <strong class="badge">5</strong>
  </a>

  <button
    class="gnb-avatar-button sm-hidden"
    type="button"
    aria-label="프로필 페이지로 이동"
  >
    <div class="avatar-32">
      <img src="./assets/images/profile.jpg" alt="프로필" />
    </div>
  </button>
</div>
```
