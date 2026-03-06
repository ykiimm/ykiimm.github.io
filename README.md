# 👋 안녕하세요, 제 홈페이지에 오신 걸 환영합니다!

## 📸 My Photo Gallery
여기에 제가 찍은 사진들과 기록들을 남길 예정입니다.

### 갤러리 모음

<div align="center" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 30px; padding: 50px 20px;">

  <div class="photo-wrapper">
    <img src="images/photo1.jpg" alt="사진 1" class="pop-img">
  </div>

  <div class="photo-wrapper">
    <img src="images/photo2.jpg" alt="사진 2" class="pop-img">
  </div>

  <div class="photo-wrapper">
    <img src="images/photo3.jpg" alt="사진 3" class="pop-img">
  </div>

</div>

<style>
  /* 사진이 놓일 기본 자리 (틀) */
  .photo-wrapper {
    width: 200px;
    height: 300px;
    background-color: #eee; /* 사진 로딩 전 배경색 */
    border-radius: 12px;
    /* overflow: hidden을 제거하여 사진이 밖으로 나올 수 있게 합니다 */
  }

  /* 실제 이미지 스타일 */
  .pop-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 12px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s ease-out, box-shadow 0.3s ease-out;
    position: relative; /* z-index 적용을 위해 필요 */
    z-index: 1;
  }

  /* 마우스를 올렸을 때 효과 */
  .pop-img:hover {
    transform: scale(2); /* 2배 확대 */
    z-index: 100; /* 주변 다른 사진들보다 위로 올라오게 함 */
    box-shadow: 0 20px 40px rgba(0,0,0,0.4); /* 떠 있는 느낌을 주는 진한 그림자 */
    border-radius: 8px; /* 확대 시 모서리를 조금 더 날카롭게 (선택 사항) */
  }
</style>

* **취미:** 사진 찍기, 코딩 공부
* **목표:** 멋진 나만의 웹사이트 완성하기
